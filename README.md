# Bookstore Application — Internship Project

A React single-page bookstore application with authentication-aware routes and workflows for books, categories, users, profiles and a shopping cart.

## Technology stack

- React 18
- React Router 6
- Material-UI 4
- Axios
- Formik and Yup
- React Toastify
- React Testing Library

## Features represented in the application

- Login and registration screens
- Protected routes based on authentication state
- Book listing, creation and editing
- Category management
- User management and profile updates
- Shopping cart
- Shared authentication and cart context
- Form validation and toast notifications

## Getting started

### Prerequisites

Install a current Node.js LTS release and npm.

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Available scripts

| Command | Description |
|---|---|
| `npm start` | Start the development server |
| `npm test` | Run tests |
| `npm run build` | Generate a production build |

## Source layout

```text
src/
├── assets/
├── components/
├── constant/
├── context/
├── pages/
├── utils/
├── App.js
└── index.js
public/
package.json
```

## Implementation notes

- React Router handles client-side navigation.
- Authentication and cart state are provided through React context.
- Formik and Yup support form state and validation.
- Axios is included for HTTP communication.

## Repository hygiene

Install dependencies with `npm install`; do not commit the generated `node_modules/` directory. Keep environment-specific credentials outside version control.

## Maintainer

[Shyam Katariya](https://github.com/Shyam-Katariya) · [Portfolio](https://mediumturquoise-fox-633667.hostingersite.com/shyam.html)