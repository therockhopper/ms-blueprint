# POC for Microservice Pattern Template

## Getting Started
### Pre-requisites
- Node.js
- Podman

`podman machine start` -- start podman

### Install
- `npm i ` -- install node app dependencies
- `npm run start` -- start the app

### Build
- `podman build -t ms-service-template .` -- build the image.

### Run
Run the image `podman run -d -p 3000:3000 localhost/ms-service-template` 
- `-d ` -- detach
- `-p 3000:3000` -- expose port 3000

See the logs
`podman logs -f [container id]`

