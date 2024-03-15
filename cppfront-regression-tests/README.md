# cppfront-regression-tests - An executable

The `cppfront-regression-tests` executable is a <SUMMARY-OF-FUNCTIONALITY>.

Note that the `cppfront-regression-tests` executable in this package provides `build2` metadata.


## Usage

To start using `cppfront-regression-tests` in your project, add the following build-time
`depends` value to your `manifest`, adjusting the version constraint as
appropriate:

```
depends: * cppfront-regression-tests ^<VERSION>
```

Then import the executable in your `buildfile`:

```
import! [metadata] <TARGET> = cppfront-regression-tests%exe{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
exe{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.cppfront_regression_tests.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
