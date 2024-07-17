## Sauce Assessment

### Approach to Task
---

- [ ] Each Test requires a user to login and Logout except the invalid login
- [ ] Inputting values into the username and password fields.
- [ ] Clicking the login button.
- [ ] Verifying the successful login or checking for the presence of the error message upon failed login.
- [ ] The inventory list was checked to confirm successful login
- [ ] Error message was assert to confirm invalid login
- [ ] Set Up GitHub Actions for CI/CD:


---

### Libraries Used
---

- [ ] [Cypress v. 13.9.0](https://www.npmjs.com/package/cypress)

---

### Set Guide
---

- [ ] Clone repository to a desired location on your machine
- [ ] Navigate to the repository and open terminal inside the repository
- [ ] Use `npm install` or `npm i` to install the dependencies required to run the test from the `package.json` file. Alternatively, you can use `npm ci` to install the dependencies required from the `package-lock.json` file

---

### Execute the Test
---

To excute the test headlessly, run the following

- [ ] To run without flags: `npx cypress run`
- [ ] To run with a specific browser: `npx cypress run --browser <specify a browser>`
> Cypress collects the binaries of browsers that are installed on your system in addition to the    default electron browser


---
### Pipeline

---

A pipeline config was added to ensure that the test can run in a pipeline for every time there's push or merge to the main branch. Below is a screenshot of a sample result from the GitHub Actions execution.

![](pipeline-result.png)

---

### Contributor
---
[Ayanloye Segun Samson]()
[Software Quality Assurance Engineer]()
