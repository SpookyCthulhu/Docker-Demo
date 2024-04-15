# Docker-Demo

The following application consists of many divs that alternate between the colors of the rainbow

and fill the screen (semi) dynamically. If a div is clicked it will flip colors, allowing you to

create designs in the page.

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

![rainbow](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGdjY2FwanIwMnh1NXdjZDR0bWx6N2o3bzhiNW1kbGtnd2htczlqaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZYQ4Bc9gdQv70tBJFP/giphy.gif)
