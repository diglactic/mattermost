# mattermost

> ⚠️ Working Notes

## Setup on Heroku

- Buildpack: `http://github.com/kr/heroku-buildpack-inline.git`
-

## Environment

```dotenv
BUILDPACK_URL=https://github.com/kr/heroku-buildpack-inline.git
DATABASE_URL=postgresql://username:password@host/database
FILE_SETTINGS__AMAZON_S3_ACCESS_KEY_ID=
FILE_SETTINGS__AMAZON_S3_BUCKET=
FILE_SETTINGS__AMAZON_S3_REGION=us-east-1
FILE_SETTINGS__AMAZON_S3_SECRET_ACCESS_KEY=
FILE_SETTINGS__DRIVER_NAME=local
```
