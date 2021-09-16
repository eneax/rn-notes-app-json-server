# rn-notes-app-json-server

JSON Server for my [React Native Notes App](https://github.com/eneax/rn-notes-app).

## Run this project locally

To run this project locally, you need to open two terminal windows:

- on the first window run `JSON Server` with the following command:

```shell
npm run db
```

- on the second window run `ngrok` with the following command:

```shell
npm run tunnel
```

## Note

Every time you start `ngrok`, you will get a new HTTP/TCP tunnel on random URLs/ports.
If you want to have custom subdomains and reserved domains, you have get the `ngrok` BASIC or PRO plan :)
