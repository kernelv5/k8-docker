# Docker Installation on Macbook
This guide will walk you through the steps to install Docker on your Macbook.

1. Go to the [Docker website](https://www.docker.com/products/docker-desktop) and download the Docker Desktop for Mac installer.
2. Double-click the downloaded file to start the installation process.
3. Follow the prompts in the installer to complete the installation.
4. After the installation is complete, launch Docker Desktop from the Applications folder.


# Docker Installation on Macbook using Brew

Prerequisites
Before proceeding with the installation, you should have the following:

1. A Macbook running macOS High Sierra 10.13 or later
2. An active internet connection

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After Homebrew is installed, run the following command to add the Homebrew tap for Docker:

```
brew tap homebrew/cask
```

Now you can install Docker Desktop with Homebrew by running the following command:

```
brew install --cask docker
```

# Validation 

Open Terminal on your Macbook and run the following command to verify that Docker is installed correctly:

```
docker run hello-world
```
If Docker is installed correctly, you should see a message that says "Hello from Docker!" in your Terminal.



