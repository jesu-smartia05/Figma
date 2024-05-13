# Ex09 Event Registration Web Application
## Date:13.05.24

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
/* Home page */

box-sizing: border-box;
position: relative;
width: 360px;
height: 640px;
background: #F3A8D1;
border: 1px solid #000000;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);

/* Login page */

position: relative;
width: 367px;
height: 640px;
background: #F7D662;

/* SEC Page */

position: relative;
width: 360px;
height: 640px;
background: #8EE1D7;

/* LOGIN */

position: absolute;
width: 188px;
height: 29px;
left: 84px;
top: 449px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #FFFFFF;

/* Rectangle 1 */

position: absolute;
width: 271px;
height: 50px;
left: 43px;
top: 434px;
background: #86AD67;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);

/* logo 1 */

position: absolute;
width: 115px;
height: 116px;
left: 120px;
top: 100px;
background: url(rename.jpg);

/* Line 1 */

position: absolute;
width: 360px;
height: 0px;
left: 0px;
top: 89px;
border: 4px solid #FD0404;
transform: rotate(0.16deg);

/* NIRF Ranked Autonomous Institution */

position: absolute;
width: 324px;
height: 38px;
left: 16px;
top: 310px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Affiliated to Anna University */

position: absolute;
width: 345px;
height: 56px;
left: 1px;
top: 241px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Saveetha Engineering College */

position: absolute;
width: 324px;
height: 38px;
left: 9px;
top: 31px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Submit */

position: absolute;
width: 145px;
height: 22px;
left: 58px;
top: 516px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: right;
color: #FFFFFF;

/* Line 2 */

position: absolute;
width: 360px;
height: 0px;
left: 0px;
top: 89px;
border: 4px solid #FD0404;
transform: rotate(0.16deg);

/* Frame 1 */

position: absolute;
width: 271px;
height: 50px;
left: 44px;
top: 502px;

/* password */

position: absolute;
width: 96px;
height: 17px;
left: 47px;
top: 387px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: right;
color: #000000;

/* username */

position: absolute;
width: 96px;
height: 17px;
left: 50px;
top: 272px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: right;
color: #000000;

/* Rectangle 4 */

position: absolute;
width: 259px;
height: 38px;
left: 50px;
top: 424px;
background: #D9D9D9;

/* Rectangle 2 */

position: absolute;
width: 259px;
height: 38px;
left: 50px;
top: 305px;
background: #D9D9D9;

/* logo 2 */

position: absolute;
width: 115px;
height: 116px;
left: 115px;
top: 133px;
background: url(rename.jpg);

/* Saveetha Engineering College */

position: absolute;
width: 324px;
height: 38px;
left: 11px;
top: 39px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* logo 3 */


position: absolute;
width: 115px;
height: 116px;
left: 112px;
top: 131px;
background: url(rename.jpg);

/* Line 2 */

position: absolute;
width: 360px;
height: 0px;
left: 0px;
top: 90px;
border: 4px solid #FD0404;
transform: rotate(0.16deg);

/* AI-DS */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 479px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* AI-ML */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 543px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* IOT */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 415px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Cyber Security */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 351px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Departments */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 287px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;

/* Saveetha Engineering College */

position: absolute;
width: 324px;
height: 24px;
left: 18px;
top: 36px;
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;
color: #000000;
```

## OUTPUT:

![img1](https://github.com/jesu-smartia05/Figma/assets/148514819/da2153e1-6473-4224-885c-29668a1ffd8e)

![img2](https://github.com/jesu-smartia05/Figma/assets/148514819/b077f1e8-56ff-4681-8f81-be037bdc8440)

![img3](https://github.com/jesu-smartia05/Figma/assets/148514819/96740580-23bf-433c-9b0c-39c395a30d27)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
