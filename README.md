# Python template

_Table of content, automatically updates on save via_ yzhang.markdown-all-in-one _._

- [Python template](#python-template)
  - [About the project](#about-the-project)
    - [Built with](#built-with)
  - [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
      - [In a completely new repository](#in-a-completely-new-repository)
      - [Into an existing repository](#into-an-existing-repository)
      - [Poetry](#poetry)
      - [Suggested VSCode extensions](#suggested-vscode-extensions)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contributors](#contributors)
  - [Acknowledgments](#acknowledgments)

## About the project

_One sentence summarizing the motivation and value proposition this project provides._

Generic Python VSCode template with opinionated configuration.

### Built with

_Frameworks used for this project._

## Setup

### Prerequisites

_Prerequisites for installation._

### Installation

_How to install._

#### In a completely new repository

```shell
git remote add template https://github.com/StephanSchmiedmayer/PythonTemplate.git
git pull template main
git reset $(git commit-tree HEAD^{tree} -m ".") && git commit --amend -m "Add template"
git remote rm template
```

Step by step explanation:

1. Add this repo as a remote repository called `template`:

   `git remote add template https://github.com/StephanSchmiedmayer/PythonTemplate.git`

2. Pull the template into your current branch:

   `git pull template main`

   Be aware that this will also add the MIT License of this project.

3. Squash all commits to a single initial commit:

   `git reset $(git commit-tree HEAD^{tree} -m ".") && git commit --amend -m "Add template"`

4. Remove template remote:

   `git remote rm template`

#### Into an existing repository

```shell
git remote add template https://github.com/StephanSchmiedmayer/PythonTemplate.git
git checkout template/main -- .gitignore README.md LICENSE.md .vscode/settings.json
```

#### Poetry

[Once per machine] Make sure poetry puts the virtual environment into this project, otherwise VSCode can have problems picking it up. For more info see [stackoverflow](https://stackoverflow.com/a/64434542).

`poetry config virtualenvs.in-project true`

#### Suggested VSCode extensions

- `njpwerner.autodocstring`
- `ms-python.black-formatter`
- `streetsidesoftware.code-spell-checker`
- `ms-vscode-remote.remote-containers`
- `ms-azuretools.vscode-docker`
- `ms-python.flake8`
- `donjayamanne.githistory`
- `visualstudioexptteam.vscodeintellicode`
- `visualstudioexptteam.intellicode-api-usage-examples`
- `ms-python.isort`
- `yzhang.markdown-all-in-one`
- `davidanson.vscode-markdownlint`
- `matangover.mypy`
- `christian-kohler.path-intellisense`
- `cs50.vscode-presentation-mode`
- `ms-python.vscode-pylance`
- `ms-python.pylint`
- `ms-python.python`
- `mukundan.python-docs`
- `donjayamanne.python-environment-manager`
- `kevinrose.vsc-python-indent`
- `avaly.restore-git-branch-tabs-improved`
- `lextudio.restructuredtext`
- `trond-snekvik.simple-rst`

## Usage

_How to use the software / library.
If necessary include any warnings about common problems / misusage._

## Testing

_How to execute the test suite._

## Roadmap

_Where is this project currently going?_

## Contributing

_How to contribute to the project._

## License

See [License.md](LICENSE.md).

## Contributors

[Stephan Schmiedmayer](https://github.com/stephanschmiedmayer)

## Acknowledgments

_Thank anybody who helped with this project._
