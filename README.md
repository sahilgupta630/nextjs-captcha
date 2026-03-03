# Next.js Image CAPTCHA

This is an example implementation of a custom image-based CAPTCHA using Next.js and `iron-session`. It asks users to select specific images from a grid to verify they are human before allowing them to submit a message.

## Features

- Custom image grid CAPTCHA
- React state management for selections
- Secure session handling using `iron-session`
- Next.js API Routes for server-side verification

## Getting Started

First, make a copy of the `.env.example` file and name it `.env.local`:

```bash
cp .env.example .env.local
```

Update the `SESSION_SECRET` variable to a complex, at least 32-character string.

Then, install dependencies:

```bash
npm install
# or
yarn install
```

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Tech Stack

- **Framework:** Next.js
- **Session Management:** `iron-session`
