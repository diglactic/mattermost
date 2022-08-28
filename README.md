# mattermost

> ⚠️ Working Notes

## Requirements

- Heroku Buildpack: `http://github.com/kr/heroku-buildpack-inline.git`
- Postgres database

## Environment

```dotenv
BUILDPACK_URL=https://github.com/kr/heroku-buildpack-inline.git
DATABASE_URL=postgresql://username:password@host/database
FILE_SETTINGS__AMAZON_S3_ACCESS_KEY_ID=
FILE_SETTINGS__AMAZON_S3_BUCKET=
FILE_SETTINGS__AMAZON_S3_REGION=us-east-1
FILE_SETTINGS__AMAZON_S3_SECRET_ACCESS_KEY=
FILE_SETTINGS__DRIVER_NAME=local
MATTERMOST_DOWNLOAD_URI=https://releases.mattermost.com/5.32.1/mattermost-5.32.1-linux-amd64.tar.gz
SERVICE_SETTINGS__SITEURL=https://mattermost.diglactic.com
```
