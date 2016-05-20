ESS_WEB_PROJECT is node.js web project, integrated with official docker "node" image from Docker Hub. Dockerfile will create customized node image, integrated with EXPRESS_WEB_PROJECT source code.

Example:
 docker run -p 80:3000 neoxsys/express_web_project

Now redirect you local browser to localhost, since we map container port 3000 to local port 80.

