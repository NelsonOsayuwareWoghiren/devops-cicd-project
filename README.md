# devops-cicd-project
This is a simple web applications that showcases a complete DevOps workflow using Docker, Github Actions, and cloud deployment.

----

This project includes: A static HTML website , Containerization using Docker and Nginx, Automated CI/CD pipeline with Github Actions, Deployment to a live cloud service (Render)


----


Tech Used?
HTML, Docker, Nginx, Github Actions, Render


----

How does it work?

The website is written in 'index.html'
Docker packages the site using Nginx
Github Actions automatically builds the Docker image on every push
Render deploys the updated container to a live running URL

To run locally:

```bash
docker build -t devops-project  .
docker run -p 8080:80 devops-project
