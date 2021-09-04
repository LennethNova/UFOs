# UFOs

# UFO Finder

## Overview of Project
Using the data about ***"UFO sightings"*** provided by the client, there is a need to visualize and filter data in order to show the information that the user is looking for, that way the final user won't have to scroll down the whole page and will only get the results that were requested.

### This project includes:
- Filter UFO sightings on multiple criteria using Javascript
- A webpage to visualize the information.

### Purpose
The main purpose of this challenge is to filter the information accordingly in order to show what the user is expecting and at the same time, deliver an easy to read format. The display must be simple, in order to be user friendly and easy to navigate. 

## Analysis and Challenges
There is a lot of information regarding UFO sightings but there was not a way to display it. In order to make it work and filter the information based on selected dates, city, state, country and shapes, a way to display it using html and javascript was implemented.

![01](https://github.com/LennethNova/UFOs/blob/main/images/01.PNG)

Once the page is partly made with html, there a functions in javascript that need to be created in order to make the filters work and link them to the html. 

### Challenges and Difficulties Encountered
During this challenge the difficult part was making sure that the filters work based on user selection. Understanding the **d3.select(this)** and **Object.entries** was a big part in this project to complete it.

![02](https://github.com/LennethNova/UFOs/blob/main/images/02.PNG)

## Results

- How someone might use the new webpage by walking through the process of using the search criteria: 

Once the user enters the webpage, the options to write appear, and those have a placeholder text in order to set an example of the input the user should use. Once the desired data is selected, and followed by an enter command or a click to another option, the user will filter the information that is desired. Using this information and sharing it with the user (it can be placed also as instructions), the search criteria based on the user choice would be displayed. This way, if the user only desires for an specific date, country, state, city or a particular shape, the data selected will appear and the change would be faster.

![03](https://github.com/LennethNova/UFOs/blob/main/images/03.PNG)

![04](https://github.com/LennethNova/UFOs/blob/main/images/04.PNG)

- Describe one drawback of this new design and two recommendations for further development: 

One of the drawbacks is that since there is not a button, the user might feel that the information is not changing. Also, it would be better to have a scroll down menu in order to show the information available because the data is specific, for instance there could be various contries inside the data, but the user might think that the information is only from sightings in the US. It would be the same with the other options, so a scroll down with the data would really help the user to know the available information about the UFO sightings. A button should also be considered in order to give the user more control, it could also work for those who are used to click on something instead of just hitting enter or tab.

![05](https://github.com/LennethNova/UFOs/blob/main/images/05.PNG)
