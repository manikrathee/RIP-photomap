# RIP-photomap
Instagram deprecated photo map. Stub to make your own.

- Register a new app: https://www.instagram.com/developer/clients/manage/
- Using Client-side Implicit Auth (e.g. in your browser), get your code: `https://api.instagram.com/oauth/authorize/?client_id=CLIENT-ID&redirect_uri=REDIRECT-URI&response_type=token`
- Replace `token` with your code
- If running locally, use a browser extension like [this](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en) to enable XMLHTTPRequests.

You'll only get up to 20 unless your app is approved and un-sandboxed, GG.
