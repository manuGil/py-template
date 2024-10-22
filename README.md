# Python Package Template

A template for python packages for open science.

## Installation

Use [pipx](https://pipx.pypa.io/stable/installation/) to install `copier`, and
render the template.

```bash
# intalling copier
pipx install copier
```

## Usage

```python
# start a software project with this template
copier copy https://github.com/SS-NES/<repo>.git <path/to/project-directory>
```

```shell
# Changes to the meta template can be synced.  
# At the root of the software project, do:
copier update
```
> IMPORTANT: To enable updates, the sofware project must be a Git repository, and the status must show it is clean, i.e., no pending changes to commit.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)

## Acknowledgements

* [Serious Scaffold Python](https://github.com/serious-scaffold/ss-python)
* [Make a README](https://www.makeareadme.com/)


