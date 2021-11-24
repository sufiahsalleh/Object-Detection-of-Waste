# Object-Detection-of-Waste

This is an object detection project. It is used to detect 3 type of waste which are glass, metal and plastic.

<h1>Description</h1>
<b>Aim</b><br>
1. It is used to detect 3 types of waste which are glass, metal and plastic.<br>
2. By displaying waste to a webcam, the project hopes to detect metal, glass, and plastic waste.
<br><br>
<b>Tools:</b><br>
	1. IntelliJ to write java code and execute them.<br>
	2. LabelImg to create datasets annotations.<br><br>
 
<b>Library:</b><br>
	1. The Deeplearning4j library were used to create this object detection project. 

<h1>Motivation of the idea</h1>

- We also inspired to do this object detection waste for education purpose which to help kids in learning that there is many type of waste that can be recycled.
- This project also our CDLE capstone project.

<h1>Data Set Sources</h1>

- The data was custom made from google image. 
- Image data are in .jpg
- 80% of the data was utilized for training, while 20% was used for testing.

<h1>Network Description</h1>
The Pre-trained Tiny Yolo comprised 9 convolutions layer with 6 max pooling. We fine-tuning the output layer for classification.

<h1>Model Training</h1>
We used <b>tiny YOLO</b> model.

<h1>Testing</h1>
<table>
    <tr>
    <td align="center">Testing with Test Dataset</td>
    <td align="center">Testing with Webcam</td></td>
    </tr>
    <tr>
    <td align="center"><img src="https://github.com/sufiahsalleh/sufiahsalleh.github.io/blob/main/assets/img/5vdatj.gif" alt="Test with Testing Dataset" width="80%" height="20%"</td>
    <td align="center"><img src="https://github.com/sufiahsalleh/sufiahsalleh.github.io/blob/main/assets/img/5vdewu.gif" alt="Test with Webcam" width="80%" height="80%"></td>
    </tr>
</table>

<h1>Future Development</h1>

- Create more accurate model by using more dataset.
- Add features that will predict the recycle bin the waste should go into after classify the object.
- Develop mobile application to detect waste using this model.

<h1>List of Group members</h1>

- Norruljannah binti Hashim, njannah.hashim@gmail.com
- Sufiah Afira binti Salleh, sufiah.afira01@gmail.com
