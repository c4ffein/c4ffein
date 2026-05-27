# [RealWorld](https://github.com/realworld-apps/realworld/)
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
