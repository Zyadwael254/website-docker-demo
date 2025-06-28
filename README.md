# website-docker-demo
"A simple Dockerized web app demonstrating image build, push to Docker Hub, and container deployment."
## Prerequisites
- Docker
- Git
## Getting Started

```bash
# Clone the repo
git clone https://github.com/menamagdy/your-repo-name.git
cd your-repo-name

# Build the image
docker build -t zyadwael/web-app .

# Run the container
docker run -d -p 8080:80 zyadwael/web-app
## Docker Hub
Pull the image:
```bash
docker pull zyadwael/web-app
