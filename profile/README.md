# Open-source by Sneat.co
For setting up local dev environment see [sneat-devenv](https://github.com/sneat-co/sneat-devenv).

## [Sneat-apps](https://github.com/sneat-co/sneat-apps)

[Sneat.app](https://sneat.app) is an extandable platform that allows to build apps with extension modules.

The root repositories for developing sneat apps are:

- [sneat-apps](https://github.com/sneat-co/sneat-apps) - the frontend.
- [sneat-go-backend](https://github.com/sneat-co/sneat-go-backend) - the backend in Go language.

### Modules for sneat.app

You can develop your own module by creating a new repo from [sneat-mod-template](https://github.com/sneat-co/sneat-mod-template).

#### Built-in Sneat.app modules:
You can find source code for built-in modules in [sneat-go-core/src/modules](https://github.com/sneat-co/sneat-go-core/tree/main/modules).
They are built-in as most of other modules would depend on at least some of them (_specifically membership, contacts, calendar, etc._).

##### List of build-in Sneat.app modules

- [contactus](https://github.com/sneat-co/sneat-go-core/tree/main/modules/contactus) - contacts management (_a CRM module_)
- [memberus](https://github.com/sneat-co/sneat-go-core/tree/main/modules/memberus) - membership management
- etc...
