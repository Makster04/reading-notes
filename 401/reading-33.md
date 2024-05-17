#  [Reading: Login and Auth](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-33)

## [What is Role Based Access Control (RBAC)](https://www.digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
1. **What is Role Based Access Control (RBAC)?** RBAC is a security model that restricts access based on user roles within an organization. Permissions are assigned to roles, not individuals, simplifying the management of user permissions, particularly in large organizations.
2. **Share some an example of RBAC including all possible CRUD operations and correlating roles.** In an inventory system, roles like Admin, Manager, Employee, and Viewer have distinct CRUD permissions. For example, Admins have full CRUD access, Managers can create, read, and update, Employees can create and read, and Viewers can only read.
3. **What are the Benefits of RBAC?** RBAC provides improved security, simplifies administration, ensures regulatory compliance, enhances operational efficiency, and enforces the least privilege principle by granting users only the access necessary for their roles.

## [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)
1. **What problem do Contexts aim to solve?**
* Contexts aim to solve the problem of prop drilling, where props need to be passed through multiple layers of components.
2. **What is one technique to try before useContext?**
* One technique to try before useContext is prop drilling, where state is passed down through component props.
3. **What hook complements useContext for complex applications?**
* The useReducer hook complements useContext for complex applications by providing a more structured way to manage state updates, especially when state logic becomes intricate and requires more than just simple value changes.

## Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.
* [react-cookie library](https://www.npmjs.com/package/react-cookie)
* [react-cookies component](https://www.npmjs.com/package/react-cookies)
1. **Describe some react-cookie features.** The react-cookie library offers cookie management functions, hooks for easy use in functional components, server-side support, and TypeScript definitions.
2. **Describe some react-cookies features.** The react-cookies component provides methods for cookie management, automatic state synchronization with cookies, context API support, and browser compatibility.
3. **Which library would you prefer would you prefer? Why?** Preferred Library: react-cookie (Convenient useCookies hook, Better server-side rendering support, Built-in TypeScript definitions for enhanced type safety)

4. ## Things I want to know
