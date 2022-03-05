# takagi.AI

## Install
`docker-compose.yml`
```yml
version: '3.8'

services:
  app:
    image: ghcr.io/iamtakagi/takagi.ai
    environment:
      HOST: 0.0.0.0
      PORT: 8080
      TZ: Asia/Tokyo
      USERS: iam_takagi
      TWITTER_CK: xxx
      TWITTER_CS: xxx
      TWITTER_AT: xxx
      TWITTER_ATS: xxx
    restart: unless-stopped
```

## LICENSE
MIT License.
