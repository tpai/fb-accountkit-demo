# fb-accountkit-demo
Implement facebook account kit service into node server. (https://developers.facebook.com/docs/accountkit/web)

## How To Start

1) Create facebook app and its test app

2) Add account kit product

Be sure to add platform, pick website and put in URL.

For example:

```
http://localhost:8080
```

3) Fill up .env

```
APP_ID=[YOUR_APP_ID]
APP_SECRET=[ACCOUNT_KIT_APP_SECRET_KEY]
```

4) Install dependencies and run server

```
npm i
npm start
```

5) Done
