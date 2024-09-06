## Common Docker Commands

### Checking Docker Version
```bash
docker --version
```

### Pulling an Image
```bash
docker pull <image-name>
```

### Listing Images
```bash
docker images
```

### Deleting an Image
```bash
docker rmi <image-id>
```

### Running a Container
Start a new container from an image:
```bash
docker run <image-name>
```

To run the container interactively and attach to its shell, use the `-it` flag:
```bash
docker run -it <image-name>
```

### Listing Containers
- **Running containers**:
    ```bash
    docker ps
    ```
- **All containers (including stopped ones)**:
    ```bash
    docker ps -a
    ```

### Stopping a Container
```bash
docker stop <container-id>
```

### Removing a Container
You can only remove a container that is not running:
```bash
docker rm <container-id>
```

### Running Containers in Detached Mode
Run a container in the background (detached mode) using the `-d` flag:
```bash
docker run -d <image-name>
```


