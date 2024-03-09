# Changelog

## 4.1.0 - 2024-03-09

#### Added
- Formatting helper function (thanks, @kutyel)
    - `withOrdinalSuffix`


## 4.0.1 - 2022-02-27

#### Fixed
- `fromIsoString` function now provides detailed error messages when given out-of-range date parts (fixes #31)


## 4.0.0 - 2021-09-09

#### Changed
- `today` type signature relaxed from `Task Never Date` to `Task x Date` (thank you, [@kofigumbs](https://github.com/kofigumbs))


## 3.2.1 - 2020-06-08

#### Fixed
- `fromIsoString` function no longer gives redundant error messages


## 3.2.0 - 2019-09-11

#### Added
- Helper functions (thank you, [@2mol](https://github.com/2mol))
    - `min`
    - `max`


## 3.1.2 - 2018-10-04

#### Fixed
- `fromIsoString` function now has better error messages


## 3.1.1 - 2018-09-16

_Updated documentation_


## 3.1.0 - 2018-09-12

#### Added
- Language support
    - `formatWithLanguage` function
    - `Language` type
- Ordering helper functions
    - `compare`
    - `isBetween`
    - `clamp`


## 3.0.0 - 2018-09-10

#### Added
- `fromPosix` function

#### Removed
- `Date.RataDie` module


## 2.0.2 - 2018-09-06

#### Fixed
- Dates before year 1 are now handled correctly


## 2.0.1 - 2018-09-02

_Updated documentation_


## 2.0.0 - 2018-09-02

#### Changed
- `Month` and `Weekday` types were replaced by those from `elm/time`
- `toFormattedString` function was renamed to `format`

#### Removed
- Record helper functions
    - `toCalendarDate`
    - `toOrdinalDate`
    - `toWeekDate`


## 1.1.0 - 2018-08-31

#### Added
- `today` task


## 1.0.0 - 2018-08-21
