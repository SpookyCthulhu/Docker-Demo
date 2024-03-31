# Docker-Demo

The following application consists of many divs that alternate between the colors of the rainbow

and fill the screen (semi) dynamically. If a div is clicked it will flip colors, allowing you to alter the

flow of the pattern.

To run the code for this application in your browser you first need to login to docker using:

docker login

Then enter your login credentials as prompted.

Once logged in pull the image in my repository like so:

docker pull eldritchautomata/rainbow

This should give you the image for the web server.

Finally run the image:

docker run -p 8080:80 eldritchautomata/rainbow

You should now be running the container.

Visit http://{your_IP}:8080 to view it in action.
