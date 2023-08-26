## Getting Started

Create a .env.local file and add the following:
NEXTAUTH_SECRET= here you add a safe secret. Ex: open a terminal to generate a secret with the command --> openssl rand -base64 32
GITHUB_SECRET= Create at https://github.com/settings/apps --> New GitHub App
GITHUB_ID= Create at https://github.com/settings/apps --> New GitHub App

npm install

npm run dev

If you dont change anything there are two ways of signing in:

1. Username: Eddie, Password: nextauth
2. use your personal github account
