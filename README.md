# Color-Detection
Colour detection is the process of detecting the name of any color. Simple isn’t it? Well, for humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. 

<h3>About the Project</h3><hr>

In this color detection Python project, we are going to build an application through which you can automatically get the name of the color by clicking on them. So for this, we will have a data file that contains the color name and its values. Then we will calculate the distance from each color and find the shortest one


<h3>Dataset:</h3><hr>

Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color ? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. 

<b>Color Dataset:</b>

The colors.csv file includes 865 color names along with their RGB and hex values <a href="https://www.kaggle.com/datasets/adityabhndari/color-detection-data-set">visit here</a>

<h3>Install Required Modules:</h3><hr>
OpenCV, Pandas, argparse and numpy are the Python packages that are necessary for this project in Python. 

To install them, simply run this pip command in your terminal:

<b>pip install opencv-python numpy pandas</b>


<h3>Use Case Diagram:</h3><hr>

![Screenshot_2024_0426_145624](https://github.com/Praveen-ASE/Color-Detection/assets/148997369/44dadec4-e3d7-4ee7-9e7e-54ad679be01b)

<h3>Project Execution</h3><hr>
You can run the Python file from the command prompt. Make sure to give an image path using ‘-i’ argument. If the image is in another directory, then you need to give full path of the image:
<b>python color_detection.py -i <add your image path here></b>


