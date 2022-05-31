# balaji-jenkins

# Build Iamge

./gradlew clean build
./gradlew docker

# List all images

docker images

# Run as Container

docker run -d -p 8080:8080 {image_id}

# List all running Containers

docker ps

# Kill and Remove Container

docker kill {container_id}
docker rm -f {container_id}

# Remove image

docker rmi -f {image_id}
