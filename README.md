# Sample upload files to AWS S3 via Laravel

## Installing dependencies with Composer

`composer install --prefer-dist --no-scripts`

## Copy .env file

`cp .env.example .env`

## Edit .env file

```
AWS_ACCESS_KEY_ID=changeme
AWS_SECRET_ACCESS_KEY=changeme
AWS_DEFAULT_REGION=changeme
AWS_BUCKET=changeme
AWS_USE_PATH_STYLE_ENDPOINT=false
```

## Browse

`http://your-ip-address:port/image-upload`
