```bash
docker run -w /tmp --ipc=host --mount="type=bind,src=$(pwd),dst=/tmp" --entrypoint="/tmp/node_modules/.bin/playwright" mcr.microsoft.com/playwright:v1.48.1 test
```