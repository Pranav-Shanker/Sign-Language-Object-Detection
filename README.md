# Tensorflow Object Detection

## Steps
<br />
<b>Step 1.</b> Clone this repository: https://github.com/Pranav-Shanker/Sign-Language-Object-Detection/
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 5.</b> Collect images using the Notebook <a href="https://github.com/nicknochnack/TFODCourse/blob/main/1.%20Image%20Collection.ipynb">1. Image Collection.ipynb</a> - change the kernel to the virtual environment as shown below
<img src="https://i.imgur.com/8yac6Xl.png"> 
<br/>
<b>Step 6.</b> Manually divide collected images into two folders train and test. <br/>
\TFODCourse\Tensorflow\workspace\images\train<br />
\TFODCourse\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 7.</b> Begin training process by opening <a href="https://github.com/nicknochnack/TFODCourse/blob/main/2.%20Training%20and%20Detection.ipynb">2. Training and Detection.ipynb</a>, this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model. 
<br /><br/>
<b>Step 8.</b> Install Tensorflow Object Detection.  at Step 8 with the last line stating OK.  
<img src="https://i.imgur.com/FSQFo16.png">
<br /> <br/>
<b>Step 9.</b> Train the model, inside of the notebook.
<img src="https://i.imgur.com/K0wLO57.png"> 
<br />
