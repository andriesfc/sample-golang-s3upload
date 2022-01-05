# Sample application to upload to S3 using the Amazon's SDK

## How to configure

Update settings via the `.env` file, or provide environment variables.

## Testing & running

I've tested the sample against [MINIO](https://min.io/) S3 storage implementation. It can be run locally docker, or by installing it
yourself (see the [docker-compose](docker-compose.yaml) file)

To start MINIO, run the following command in the project directory: 

```shell
docker-compose start minio
```
