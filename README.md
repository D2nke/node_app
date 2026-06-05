# my_apps_demo — Node branch

Demo app showing how to use [my_workflows](https://github.com/D2nke/my_workflows) reusable workflows in a Node.js (Express) stack.

---

## Pipeline

```
Test (Jest + coverage) → Security Scan (SonarQube + Mend) → Build Docker Image → Deploy to DEV
```

All steps are defined in `my_workflows` — this repo only provides the `with:` parameters.

---

## Running locally

```bash
npm install
npm test
node src/index.js
```

App runs at `http://localhost:8080`.

---

## Branches

| Branch | Stack |
|--------|-------|
| [master](https://github.com/D2nke/my_apps_demo/tree/master) | Java (Spring Boot + Maven) |
| [python](https://github.com/D2nke/my_apps_demo/tree/python) | Python (Flask + pytest) |
| [node](https://github.com/D2nke/my_apps_demo/tree/node) | Node.js (Express + Jest) |
