# Ex09 Event Registration Web Application
# Date:25-11-24
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
page 1:
html code:
<div class="i-phone-13-mini-1">
  <img class="background-figma-1" src="background-figma-10.png" />
  <img class="sec-logo-01-as-1" src="sec-logo-01-as-10.png" />
  <div class="sports-event-registrations">Sports Event Registrations</div>
  <img class="sec-logo-1" src="sec-logo-10.png" />
  <div class="register">register</div>
  <div class="rectangle-1"></div>
</div>

css:
.i-phone-13-mini-1,
.i-phone-13-mini-1 * {
  box-sizing: border-box;
}
.i-phone-13-mini-1 {
  background: #804d4d;
  height: 817px;
  position: relative;
  overflow: hidden;
}
.background-figma-1 {
  width: 615px;
  height: 817px;
  position: absolute;
  left: -235px;
  top: 0px;
  object-fit: cover;
}
.sec-logo-01-as-1 {
  width: 378px;
  height: 76px;
  position: absolute;
  left: 2px;
  top: 27px;
  object-fit: cover;
}
.sports-event-registrations {
  color: #1e1e4b;
  text-align: center;
  font-family: "ImFellEnglishSc-Regular", sans-serif;
  font-size: 40px;
  font-weight: 400;
  position: absolute;
  left: 43px;
  top: 116px;
  width: 292px;
  height: 181px;
}
.sec-logo-1 {
  border-radius: 119px;
  width: 192px;
  height: 177px;
  position: absolute;
  left: 93px;
  top: 231px;
  object-fit: cover;
}
.register {
  color: var(--miscellaneous-floating-tab-text-selected, #007aff);
  text-align: center;
  font-family: "ImFellEnglishSc-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
  position: absolute;
  left: 26px;
  top: 477px;
  width: 328px;
  height: 75px;
}
.rectangle-1 {
  background: rgba(23, 28, 60, 0.08);
  width: 220px;
  height: 79px;
  position: absolute;
  left: 80px;
  top: 473px;
}

page 2:
<div class="i-phone-13-mini-1">
  <img class="background-figma-1" src="background-figma-10.png" />
  <div class="sports-day-events">sports day events</div>
  <div
    class="foot-ball-cricket-kabadi-volley-ball-throw-ball-badminton-400-m-relay"
  >
    Foot ball
    <br />
    Cricket
    <br />
    Kabadi
    <br />
    Volley ball
    <br />
    Throw ball
    <br />
    Badminton
    <br />
    400m relay
    <br />
  </div>
  <img class="star-1" src="star-10.svg" />
  <img class="star-2" src="star-20.svg" />
  <img class="star-3" src="star-30.svg" />
  <img class="star-4" src="star-40.svg" />
  <img class="star-6" src="star-60.svg" />
  <img class="star-7" src="star-70.svg" />
  <img class="star-8" src="star-80.svg" />
</div>

css:
.i-phone-13-mini-1,
.i-phone-13-mini-1 * {
  box-sizing: border-box;
}
.i-phone-13-mini-1 {
  background: #ffffff;
  height: 817px;
  position: relative;
  overflow: hidden;
}
.background-figma-1 {
  width: 640px;
  height: 817px;
  position: absolute;
  left: -192px;
  top: 0px;
  object-fit: cover;
}
.sports-day-events {
  color: #080255;
  text-align: center;
  font-family: "ImFellEnglishSc-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
  position: absolute;
  left: 50px;
  top: 29px;
  width: 281px;
  height: 115px;
}
.foot-ball-cricket-kabadi-volley-ball-throw-ball-badminton-400-m-relay {
  color: #000000;
  text-align: left;
  font-family: "HindColombo-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 110px;
  top: 191px;
  width: 295px;
  height: 435px;
}
.star-1 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 191px;
  overflow: visible;
}
.star-2 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 240px;
  overflow: visible;
}
.star-3 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 289px;
  overflow: visible;
}
.star-4 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 387px;
  overflow: visible;
}
.star-6 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 485px;
  overflow: visible;
}
.star-7 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 436px;
  overflow: visible;
}
.star-8 {
  width: 28px;
  height: 33px;
  position: absolute;
  left: 68px;
  top: 338px;
  overflow: visible;
}

