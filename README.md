# PSPhree_Public v.1.0
Unofficial Update of PS-Phive v3 by Leeful FOR PS4 FW 9.00

# News
Updated with latest GoldHen v2.4b18

# What is included in this version
1) New PSFree Exploit
2) Latest Beta Gold Hen Payload coded by SiSTR0 2.4b18
3) Linux Payloads for all consoles
4) Docker container that runs all the stack exposing the 8080 port

# Attention
The PSFree exploit is for 6.xx to 9.60 but this version of PSPhree have been only tested on PS4 FW9.00.


## Prerequisites
All you need is docker , you can install it downloading from the official website.
https://www.docker.com/products/docker-desktop/


# Running Your Docker Container with Docker Compose

This repository contains the necessary files to run your application in a Docker container using Docker Compose.

## Prerequisites

Before running the Docker container, ensure that you have the following prerequisites installed on your system:
- Docker: Follow the installation instructions for your operating system [here](https://docs.docker.com/get-docker/).
- Docker Compose: If you don't have Docker Compose installed, you can install it by following the instructions [here](https://docs.docker.com/compose/install/).

## Getting Started

Follow these steps to run the Docker container:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/KyrosWeb/PSPhree_Public.git
    ```

2. Navigate to the cloned repository directory:
    ```bash
    cd PSPhree_Public
    ```

3. Run the Docker container using Docker Compose:
    ```bash
    docker-compose up -d
    ```

   The `-d` flag runs the services in detached mode, meaning they'll run in the background.

5. Discover your remote ip
### For Linux User:
```bash
     ip addr show
```
### For Windows User:
- Press `Windows + R` to open the Run dialog.
- Type `cmd` and press `Enter` to open the Command Prompt.
- In the Command Prompt, run the following command to display the IP configuration:
    ```
    ipconfig
    ```
- Look for the IPv4 Address in the output.

### For MacOS User:
```bash
ipconfig getifaddr en0
```

4. Access your application:
   Once the container is running, you can access your application by navigating to `http://remoteip:8080` 

## Stopping the Container

To stop and remove the Docker container, run the following command in the repository directory:
```bash
docker-compose down
```

