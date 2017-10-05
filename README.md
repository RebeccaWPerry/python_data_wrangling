# Data Wrangling with Python

## Workshop Links
[Software Carpentry Lesson](http://swcarpentry.github.io/python-novice-inflammation/){:target="_blank"}

<a href="http://swcarpentry.github.io/python-novice-inflammation/data/python-novice-inflammation-data.zip" download="Download">Download Weather Radar Station Data</a> 
<a href="Weather_Radar.csv" download="Download">Download Mock Patient Data</a>

## Required Prework
During this workshop, you will be writing Python code on your own laptop to analyze a provided sample data set. Working on your own laptop means you will walk away from the workshop ready to continue learning Python and using it with your own data! To make this possible, I ask that you do some setup on your laptop before arriving. If you run into trouble installing the necessities, please come to the class anyways. There will be people to help you.

The workshop will make heavy use of [Software Carpentry's](https://software-carpentry.org/lessons/){:target="_blank"} lesson on scientific Python programming. Please download the sample data set python-novice-inflammation-data.zip from [here](http://swcarpentry.github.io/python-novice-inflammation/setup/){:target="_blank"}: http://swcarpentry.github.io/python-novice-inflammation/setup/.

Great. Now that you have the data, you need a programming language! Here are separate instructions for those who have used Python before and for newbies: 

### This is all new to me
My recommendation for scientific Python is to install the Anaconda Python distribution. This is an easy way to install Python bundled up with a lot of really helpful libraries.

You can choose between 3.6 and 2.7. If you are just starting out and aren't tied to any legacy code, I recommend going for 3.6. You can download either version [here](https://www.anaconda.com/download/){:target="_blank"} (https://www.anaconda.com/download/).

After completing the installation (could take up to 30 minutes), you will need to verify that it installed correctly following the steps below. To follow these steps you need to find the Terminal or Command Prompt on your computer. You will be able to find Terminal on a Mac or Linux laptop and a Command Prompt on a Windows laptop. If there is somewhere you are used to clicking and then typing the name of a program to search for it (e.g the start or Windows menu), that's where you would be typing Terminal or Command to pull up either of those programs.


### I already have Python on my computer
Great -- let's check that you have interactive Python and a few really helpful libraries. For this workshop, we will be using an interactive python console. If you are a big fan of iPython notebooks, you may use those instead of the console but there will not be support to troubleshoot the notebooks.

1. Open a terminal (linux/apple) or command prompt (windows) and type ipython followed by enter.
```markdown
ipython
```
If you see a Python version number, an iPython version number, and get a new prompt strting with "In [1]:", then you have interactive Python! If you see an error instead of these things, then you will need to install interactive python. I recommend going back to "This is all new to me," but you can also forge ahead by [installing iPython on its own](https://ipython.org/install.html){:target="_blank"}.

2. Now check for packages that we will use in class by typing these lines followed by enter after each line.
```markdown
import time
import glob
import numpy as np
import matplotlib.pyplot as plt
```
If these packages are already installed, then the ipython console will simply return new input lines. If you are missing any of these libraries, you will see a message like "ImportError: No module named matplotlib." If that is the case, you can try installing the missing packages individually ([https://matplotlib.org/users/installing.html](https://matplotlib.org/users/installing.html){:target="_blank"}) or go back to This is all new to me.

3. Now let's try to generate a figure window (where you would display a graph). In the iPython console where you have already imported matplotlib.pyplot as plt, type this on two new lines:
```
plt.figure()
plt.show()
```
The intended output is a new window that says Figure 1 at the top, has some icons, and is mostly gray. If you got an error instead, Google will be the best avenue to troubleshoot the error. Closing the figure window will bring you back to a fresh command prompt.

4. Great! You know how to start up an interactive python console and can import the necessary libraries. Please bring this laptop to the workshop. See you there!

### Resources
[Google](https://www.google.com/){:target="_blank"} How did people learn how to code before there was Google?

[Stack Overflow](https://stackoverflow.com/){:target="_blank"} Many of your Google searches may land you here

[Software Carpentry](https://software-carpentry.org/){:target="_blank"}

[Scipy Lecture Notes](http://www.scipy-lectures.org/){:target="_blank"}

Please feel free to reach out to me at perry.becca@gmail.com
