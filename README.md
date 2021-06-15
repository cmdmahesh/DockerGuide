# DockerGuide

### 1) Get OS image from repo
~# dockerdocker pull ubuntu

### 2) Create container from image 
~# docker run -itd --name {container-name} {image-name}

### 3) Start docker container(if not running)
~# docker start {container-name}

### 4) Connect to the terminal of container 
~# docker attach {container-name}

### 5) View available images 
~# docker images

### 6) View available containers
~# docker container ls

### 7) View running containers
~# docker ps
