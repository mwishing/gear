# Change Log

All notable changes to this project will be documented in this file starting from version **v1.0.0**.
This project adheres to [Semantic Versioning](http://semver.org/).

-----

## [1.4.1] - 2017-04-24

**Changed:**

- Remove unnecessary error constants.

## [1.4.0] - 2017-04-23

**Changed:**

- Refactor `gear.Error` type. It is more powerful!

## [1.3.1] - 2017-04-12

**Changed:**

- Ignored `"context canceled"` error.
- Added more examples.

## [1.3.0] - 2017-03-28

**Changed:**

- Support Form body parse.
- Improve project structure.

## [1.2.0] - 2017-03-19

**Changed:**

- Add `Response.Status()`, `Response.Type()`.
- `Context.Status` and `Context.Type` will not return value now.

## [1.1.3] - 2017-03-15

**Changed:**

- Improve code.

## [1.1.2] - 2017-03-14

**Fixed:**

- Fix Logging middleware https://github.com/teambition/gear/pull/19 .

**Changed:**

- Add more document.

## [1.1.1] - 2017-03-11

**Changed:**

- Change default BodyParser's `MaxBytes` to `2MB`.
- Add more document.

## [1.1.0] - 2017-03-08

**Changed:**

- Simplify ctx.Timing method: `func (*Context) Timing(time.Duration, fn func(context.Context)) error`

## [1.0.5] - 2017-03-08

**Fixed:**

- Fix CORS middleware https://github.com/teambition/gear/pull/17 .

## [1.0.4] - 2017-03-05

**Fixed:**

- Fix logging middleware that should init structured log when start.

## [1.0.3] - 2017-03-05

**Fixed:**

- Fix Context.WithContext method that maybe recursive.

## [1.0.2] - 2017-03-02

**Fixed:**

- Fix Error.String() method that Error.Meta may be invalid utf-8 bytes.

## [1.0.1] - 2017-03-01

**Fixed:**

- Fix and improve Content-Disposition which is used by ctx.Attachment.
- Update Readme document.

-----

## [1.0.0] - 2017-03-01
