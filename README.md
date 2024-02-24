# Dockerfile for Installing Apache Server

This Dockerfile provides instructions for building a Docker image that installs Apache server. Apache server is a popular web server software that allows you to serve web content on the internet.

## Usage

1. **Clone Repository**:
   Clone this repository to your local machine using the following command:

2. **Navigate to Directory**:
Navigate to the directory containing the Dockerfile:

3. **Build Docker Image**:
Build the Docker image using the following command:

4. **Run Docker Container**:
Run a Docker container using the newly built image:

5. **Access Apache Server**:
Access the Apache server by visiting `http://localhost:8080` in your web browser.

## Dockerfile Details

- The Dockerfile starts with the official Ubuntu 20.04 base image.
- It updates the package lists and installs Apache server (`apache2` package).
- Port 80, the default port used by Apache, is exposed to the outside world.
- Apache server is started in the foreground when the container starts.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Apache HTTP Server](https://httpd.apache.org/): Official website for Apache HTTP Server.
- [Docker](https://www.docker.com/): Official website for Docker.
