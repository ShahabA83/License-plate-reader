# This project is about detecting license plates and then reading the license plate number.
----
### Description
In this project, with the help of the `YOLOv7` model and fine-tuning our data, we were able to recognize the license plate in the image and frame.<br>
In the next step, we divide the recognized license plate into eight parts, each part containing a number or a letter from the license plate.<br>
These eight images must be examined to see what number or letter is inside them. Using the data we have prepared, we created a model for recognizing numbers and a model for recognizing letters.<br>
The two models created are a combination of CNN and dense layers.<br>
The accuracy of the number recognition model is `95` percent and the accuracy of the letter model is `80` percent.<br>
Of course, we are still improving the quality of these two models.<br>
In this project, some processing has been done on the images to improve performance. For example, if the license plate in the photo has an angle, we can correct this angle with the help of written commands (of course, if the depth angle is too large, good performance will not be achieved)<br>
#### Final program:<br>
The final program is located in a Python file called `Final Code`<br>

----

## Examples of project outputs:
<p align="center">
  <img src="https://github.com/ShahabA83/License-plate-reader/blob/main/Dataset/Output%20samples%20taken/detected_plate1.png?raw=true" width="400" height="300"/>
  <img src="https://github.com/ShahabA83/License-plate-reader/blob/main/Dataset/Output%20samples%20taken/detected_plate4.png?raw=true" width="400" height="300"/>
</p>


<p align="center">
  <img src="https://github.com/ShahabA83/License-plate-reader/blob/main/Dataset/Output%20samples%20taken/detected_plate5.png?raw=true" width="400" height="300"/>
  <img src="https://github.com/ShahabA83/License-plate-reader/blob/main/Dataset/Output%20samples%20taken/detected_plate10.png?raw=true" width="400" height="300"/>
</p>