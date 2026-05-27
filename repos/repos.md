## Repos

#### [OOS Firmware Updater](https://github.com/c4ffein/OOS-firmware-updater)
- Extract firmware from an OxygenOS ROM to a custom flashable firmwareupdater.zip

#### [RealWorld](https://github.com/realworld-apps/realworld/)
A [spec to an example app](https://github.com/realworld-apps/realworld/) including:
- an [openapi spec](https://github.com/realworld-apps/realworld/blob/main/specs/api/openapi.yml)
- both [api tests](https://github.com/realworld-apps/realworld/tree/main/specs/api) and [e2e tests](https://github.com/realworld-apps/realworld/tree/main/specs/e2e)
- a [documentation website](https://docs.realworld.show)
so anyone can easily reimplement [this Medium clone](https://demo.realworld.show).

This comes from a critique that most example apps are either too simple or too complex.
So reimplementing this app lets demo a framework as something as close to a "real" app as possible,
while staying simple enough to be easily reviewed.

I initially implemented the [Django Ninja version](https://github.com/c4ffein/realworld-django-ninja/), then gained ownership of the main repo when they were looking for maintainers. It is now a good example of [AI](https://docs.anthropic.com/en/docs/claude-code/overview)+[SDD](https://en.wikipedia.org/wiki/Spec-driven_development).

Most implementations are listed on [CodebaseShow](https://codebase.show).

##### I also maintain multiple implementations
| Link                                                                               | Part of stack     | Frameworks / libs                                                                              |
| :--------------------------------------------------------------------------------- | :---------------- | :--------------------------------------------------------------------------------------------- |
| [🔗](https://github.com/realworld-apps/angular-realworld-example-app)              | Frontend          | [Angular](https://angular.dev/)                                                                |
| [🔗](https://github.com/realworld-apps/nitro-prisma-zod-realworld-example-app)     | Backend           | [Nitro](https://nitro.build/) + [Prisma](https://www.prisma.io/) + [Zod](https://zod.dev/)     |
| [🔗](https://github.com/c4ffein/realworld-django-ninja)                            | Backend           | [Django Ninja](https://django-ninja.dev/)                                                      |
| [🔗](https://github.com/c4ffein/realworld-django-htmx)                             | Fullstack         | [Django](https://www.djangoproject.com/) + [HTMX](https://htmx.org/)                           |
| [🔗](https://github.com/c4ffein/realworld-demo-deploy)                             | Backend           | Pure python, in-memory only, used as [a demo backend for frontend implementation / test suites](https://api.realworld.show) - which enforces strong user isolation|

#### [NNVP](https://github.com/c4ffein/NNVP)
- This project allows you to generate Python code describing a Keras model by creating a graph representing the different layers in your browser

#### [c4ffein-configs](https://github.com/c4ffein/c4ffein-configs)
- Quick setups and config files for different environments

#### [txt2pdf](https://github.com/c4ffein/txt2pdf)
- Convert Markdown files to PDF in Python with optional custom CSS

#### [writings](https://github.com/c4ffein/writings)
- Trying to fight my perfectionism and start writing in public
- Also deployed in a clean state at [writings.cafeine.dev](https://writings.cafeine.dev)

#### [c4ffein/puzzles](https://github.com/c4ffein/puzzles)
- Links to puzzles I enjoyed solving, and solutions for some

## Contributions to other projects
*Projects I enjoyed contributing to*

#### [Parsec Cloud by Scille](https://github.com/Scille/parsec-cloud)
- A self-hostable cloud storage service with nearly full end-to-end encryption. See the [documentation](https://docs.parsec.cloud/en/latest/architecture.html).

#### [Djano Ninja](https://github.com/vitalik/django-ninja)
- Far more [KISS](https://en.wikipedia.org/wiki/KISS_principle) than [Django Rest Framework](https://github.com/encode/django-rest-framework), dropped [some small PRs](https://github.com/vitalik/django-ninja/pulls?q=is%3Apr+author%3Ac4ffein), I really enjoyed working with that framework and pushed for its adoption at some companies.

## Small projects I only use myself

### Reusable code

- **[`1files-js`](https://github.com/c4ffein/1files-js)** Monorepo collection of short js libs I used, either developed by myself or just found and modified according to my needs
- **[`python-snippets`](https://github.com/c4ffein/python-snippets)** Python snippets that don't deserve to get released on PyPI

### [Python cli utils](https://github.com/c4ffein/c4ffein/blob/main/repos/repos-python-cli-utils.md)
[A collection of KISS Python cli tools that each fit in one file.](https://github.com/c4ffein/c4ffein/blob/main/repos/repos-python-cli-utils.md)

### [Tools living on my servers](https://github.com/c4ffein/c4ffein/blob/main/repos/repos-self-hosted-tools.md)
[Decided I'd have more fun also vibe coding (still reviewing once before prod ofc) the tools that live on my servers.](https://github.com/c4ffein/c4ffein/blob/main/repos/repos-self-hosted-tools.md)

### pure sh helpers
- [bssh](https://github.com/c4ffein/bssh) - KISS pure-shell helper to make your ssh connections persistent in case of network cuts, only requires GNU Screen to be available on the remote server

### [presentations](https://github.com/c4ffein/presentations) - Archive for some slides

### [Custom Docker images](https://github.com/c4ffein/docker-images) - Custom setups I needed

## Just for fun

#### [shaders](https://github.com/c4ffein/shaders)
- Just some shaders

#### [pyscotch](https://github.com/c4ffein/pyscotch)
- Vibe-engineered Python wrapper around [PT-Scotch](https://gitlab.inria.fr/scotch/scotch)

#### [xjsx](https://github.com/c4ffein/xjsx)
- A new way to generate React elements without jsx, inspired by pug syntax, compatible with Tailwind CSS, actually pure JavaScript - I had fun writing this, but feeling that I need to precise that you probably shouldn't use this

## Gists
- `.gitignore` https://gist.github.com/c4ffein/58c1dba80e5665d85112f3eab513a170
