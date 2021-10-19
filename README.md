

## Get Started

1. Clone this repo.

2. Install dependencies with `npm install`.

3. Run `npm run server` to start an instance of the server. A WalletConnect connection URI will be
printed to the console.

4. In a separate terminal, run `npm run client` to start an instance of the client. This will prompt
you to enter the WalletConnect connection URI from the previous step.

5. A session has now been established between the client and server. The server will then request a
single transaction to be signed, the client will sign and return it, then the session will end.
