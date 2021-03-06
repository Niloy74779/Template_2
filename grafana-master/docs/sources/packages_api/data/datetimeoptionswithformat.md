+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "DateTimeOptionsWithFormat"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## DateTimeOptionsWithFormat interface

The type describing the options that can be passed to the [dateTimeFormat](./data/datetimeformat.md) helper function to control how the date and time value passed to the function is formatted.

<b>Signature</b>

```typescript
export interface DateTimeOptionsWithFormat extends DateTimeOptions 
```
<b>Import</b>

```typescript
import { DateTimeOptionsWithFormat } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [defaultWithMS](#defaultwithms-property) | <code>boolean</code> | Set this value to <code>true</code> if you want to include milliseconds when formatting date and time values in the default [DEFAULT\_DATE\_TIME\_FORMAT](./data/default_date_time_format.md) format. |
|  [format](#format-property) | <code>string</code> | Specify a [momentjs](https://momentjs.com/docs/#/displaying/format) format to use a custom formatting pattern of the date and time value. If no format is set, then [DEFAULT\_DATE\_TIME\_FORMAT](./data/default_date_time_format.md) is used. |

### defaultWithMS property

Set this value to `true` if you want to include milliseconds when formatting date and time values in the default [DEFAULT\_DATE\_TIME\_FORMAT](./data/default_date_time_format.md) format.

<b>Signature</b>

```typescript
defaultWithMS?: boolean;
```

### format property

Specify a [momentjs](https://momentjs.com/docs/#/displaying/format) format to use a custom formatting pattern of the date and time value. If no format is set, then [DEFAULT\_DATE\_TIME\_FORMAT](./data/default_date_time_format.md) is used.

<b>Signature</b>

```typescript
format?: string;
```
