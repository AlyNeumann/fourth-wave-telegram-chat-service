# Fourth Wave Telegram Web App
### Running locally
1. **Obtaining Telegram api keys.**

Please visit this [page](https://github.com/telegramdesktop/tdesktop/blob/dev/docs/api_credentials.md) for details.

2. **Setup .env file.**

Manually copy Telegram api keys from previous step into REACT_TELEGRAM_API_ID and REACT_TELEGRAM_API_HASH at .env file.

3. **Install node.js & npm.**
Probably, you should use [nvm](https://github.com/nvm-sh/nvm).

4. **Install dependencies.**

```bash
npm ci
```
All TDLib files will be installed into node_modules/tdweb/dist/ folder. 

5. **Manually copy TDLib files into the public folder.**

```bash
cp node_modules/tdweb/dist/* public/
```

6. **Run the app in development mode.**

```bash
npm run start
```

Open http://localhost:3000 to view it in the browser.