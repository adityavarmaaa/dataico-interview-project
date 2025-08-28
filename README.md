# Dataico Interview Project

This is my completed submission for the Dataico Interview Project - Software Engineer position.

## How to Run

### Prerequisites
- Java 11+
- [Clojure CLI tools](https://clojure.org/guides/install_clojure)
- Node.js & npm

### Backend (API Server)
From the project root, run:
```bash
clojure -A:dev
```
This starts the backend server (default: http://localhost:3000).

### Frontend (Fulcro / Shadow-CLJS)
In a separate terminal, run:
```bash
npm install
npx shadow-cljs watch app
```
This compiles and serves the frontend on: http://localhost:8000

### Tests
```bash
clojure -A:test
```

---
Thank you for reviewing my submission.