page 3:
htmlcode:
<div class="i-phone-13-mini-1">
  <img class="background-figma-1" src="background-figma-10.png" />
  <div class="event-registration-form">Event registration form</div>
  <div class="rectangle-1"></div>
  <div class="rectangle-2"></div>
  <div class="rectangle-3"></div>
  <div class="rectangle-4"></div>
  <div class="rectangle-5"></div>
  <div class="rectangle-6"></div>
  <div class="name">Name:</div>
  <div class="register-no">Register no:</div>
  <div class="department">Department:</div>
  <div class="year">
    Year:
    <br />
  </div>
  <div class="email">Email:</div>
  <div class="phone-no">Phone no:</div>
  <div class="rectangle-7"></div>
  <div class="submit">SUBMIT</div>
</div>

css code:
.i-phone-13-mini-1,
.i-phone-13-mini-1 * {
  box-sizing: border-box;
}
.i-phone-13-mini-1 {
  background: #ffffff;
  height: 817px;
  position: relative;
  overflow: hidden;
}
.background-figma-1 {
  width: 666px;
  height: 866px;
  position: absolute;
  left: -251px;
  top: -7px;
  object-fit: cover;
}
.event-registration-form {
  color: #1b1d53;
  text-align: center;
  font-family: "ImFellDoublePica-Regular", sans-serif;
  font-size: 40px;
  font-weight: 400;
  position: absolute;
  left: 28px;
  top: 34px;
  width: 323px;
  height: 102px;
}
.rectangle-1 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 170px;
}
.rectangle-2 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 309px;
}
.rectangle-3 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 233px;
}
.rectangle-4 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 459px;
}
.rectangle-5 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 522px;
}
.rectangle-6 {
  background: #fbfdff;
  width: 309px;
  height: 42px;
  position: absolute;
  left: 17px;
  top: 384px;
}
.name {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 170px;
  width: 238px;
  height: 51px;
}
.register-no {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 233px;
  width: 249px;
  height: 50px;
}
.department {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 309px;
  width: 273px;
  height: 58px;
}
.year {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 384px;
  width: 238px;
  height: 36px;
}
.email {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 459px;
  width: 243px;
  height: 64px;
}
.phone-no {
  color: #000000;
  text-align: left;
  font-family: "Hind-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 35px;
  top: 513px;
  width: 220px;
  height: 62px;
}
.rectangle-7 {
  background: rgba(66, 108, 154, 0.86);
  width: 164px;
  height: 55px;
  position: absolute;
  left: 189px;
  top: 609px;
}
.submit {
  color: #ffffff;
  text-align: center;
  font-family: "Iceberg-Regular", sans-serif;
  font-size: 38px;
  font-weight: 400;
  position: absolute;
  left: 190px;
  top: 614px;
  width: 149px;
  height: 69px;
  -webkit-text-stroke: 1px #fff4f4;
}

page 4:
html code:
<div class="i-phone-13-mini-1">
  <img class="background-figma-1" src="background-figma-10.png" />
  <div class="thank-you-for-registering">THANK YOU FOR REGISTERING!!</div>
  <div class="we-are-eagerly-waiting-for-you">
    we are eagerly waiting for you
  </div>
</div>
css code:
.i-phone-13-mini-1,
.i-phone-13-mini-1 * {
  box-sizing: border-box;
}
.i-phone-13-mini-1 {
  background: #ffffff;
  height: 817px;
  position: relative;
  overflow: hidden;
}
.background-figma-1 {
  width: 619px;
  height: 817px;
  position: absolute;
  left: -177px;
  top: 0px;
  object-fit: cover;
}
.thank-you-for-registering {
  color: #40466a;
  text-align: center;
  font-family: "IrishGrover-Regular", sans-serif;
  font-size: 48px;
  font-weight: 400;
  position: absolute;
  left: 12px;
  top: 174px;
  width: 355px;
  height: 179px;
}
.we-are-eagerly-waiting-for-you {
  color: #000000;
  text-align: center;
  font-family: "InriaSans-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 22px;
  top: 442px;
  width: 318px;
  height: 90px;
}





```
# OUTPUT:
![figma final](https://github.com/user-attachments/assets/8856f3a2-8c00-47fd-a0e6-bc9c73e2c1ef)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
