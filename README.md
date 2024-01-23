# RDI Employee Library App

## Description

This web app allows RDI employees to view a catalog of books that employees keep in RDI offices and allow other employees onsite borrowing privileges. The intent is to facilitate free sharing of information among employees, as well as to create opportunities for discussion and mentorship.

## Prerequisites

- Node.js and npm (Node Package Manager)
- Vue CLI (Command Line Interface)
- Firebase CLI
- A Firebase account and project

## Installation and Setup

### Step 1: Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/pizzimenti/rdi-employee-library-vueapp.git
cd rdi-employee-library-vueapp
```

### Step 2: Install Node.js and npm

Download and install Node.js from [Node.js website](https://nodejs.org/). npm is included in the installation.

Verify the installation:

```bash
node -v
npm -v
```

### Step 3: Install Vue CLI

Install Vue CLI globally:

```bash
npm install -g @vue/cli
```

Verify the installation:

```bash
vue --version
```

### Step 4: Install Project Dependencies

Navigate to the project directory and install the dependencies:

```bash
npm install
```

### Step 5: Local Development

Start the local development server:

```bash
npm run serve
```

The app should now be running on [http://localhost:8080/](http://localhost:8080/).

### Step 6: Build for Production

Build the app for production:

```bash
npm run build
```

This creates a `dist/` directory with the production build.

### Step 7: Firebase Setup

Install Firebase CLI:

```bash
npm install -g firebase-tools
```

Log in to Firebase:

```bash
firebase login
```

Initialize Firebase in your project (select 'Hosting', configure as a single-page app, and use `dist` as the public directory):

```bash
firebase init
```

### Step 8: Deploy to Firebase Hosting

Deploy your app:

```bash
firebase deploy
```

The app is now deployed. Visit the provided URL to view it live.

## Usage

To use the app, simply provide RDI credentials (OAuth) to log in once deployed.

## Contributing

Reach out to Bradley Pizzimenti by email or on Teams for any contributions or inquiries.

## License

This project is licensed under the MIT License - see the [Open Source Initiative](https://opensource.org/licenses/MIT) for details.
