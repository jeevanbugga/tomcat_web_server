This image is a basic Tomcat image that will display a custom message when you run it as a Docker container.

**Usage:**
1. Clone the repository to your local machine and build the Docker image using the following command. Make sure you are in the repository directory when running the 'docker build' command.
   ```
   docker build . -t <tomcatweb_server>
   ```

2. Run the container:
   ```
   docker container run -p <YourFreeHostPort>:8080 tomcatweb_server
   ```

3. Now you can access the web server using:
   ```
   https://yourpublicip:<hostport you configured>
   ```

**Output:**
- Displays a custom message indicating that Tomcat has been successfully installed.
