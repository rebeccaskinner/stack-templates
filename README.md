# Stack Templates

This repository contains templates for common project types that I work with.

## simple.hsfiles

This template will give you an application broken up into an "app" and "lib"
with tests.  It provides a default monad transformer stack with exceptions and
application config.

```
stack new test rebeccaskinner/simple -p "category:web" --resolver lts-13.19
```

## servant-echo.hsfiles

This template provides a basic echo server implementation using servant.  It
includes a monad transformer stack, service-pattern based logging, and a basic
unit test with Hspec-Wai and lifted expectations, including a logging handle the
allows you to set expectations on specific log messages.
