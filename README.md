# MyDockerRepo
PreSession and Homework assignments
We continue our journey in the wonderful world of docker.

Before our next session, please make sure you complete the following:

1.     Watch the following chapters on the "Docker deep Dive" course at pluralsight:

·       Working with Images. Only submodules: “Registries”.

·       Containerizing an App. Only submodules: "Digging Deeper".

·       Working with Containers. Only submodules: “Containers: The Big Picture” and “Diving Deeper”

·       If you don’t remember everything from last week, please review the previous sub-modules in these chapters.

2.     Create a Dockerfile and dockerize the attached python web application (app.py):

·       The image will be based on the alpine:3.9

·       Make sure you mark yourself as the maintainer

·       The image should update package repository and install python3

·       The image should have the following python packages installed:

o   Click==7.0

o   Flask==1.0.2

o   itsdangerous==1.1.0

o   Jinja2==2.10

o   MarkupSafe==1.1.1

o   Werkzeug==0.14.1

·       The image should contain our app J

3.     Push your newly created image to your dockerhub account

4.     Run a container deamon from your newly created image and map it to a port on your host (**Tip: the webserver is using port 5000)

5.     From your browser access the dockerized web application:

·       Print the browser screen with the webpage you got on the default server path (/)

·       Print the browser screen with the webpage you got on the goaway server path (/goaway)

6.      Please save the following files in your personal git repo and paste the link as text:

·       Dockerfile

·       Application file (app.py)

·       Any other file you think are required for the docker build to succeed

·       2 screen capture files (from step 7)

·       A text file with a link to your docker hub repo and image

