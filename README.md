# Stack Templates

This repository contains templates for common project types that I work with.

## simple.hsfiles

This template will give you an application broken up into an "app" and "lib"
with tests.  It provides a default monad transformer stack with exceptions and
application config.

```
stack new test rebeccaskinner/simple -p "category:web" --resolver lts-13.19
```
