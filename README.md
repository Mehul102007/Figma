# Ex09 Event Registration Web Application
## Date:23.12.2025
## Reference number: 25018961

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
### FIRST PAGE:
#### INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="sec-logo" src="img/sec-logo-01as-2048x412-1.png" />
      <img class="download" src="img/download-1.png" />
      <img class="rectangle" src="img/rectangle-3.svg" />
      <div class="text-wrapper">MUSIC EVENTS</div>
      <div class="div"></div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">REGISTER</div>
    </div>
  </body>
</html>
~~~
#### globals.css:
~~~
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

~~~

#### style.css
~~~
.iphone {
  width: 100%;
  min-width: 446px;
  min-height: 841px;
  position: relative;
}

.iphone .sec-logo {
  position: absolute;
  top: 2px;
  left: 10px;
  width: 436px;
  height: 88px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone .download {
  position: absolute;
  top: 118px;
  left: 106px;
  width: 229px;
  height: 220px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .rectangle {
  top: 387px;
  left: 52px;
  width: 347px;
  height: 74px;
  position: absolute;
}

.iphone .text-wrapper {
  position: absolute;
  top: 397px;
  left: 96px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  top: 525px;
  left: 144px;
  width: 162px;
  height: 56px;
  background-color: #22e3df;
  border-radius: var(--shape-corner-large);
  position: absolute;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 527px;
  left: 169px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  top: 644px;
  left: 136px;
  width: 189px;
  height: 68px;
  background-color: #21e2df;
  border-radius: var(--shape-corner-large);
  position: absolute;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 650px;
  left: 143px;
  width: 170px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

~~~


#### styleguide.css
~~~
:root {
  --shape-corner-large: 16px;
}
~~~
### SECOND PAGE:
#### INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="rectangle"></div>
      <div class="text-wrapper">MUSIC EVENTS</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <div class="div">Festivals</div>
      <div class="text-wrapper-2">concerts</div>
      <div class="text-wrapper-3">concerences</div>
      <div class="text-wrapper-4">DJ</div>
    </div>
  </body>
</html>

~~~
#### GLOBAL.CSS:
~~~
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

~~~
#### STYLE.CSS:
~~~
.iphone {
  background-image: url(./img/iphone-13-14-2.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 62px;
  left: 72px;
  width: 265px;
  height: 60px;
  background-color: #fa0d0d;
  border-radius: 18px;
  box-shadow: 0px 18px 18px 4px #00000040;
}

.iphone .text-wrapper {
  position: absolute;
  top: 68px;
  left: 87px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .star {
  position: absolute;
  top: 274px;
  left: 38px;
  width: 33px;
  height: 31px;
}

.iphone .img {
  position: absolute;
  top: 368px;
  left: 38px;
  width: 33px;
  height: 32px;
}

.iphone .star-2 {
  position: absolute;
  top: 463px;
  left: 41px;
  width: 30px;
  height: 29px;
}

.iphone .star-3 {
  position: absolute;
  top: 537px;
  left: 41px;
  width: 30px;
  height: 27px;
}

.iphone .div {
  position: absolute;
  top: 264px;
  left: 87px;
  width: 142px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 359px;
  left: 87px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 441px;
  left: 72px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 523px;
  left: 72px;
  font-family: "IBM Plex Sans KR-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

~~~
### THIRD PAGE:
#### INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">FULL NAME</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">GENDER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">AGE</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">REGISTER N0</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-5">DEPARTMENT</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">MOBILE NO</div>
      <img class="img" src="img/rectangle-14.svg" />
      <div class="text-wrapper-7">EMAIL ID</div>
      <img class="rectangle-7" src="img/rectangle-15.svg" />
      <div class="text-wrapper-8">EVENTS REGISTER</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-9">SUBMIT</div>
      <div class="EVENT-REGISTRATION">EVENT&nbsp;&nbsp;REGISTRATION FORM</div>
    </div>
  </body>
</html>

~~~
#### GLOBAL.CSS:
~~~
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

~~~
#### STYLE.CSS:
~~~
.iphone {
  overflow: hidden;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 29px;
  left: calc(50.00% - 151px);
  width: 306px;
  height: 70px;
  background-color: #f21515;
}

.iphone .div {
  position: absolute;
  top: 149px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper {
  position: absolute;
  top: 152px;
  left: calc(50.00% - 54px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 214px;
  left: calc(50.00% - 99px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 217px;
  left: calc(50.00% - 40px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 285px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 289px;
  left: calc(50.00% - 22px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 379px;
  left: -894px;
  width: 160px;
  height: 37px;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 356px;
  left: calc(50.00% - 99px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 360px;
  left: calc(50.00% - 67px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 422px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 425px;
  left: calc(50.00% - 65px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-6 {
  position: absolute;
  top: 495px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 499px;
  left: calc(50.00% - 54px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .img {
  position: absolute;
  top: 546px;
  left: calc(50.00% - 143px);
  width: 288px;
  height: 138px;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 577px;
  left: calc(50.00% - 45px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-7 {
  position: absolute;
  top: 616px;
  left: calc(50.00% - 144px);
  width: 288px;
  height: 139px;
}

.iphone .text-wrapper-8 {
  position: absolute;
  top: 648px;
  left: calc(50.00% - 89px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-8 {
  position: absolute;
  top: 769px;
  left: calc(50.00% - 90px);
  width: 181px;
  height: 33px;
  background-color: #f41919;
}

.iphone .text-wrapper-9 {
  position: absolute;
  top: 764px;
  left: calc(50.00% - 38px);
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .EVENT-REGISTRATION {
  position: absolute;
  top: 45px;
  left: calc(50.00% - 141px);
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

~~~
#### STYLEGUIDE.CSS:
~~~
:root {
  --shape-corner-large: 16px;
}

~~~
### FOURTH PAGE:
#### INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone"><div class="text-wrapper">thank you for register</div></div>
  </body>
</html>

~~~
#### GLOBAL.CSS:
~~~
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
~~~
#### STYLE.CSS:
~~~
.iphone {
  overflow: hidden;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 29px;
  left: calc(50.00% - 151px);
  width: 306px;
  height: 70px;
  background-color: #f21515;
}

.iphone .div {
  position: absolute;
  top: 149px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper {
  position: absolute;
  top: 152px;
  left: calc(50.00% - 54px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 214px;
  left: calc(50.00% - 99px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 217px;
  left: calc(50.00% - 40px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 285px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 289px;
  left: calc(50.00% - 22px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 379px;
  left: -894px;
  width: 160px;
  height: 37px;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 356px;
  left: calc(50.00% - 99px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 360px;
  left: calc(50.00% - 67px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 422px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 425px;
  left: calc(50.00% - 65px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-6 {
  position: absolute;
  top: 495px;
  left: calc(50.00% - 100px);
  width: 200px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 40px 4px #00000040;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 499px;
  left: calc(50.00% - 54px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .img {
  position: absolute;
  top: 546px;
  left: calc(50.00% - 143px);
  width: 288px;
  height: 138px;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 577px;
  left: calc(50.00% - 45px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-7 {
  position: absolute;
  top: 616px;
  left: calc(50.00% - 144px);
  width: 288px;
  height: 139px;
}

.iphone .text-wrapper-8 {
  position: absolute;
  top: 648px;
  left: calc(50.00% - 89px);
  opacity: 0.5;
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-8 {
  position: absolute;
  top: 769px;
  left: calc(50.00% - 90px);
  width: 181px;
  height: 33px;
  background-color: #f41919;
}

.iphone .text-wrapper-9 {
  position: absolute;
  top: 764px;
  left: calc(50.00% - 38px);
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .EVENT-REGISTRATION {
  position: absolute;
  top: 45px;
  left: calc(50.00% - 141px);
  font-family: "Imbue-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
~~~

## OUTPUT:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9bf1e68f-6702-4b17-80e3-71a28abd6735" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
