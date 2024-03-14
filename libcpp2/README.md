# libcpp2 - A C++ library

The `libcpp2` C++ library provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `libcpp2` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libcpp2 ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = libcpp2%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libcpp2.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
