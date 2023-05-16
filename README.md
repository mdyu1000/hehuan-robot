# hehuan-robot

## Disclaimer
This project is for personal learning use in NodeJS, Puppeteer, Docker, and Deep Learning (TensorFlow, CNN). It is not intended for any unlawful purposes. Any criminal or civil liabilities arising from the use of this project shall be borne by the user.

## Requirements
- Docker 
- Docker Compose
- **Note for Apple M1 users:** Please follow these [instructions](https://github.com/browserless/chrome#building-for-arm64-apple-m1-machines) to set up your environment.

  
## Usage
1. Update `docker-compose.yml` environment according to your needs.
2. Run the Docker container:

```
docker-compose build --no-cache hehuan-robot
docker-compose up
```