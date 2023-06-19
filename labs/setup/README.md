# COSC 404 Lab Setup

For COSC 404, the following must be installed on your machine:
 - JDK - JDK 19 is recommended
 - Docker Desktop
 - VSCode

Each lab uses the Java programming language and will create databases and other resources using Docker compose.

## Installing a JDK

A JDK of version 11 or above is required with JDK 19 recommended.

### Steps

1) [Download OpenJDK](https://jdk.java.net/19/). If you are on a Mac with M1 chip, download version `macOS/AArch64`.	
2) Unzip folder and setup environment variables. ([Windows instructions](https://java.tutorials24x7.com/blog/how-to-install-openjdk-17-on-windows), [MacOS instructions](https://java.tutorials24x7.com/blog/how-to-install-openjdk-17-on-mac))

## Installing VSCode

You may use any editor for Java code (e.g. Eclipse, IntelliJ), but the officially supported editor is VSCode.

### Steps

1) [Download VSCode](https://code.visualstudio.com/Download)
2) Install the `Extension Pack for Java`. This supports Java development and JUnit testing.
3) Install the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers). Visual Studio Code Dev Containers is an extension that lets you use a Docker container as a full-featured development environment.

## Installing Docker

Install Docker desktop on your machine that will allow for creating containers for the database systems used.

### Steps

1) [Download Docker Desktop](https://www.docker.com/products/docker-desktop)

## Starting an Assignment

1) The assignment in Canvas provides a link to GitHub classroom. Click on that link and accept the project. This will create a repository. For group projects, the first person accepts the project and the other group members join an existing project.
2) Clone the repository onto your machine. Example: `git clone https://github.com/cosc-404-2022/your-lab1-repo`
3) In a terminal window, start any Docker containers with the command: `docker-compose up -d`
4) Close containers using `docker-compose down` or using `Ctrl+C` in Docker container terminal window.

Alternative method is to Open the Command Palette (F1) to run the command
```Dev Containers: Reopen in container```. You can refer to this [step-by-step tutorial](https://code.visualstudio.com/docs/devcontainers/tutorial) if you need help.
