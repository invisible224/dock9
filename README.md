# Pull the image:

Use the docker pull command to download the image from the registry. Replace <image_name> with the actual name of the image:


docker pull <image_name>

docker pull ubuntu:latest

# 3. Create the container:

docker run -it <image_name> <command>

docker run -it ubuntu:latest bash

# 4. Verify the container:

docker ps

# 5. Another os

docker pull centos:latest

docker run -it centos:latest bash


docker pull alpine:latest

docker run -it alpine:latest sh
