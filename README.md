# Artists Web Backend

## Technology

- Express
- Mongoose
- Cors
- JWT

## Base URL

The base URL for the API is: https://artists-web-api.vercel.app/api/v1

## Manual Installation

Clone the repo:

```bash
git clone https://github.com/RakibMojumder/artist-web-backend.git
cd artist-web-backend
```

Install the dependencies:

```bash
pnpm install
```

Set the environment variables:

```bash
cp .env.example .env
# open .env and modify the environment variables
```

## Commands

Running in development:

```bash
pnpm start:dev
```

## Environment Variables

The environment variables can be found and modified in the `.env` file.

```bash
PORT=
NODE_ENV=
MONGODB_URI=
JWT_ACCESS_TOKEN=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```
