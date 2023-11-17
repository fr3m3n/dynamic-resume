# Dynamic Resume

## Overview
Dynamic Resume is a web-based application that transcends the limitations of a traditional, static document. Built with Vanilla JavaScript, this project showcases a modern approach to resume presentation on the web.

## Features

### Asynchronous Data Loading
- Utilizes the Fetch API interface.
- Executes get() requests to retrieve data items asynchronously from the server.
- Dynamically updates various sections of the webpage with fetched data.

### Frontend Design
- Aesthetically pleasing and responsive layout.
- Developed using HTML and CSS.
- Optimized for both desktop and mobile viewing experiences.

### Deployment
- Thoroughly tested to ensure reliability and performance.
- Hosted on a leading web hosting platform, ensuring high availability and fast access.

## Technologies Used
- **JavaScript (Vanilla JS):** For dynamic interactions and data handling.
- **HTML & CSS:** For structuring and styling the web page.
- **Fetch API:** For asynchronous data retrieval and web page updates.

## Usage
To experience the Dynamic Resume, visit [Stelline Lab](https://stellinelab.io/).

## Docker Container

The project includes a Dockerfile for easy deployment using Docker and Nginx. Follow these steps to build and run the Docker container:

1. **Build the Docker image**:
   ```
   docker build -t dynamic-resume .
   ```
   This command will use the `Dockerfile` in the project directory to build the Docker image, tagging it as `dynamic-resume`.

2. **Run the Docker container**:
   ```
   docker run -d -p 80:80 dynamic-resume
   ```
   This will start a container based on the `dynamic-resume` image. The `-d` flag runs the container in detached mode, leaving the container running in the background. The `-p` flag publishes the container's port 80 to the external port 80 on the host.

Visit `http://localhost` in your web browser to view the Dynamic Resume web application.

## Contributing
Contributions to enhance the Dynamic Resume are welcome. Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
A special thanks to everyone who contributed to the development and deployment of this project.

## Contact
For more information, please contact [Email](mailto:mtimochenko@tutanota.com).

---

# Tags
- #VanillaJS
- #AsyncWebApp
- #WebDeployment