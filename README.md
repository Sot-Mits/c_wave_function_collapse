WaveFunctionCollapse implementation in C 
========================================

*Based on the [ic-pcg's implementation of wave function collapse](https://github.com/ic-pcg/waveFunctionCollapse), itselft based on [Maxim Gumin's wave function algorithm](https://github.com/mxgmn/WaveFunctionCollapse).*

## Usage

* Given that I intend to use this library only for my upcoming game the scope of its usage is pretty low.
* Simply paste this in your 'CMakeLists.txt':
```
FetchContent_Declare(
    wave_function_collapse
    GIT_REPOSITORY "${wfc_location_or_link}"
    GIT_TAG "master"
    GIT_PROGRESS TRUE
)

FetchContent_MakeAvailable(wave_function_collapse)
target_link_libraries(${PROJECT_NAME} PRIVATE wave_function_collapse)
```

## References

* [Ic-pcg's implementation of wave function collapse](https://github.com/ic-pcg/waveFunctionCollapse)
* [Maxim Gumin's wave function algorithm](https://github.com/mxgmn/WaveFunctionCollapse)
* [Isaac Karth and Adam M. Smith paper presented at the Genetic and Evolutionary Computation Conference](https://adamsmith.as/papers/wfc_is_constraint_solving_in_the_wild.pdf)
* [Oskar Stalberg](https://twitter.com/OskSta)

## Credits and licences

Authors: 
* [Łukasz Jakubowski](https://github.com/woocashh) 
* [Maciej Kaszlewicz](https://github.com/NaraS91) 
* [Paweł Kroll](https://github.com/skrroll)
* [Stefan Radziuk](https://github.com/stefanradziuk)

This project is licensed under the terms of the MIT license.
