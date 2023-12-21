
# Social media

Social media app using Angular and Nestjs, the Node version used is 18.12.1

## Run Locally

Clone the project

```bash
  git clone --recursive https://github.com/HaroldMDiazVargas/socialMediaApp.git
```

### Frontend
Go to the frontend

```bash
  cd .\frontend\
```

Install dependencies

```bash
  npm install
```

Start local server on 4200

```bash
  npm run start
```

### Backend
Go to the backend

```bash
  cd .\backend\
```

Install dependencies

```bash
  npm install
```

Set env variables on .env file and start the server on 9000

```bash
  npm run start:dev
```

## Features
- Login/Signup using JWT Passport
- CRUD posts, set guards on backend for only author to delete and update
- Set guard on backend and frontent for logged users resources
- Soft deletion of posts records
- Responsive design using tailwind library 
- Sidebar component
- Infinite scroll
- Usages of pipes, directives, interceptors, validators


