#### Creating a dockerfile

1. Specify a base image
2. Run some commands to install additional programs
3. Specify a command to run on container setup

Dockerfile --> Docker Client --> Docker Server --> Usable Image!

#### What's the base image?

The base image is the starting point for the most container-based development workflows. Most base images are basic 
minimal Linux: Debian, Ubuntu.

#### To run docker port outside accessible

```shell
docker run -p 8080:8080 <image-id>
```