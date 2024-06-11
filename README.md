Real time form validation
>This app provides a user registration form with real-time validation for name, email, password strength, and role selection, ensuring data integrity and immediate user feedback.
Features

- Real-time Input Validation: Validates email format, password length, and required fields as you type.
- Password Strength Check: Displays error messages for passwords with less than 8 characters.
- Dynamic Role Selection: Offers predefined roles with validation.
- Form Submission: Submits and clears the form upon successful validation.

### Installation

1 - Clone the repository:

```bash
git clone https://github.com/paula-uxengineer/learnreact-form-validation-without-libraries.git
cd learnreact-form-validation-without-libraries
```

2 - Install dependencies:

- Using npm:

```bash
npm install
```

- Or using Yarn:

```bash
yarn install
```

### Initialice project:

- Start the development server: (using npm)

```bash
npm run dev
```

- Or using Yarn:

```bash
yarn dev
```

Open the app: Visit http://localhost:5173 in your browser to see the app in action.

### Technologies

- React: A JavaScript library for building user interfaces.
- TypeScript: A superset of JavaScript that adds static typing.
- Vite: A fast build tool and development server for modern web projects.
- SWC: A super-fast compiler for JavaScript and TypeScript.

Code Structure

- src/App.tsx: Main component that renders the form and manages state.
- src/validateEmail.ts: Utility function for validating email addresses.
- src/components/PasswordErrorMessage.tsx: Displays error message for weak passwords.
- public/: Contains static files like index.html.
