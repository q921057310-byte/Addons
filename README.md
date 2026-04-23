<div align = center >

# Addon Index

This repository contains the metadata of the  
official addon index and related resources.

[![Button Documentation]][Documentation]

</div>

## Data

The following metadata is stored:

-   [`Index.json`][Index]   
    List of known addons, controls the Addon display in the built-in Addon Manager. See [the Index documentation][Documentation] for information on adding your Addon to this list.

-   [`Python`][Python]  
    Version-specific metadata.

    -   [`Allowed-Packages`][Packages]  
        List of allowed Python packages. To request that a package be added, [submit an issue here][Request].

    -   [`constraints.txt`][Constraints]   
        Constraints of the Python packages (auto-generated from `Allowed-Packages`), applied by the Addon Manager during dependency resolution to prevent Addon requirements conflicts.

    -   [`pyproject.toml`][Project]  
        Python environment configuration.

<!----------------------------------------------------------------------------->

[Constraints]: ./Data/Python/3.14/constraints.txt
[Packages]: ./Data/Python/3.14/Allowed-Packages
[Project]: ./Data/Python/3.14/pyproject.toml
[Python]: ./Data/Python
[Index]: ./Data/Index.json
[Documentation]: https://freecad.github.io/Addon-Academy/Guides/Publishing/Indexed
[Request]: https://github.com/FreeCAD/Addons/issues
<!----------------------------------------------------------------------------->

[Button Documentation]: https://img.shields.io/badge/Documentation-3b8ad9?style=for-the-badge&logoColor=white&logo=buffer

[Documentation]: https://freecad.github.io/Addon-Academy/Topics/Addon-Index/
