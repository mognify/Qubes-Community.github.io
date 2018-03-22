### 1. About

We are an independent volunteer community striving to build and improve end-user content for [Qubes OS](https://www.qubes-os.org/), such as guides, documentation, code & scripts, tips, ...

**This project's tasks are**

* to make it easier for Qubes OS users to submit documentation, tips, suggestions and more generally, any resource related to the Qubes OS project. Despite the project being hosted on GitHub, knowing git is not a requirement.
* to assist in getting documentation contributions QA'd and potentially submitted to the [official QubesOS documentation](https://www.qubes-os.org/doc/).
* to host, or link to projects, documentation, code, or resources, which are better suited to be distributed in the Community.
* to build a larger community around the Qubes OS project.

The reviewer team is quite small at the moment so any help is warmly welcomed !

**Disclaimer**: this site is run by volunteers. The Qubes OS Project is not affiliated with this site and does not endorse the content of any of these pages. The members of this community are Qubes users so they obviously focus on security but there's no guarantee about the content published in this site so use it at your own risk.

### 2. Content

User contributed Documentation and code/resources are respectively in the `docs/` and `code/` subfolders of the ['Contents'](https://github.com/Qubes-Community/Contents) repository. Ongoing submissions, reviews and QA are in [Issues](https://github.com/Qubes-Community/Contents/issues) and [pull requests](https://github.com/Qubes-Community/Contents/pulls) before new content is accepted  in the repository (see section [Contributing](#contributing) below).

Documentation planned for submission to the [official qubes-doc repository](https://github.com/QubesOS/qubes-doc) is discussed in [pull requests](https://github.com/Qubes-Community/qubes-doc/pulls) of our [forked qubes-doc](https://github.com/Qubes-Community/qubes-doc) repository.

The project hosts various projects which have their own repositories. They are referenced where appropriate in the README.md files in `code/` categories subfolders. Alternatively you can search them through the project's [main github page](https://github.com/Qubes-Community). 


<a name="contributing"></a>
### 3. Contributing

Anyone is welcome to submit content they deem fit for inclusion in this community effort (or potentially in the official Qubes documentation). As Qubes OS users we value privacy and security so please keep the project's [collective vision](/strategic-statement.md) in mind when submitting new content.

Contributing content is done:

- by submitting pull requests (a relatively easy process - see ["learning git"](#learning-git) below).
- or, for users not comfortable with git, by [creating a new an issue](https://github.com/Qubes-Community/Contents/issues) in the ['Contents'](https://github.com/Qubes-Community/Contents) repository. After optional discussion in the issue's thread and after the content is deemed fit for submission a community member will create a pull request on your behalf and take care of everything "git"; alternatively - if you prefer - he/she will help you creating your own pull request. Note however that in the former case you'll loose attribution/credit because github doesn't allow transferring a pull request's ownership.

The ['Contents'](https://github.com/Qubes-Community/Contents) repository is where most pull requests and issues are expected to be submitted, with the following exceptions:

- submitting pull requests to the [forked qubes-doc repository](https://github.com/Qubes-Community/qubes-doc): for contributors who want to submit content to the [official qubes-doc repository](https://github.com/QubesOS/qubes-doc) but who would like to get preliminary feedback/QA from the community.
- submitting pull requests or issues related/specific to the various project repositories living under this project.

### 4. Licensing

GPLv2 or later is required for any documentation content so that it matches QubesOS's official documentation. You are otherwise free to use whatever license you want when submitting code/programs, provided it fits in the open source git/fork model. Note that GPLv2 will be assumed if content is published without mentioning its license.

<a name="learning-git"></a>
### 5. Learning git for further contributions

It would ease the burden on community members if returning contributors who are not proficient with git learn the few basic concepts required to submit pull requests themselves.

This [github help page](https://help.github.com/articles/about-pull-requests) explains what pull requests are.

The official Qubes OS documentation [contribution guidelines](https://www.qubes-os.org/doc/doc-guidelines/) is then a good place to start with. It is based on contributing to the official qubes-doc repository but is applicable to this (or any other) project.

However the guide doesn't approach the problem of keeping a forked repository synchronized with "upstream" (eg. the official repository). This isn't a trivial problem ([github help page](https://help.github.com/articles/syncing-a-fork/)), especially when you have made changes in your forked repository ([stackoverflow post](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository)). So until you are proficient enough to understand the steps involved, a simple alternative that does not require command line usage is to delete the forked repository and re-fork it from upstream. This is a bit of a "nuclear" option though and you'll obviously loose any changes you've made in your forked repository.

