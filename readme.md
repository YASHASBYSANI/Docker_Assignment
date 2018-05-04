# Docker-Project

Step 1: Download and Install Python from https://www.python.org/downloads/ <br>
Step 2: Install flask using command "pip install flask" <br>
Step 3: Install flaskRESTfull using command "pip install flask-RESTfull" <br>
Step 4: Download and install Docker Toolbox from https://docs.docker.com/toolbox/toolbox_install_windows/ <br>
Step 5: Open Docker Toolbox terminal and enter into your project directory <br>
Step 6: Type docker build -t flask-image:latest . to build image <br>
Step 7: Type docker run -t -p --name flask-container flask-image to run the image <br>
Step 8: Type "192.168.99.100:5000" to run your image on browser <br>
Step 9: Type "192.168.99.10:5000/foods" to see all records of foods <br>
Step 10: Type "192.168.99.10:5000/foods/1" to see records of foods based on ID <br>
Step 11: Type "192.168.99.10:5000/foods/veg" to see records of all vegeterian food <br>
Step 12: Type "192.168.99.10:5000/foods/non veg" to see records of all non vegeterian food
