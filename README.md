# Module Templates to build on Safe Accounts

This repository contains different module templates to build on Safe Accounts based on different standards. These module templates are organized as git submodules and directories.

## Module templates

A developer can select any of these module template based on different module standards or the type of application.

### Safe Core Protocol specs

- [Safe App + Hook Module template](https://github.com/koshikraj/safe-whitelist-hook)
- [Safe App + Plugin Module template](https://github.com/zenguardxyz/safe2link-plugin)


### ERC-7579 specs

- [Safe App + Executor Module template](https://github.com/koshikraj/module-template-7579)
- [Safe App + Validator Module template](https://github.com/koshikraj/module-template-7579)

- [Module template by Rhinestone](https://github.com/rhinestonewtf/module-template)

### ERC-6900 specs

Not avaliable yet


## Usage

To use this git module repository, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone --recursive https://github.com/zenguardxyz/module-templates.git
    ```

2. Initialize and update the submodules to fetch latest code:

    ```bash
    cd module-collection
    git submodule --init --recursive
    git submodule update --remote
    ```


## Contributing
If you would like to contribute to this collection of Safe account modules, please follow these guidelines:
1. Fork the repository and create a new branch for your changes.
2. Make your modifications or additions to the modules.
3. Commit your changes and push them to your forked repository.
4. Submit a pull request to the main repository, explaining the changes you made.

## License
This collection of Safe account modules is licensed under the [GNU General Public License v3.0](LICENSE).
