# `<Login />` and `<Auth />`

## [What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

1.  What is Role Based Access Control (RBAC)?

Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

2.  Share some an example of RBAC including all possible CRUD operations and correlating roles.

Primary – the primary contact for a specific account or role. [R]
Billing – access for one end-user to the billing account. [CR]
Technical – assigned to users that perform technical tasks. [CRU]
Administrative – access for users that perform administrative tasks. [CRUD]

3.  What are the Benefits of RBAC?

Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.

[react-cookie library](https://www.npmjs.com/package/react-cookie)

[react-cookies component](https://www.npmjs.com/package/react-cookies)

1.  Describe some `react-cookie` features.

Adds a cookieProvider context and hooks to get/set cookies in react. You can easily do CRUD on your cookies with the useCookies() hook.

2.  Describe some `react-cookies` features.

Appears to add cunctonality for working with cookies in react class components. The docs describe quite a few functions wrapped into a `cookie` class instance. `cookie` has functions like `save, load, loadAll` and more.

3.  Which library would you prefer would you prefer? Why?

Technically `react-cookie` has many more downloads and marketed as a functional react components solution, while the latter has 10 times less downloads per week and is marketed towards class components.. The second library does not look to be any lesser than the first but my preference would probably go to using the hook in my functional components.

### Reflection

I would like to know more about cookies. I know they can be used for many things and im pretty sure auth, preferences, and settings are some of them.
