# Ex09 Event Registration Web Application
## Date:

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
## HOMEPAGE (FRAME 1):
## CSS:
```
    .homepage,
    .homepage * {
      box-sizing: border-box;
    }
    .homepage {
      background: #ffffff;
      height: 956px;
      position: relative;
      overflow: hidden;
    }
    .homepage___2-2 {
      background: var(--accents-mint, #00c8b3);
      width: 4096px;
      height: 4096px;
      position: absolute;
      left: -1847px;
      top: -1662px;
      aspect-ratio: 1;
    }
    .homepage__saveetha-engineering-college-presents-sportsthon-2025 {
      color: #7e1111;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 29px;
      top: 36px;
      width: 411px;
      height: 180px;
      -webkit-text-stroke: 1px #6a1919;
    }
    .homepage__rectangle-16 {
      background: #d9d9d9;
      width: 192px;
      height: 49px;
      position: absolute;
      left: 220px;
      top: 322px;
    }
    .homepage__rectangle-17 {
      background: #d9d9d9;
      width: 192px;
      height: 53px;
      position: absolute;
      left: 220px;
      top: 522px;
    }
    .homepage__rectangle-18 {
      background: #ef1111;
      width: 166px;
      height: 58px;
      position: absolute;
      left: 35px;
      top: 675px;
    }
    .homepage__log-in {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 78px;
      top: 689px;
    }
    .homepage__text-on-a-path {
      background: #000000;
      border-radius: 0px;
      width: 158px;
      height: 58px;
      position: absolute;
      left: 259px;
      top: 675px;
    }
    .homepage__rectangle-20 {
      background: #dd1313;
      width: 255px;
      height: 65px;
      position: absolute;
      left: 105px;
      top: 758px;
    }
    .homepage__forgot-password {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 115px;
      top: 765px;
    }
    .homepage__username {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 13px;
      top: 322px;
      width: 145px;
      height: 49px;
    }
    .homepage__password {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 13px;
      top: 510px;
      width: 145px;
      height: 51px;
    }
    .homepage__rectangle-21 {
      background: #dd1313;
      width: 166px;
      height: 58px;
      position: absolute;
      left: 259px;
      top: 675px;
    }
    .homepage__register {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 297px;
      top: 689px;
    }
    .homepage__sec-represents-the-sporsthon-event-we-re-looking-everyone-to-join-to-supports-us {
      color: #df2222;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 0px;
      top: 861px;
      width: 440px;
      height: 89px;
      -webkit-text-stroke: 1px #e94545;
    }
```
## HTML:
```
    <div class="homepage">
      <div class="homepage___2-2"></div>
      <div class="homepage__saveetha-engineering-college-presents-sportsthon-2025">
        SAVEETHA ENGINEERING COLLEGE
        <br />
        <br />
        PRESENTS
        <br />
        <br />
        SPORTSTHON 2025
        <br />
        <br />
      </div>
      <div class="homepage__rectangle-16"></div>
      <div class="homepage__rectangle-17"></div>
      <div class="homepage__rectangle-18"></div>
      <div class="homepage__log-in">LOG IN</div>
      <div class="homepage__text-on-a-path"></div>
      <div class="homepage__rectangle-20"></div>
      <div class="homepage__forgot-password">
        FORGOT PASSWORD
        <br />
      </div>
      <div class="homepage__username">USERNAME</div>
      <div class="homepage__password">PASSWORD</div>
      <div class="homepage__rectangle-21"></div>
      <div class="homepage__register">REGISTER</div>
      <div
        class="homepage__sec-represents-the-sporsthon-event-we-re-looking-everyone-to-join-to-supports-us"
      >
        SEC REPRESENTS THE SPORSTHON EVENT WE’RE LOOKING EVERYONE TO JOIN TO
        SUPPORTS US!
      </div>
    </div>

## LIST OF SPORTS PAGE (FRAME 2):
## CSS:
    .sports-list,
    .sports-list * {
      box-sizing: border-box;
    }
    .sports-list {
      background: #ffffff;
      height: 956px;
      position: relative;
      overflow: hidden;
    }
    .sports-list___2-1 {
      background: var(--accents-red, #ff383c);
      width: 4096px;
      height: 4096px;
      position: absolute;
      left: -1828px;
      top: -1552px;
      aspect-ratio: 1;
    }
    .sports-list__cricket {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 247px;
    }
    .sports-list__sports-events-details-given-below {
      color: #ee8f3c;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 26px;
      top: 12px;
      width: 475px;
      height: 292px;
      -webkit-text-stroke: 1px #b8c414;
    }
    .sports-list__sports-available-to-register {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 8px;
      top: 191px;
    }
    .sports-list__football {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 323px;
    }
    .sports-list__basketball {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 407px;
    }
    .sports-list__volleyball {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 515px;
    }
    .sports-list__kho-kho {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 614px;
    }
    .sports-list___200-mts {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 698px;
    }
    .sports-list___400-mts {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 797px;
    }
    .sports-list__tennis {
      color: #ffffff;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 86px;
      top: 873px;
    }
```
## HTML:
```
    <div class="sports-list">
      <div class="sports-list___2-1"></div>
      <div class="sports-list__cricket">CRICKET</div>
      <div class="sports-list__sports-events-details-given-below">
        SPORTS EVENTS DETAILS
        <br />
        <br />
        <br />
        GIVEN BELOW
      </div>
      <div class="sports-list__sports-available-to-register">
        SPORTS AVAILABLE TO REGISTER:
      </div>
      <div class="sports-list__football">FOOTBALL</div>
      <div class="sports-list__basketball">BASKETBALL</div>
      <div class="sports-list__volleyball">VOLLEYBALL</div>
      <div class="sports-list__kho-kho">KHO-KHO</div>
      <div class="sports-list___200-mts">200 MTS</div>
      <div class="sports-list___400-mts">400 MTS</div>
      <div class="sports-list__tennis">TENNIS</div>
    </div>
```
## EVENTS REGISTRATION PAGE (FRAME 3):
## CSS:
```
    .event-registration-form,
    .event-registration-form * {
      box-sizing: border-box;
    }
    .event-registration-form {
      background: #d98686;
      height: 956px;
      position: relative;
      overflow: hidden;
    }
    .event-registration-form__sports-registration-form-applicable-for-all-years-2025 {
      color: #68369e;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 35px;
      top: 43px;
      width: 372px;
      height: 154px;
      -webkit-text-stroke: 1px #c82121;
    }
    .event-registration-form__star-1 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 14px;
      top: 242px;
      overflow: visible;
    }
    .event-registration-form__star-2 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 343px;
      overflow: visible;
    }
    .event-registration-form__star-3 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 425px;
      overflow: visible;
    }
    .event-registration-form__text-on-a-path {
      background: #000000;
      border-radius: 0px;
      width: 226px;
      height: 34px;
      position: absolute;
      left: 82px;
      top: 420px;
    }
    .event-registration-form__star-4 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 507px;
      overflow: visible;
    }
    .event-registration-form__star-5 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 600px;
      overflow: visible;
    }
    .event-registration-form__star-6 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 692px;
      overflow: visible;
    }
    .event-registration-form__star-7 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 780px;
      overflow: visible;
    }
    .event-registration-form__star-8 {
      width: 40px;
      height: 40px;
      position: absolute;
      left: 10px;
      top: 867px;
      overflow: visible;
    }
    .event-registration-form__text-on-a-path2 {
      background: #000000;
      border-radius: 0px;
      width: 182px;
      height: 30px;
      position: absolute;
      left: 94px;
      top: 610px;
    }
    .event-registration-form__text-on-a-path3 {
      background: #000000;
      border-radius: 0px;
      width: 181px;
      height: 38px;
      position: absolute;
      left: 137px;
      top: 918px;
    }
    .event-registration-form__text-on-a-path4 {
      background: #000000;
      border-radius: 0px;
      width: 176px;
      height: 52px;
      position: absolute;
      left: 132px;
      top: 904px;
    }
    .event-registration-form__rectangle-5 {
      background: #d9d9d9;
      width: 202px;
      height: 30px;
      position: absolute;
      left: 101px;
      top: 907px;
    }
    .event-registration-form__register {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 154px;
      top: 907px;
      width: 183px;
      height: 30px;
    }
    .event-registration-form__rectangle-6 {
      background: #d9d9d9;
      width: 8px;
      height: 3px;
      position: absolute;
      left: 69px;
      top: 239px;
    }
    .event-registration-form__rectangle-7 {
      background: #d9d9d9;
      width: 232px;
      height: 51px;
      position: absolute;
      left: 76px;
      top: 239px;
    }
    .event-registration-form__full-name {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 103px;
      top: 253px;
      width: 200px;
      height: 36px;
    }
    .event-registration-form__text-on-a-path5 {
      background: #000000;
      border-radius: 0px;
      width: 214px;
      height: 51px;
      position: absolute;
      left: 89px;
      top: 332px;
    }
    .event-registration-form__rectangle-8 {
      background: #d9d9d9;
      width: 232px;
      height: 53px;
      position: absolute;
      left: 76px;
      top: 343px;
    }
    .event-registration-form__register-number {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 82px;
      top: 358px;
      width: 303px;
      height: 35px;
    }
    .event-registration-form__rectangle-10 {
      background: #d9d9d9;
      width: 237px;
      height: 50px;
      position: absolute;
      left: 81px;
      top: 514px;
    }
    .event-registration-form__rectangle-11 {
      background: #d9d9d9;
      width: 236px;
      height: 54px;
      position: absolute;
      left: 82px;
      top: 602px;
    }
    .event-registration-form__age {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 154px;
      top: 610px;
      width: 106px;
      height: 48px;
    }
    .event-registration-form__rectangle-12 {
      background: #d9d9d9;
      width: 236px;
      height: 55px;
      position: absolute;
      left: 82px;
      top: 704px;
    }
    .event-registration-form__rectangle-13 {
      background: #d9d9d9;
      width: 237px;
      height: 50px;
      position: absolute;
      left: 81px;
      top: 791px;
    }
    .event-registration-form__e-mail-address {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 103px;
      top: 800px;
      width: 254px;
      height: 75px;
    }
    .event-registration-form__rectangle-14 {
      background: #d9d9d9;
      width: 257px;
      height: 42px;
      position: absolute;
      left: 80px;
      top: 862px;
    }
    .event-registration-form__events-to-register {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 82px;
      top: 867px;
      width: 299px;
      height: 37px;
    }
    .event-registration-form__rectangle-15 {
      background: #d9d9d9;
      width: 242px;
      height: 53px;
      position: absolute;
      left: 76px;
      top: 425px;
    }
    .event-registration-form__department {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 113px;
      top: 445px;
      width: 205px;
      height: 20px;
    }
    .event-registration-form__gender {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 137px;
      top: 526px;
      width: 98px;
      height: 29px;
    }
    .event-registration-form__phone-no {
      color: #000000;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 132px;
      top: 712px;
      width: 145px;
      height: 43px;
    }
```
## HTML:
```
    <div class="event-registration-form">
      <div
        class="event-registration-form__sports-registration-form-applicable-for-all-years-2025"
      >
        SPORTS REGISTRATION FORM
        <br />
        <br />
        APPLICABLE FOR ALL
        <br />
        YEARS 2025
        <br />
      </div>
      <img class="event-registration-form__star-1" src="star-10.svg" />
      <img class="event-registration-form__star-2" src="star-20.svg" />
      <img class="event-registration-form__star-3" src="star-30.svg" />
      <div class="event-registration-form__text-on-a-path"></div>
      <img class="event-registration-form__star-4" src="star-40.svg" />
      <img class="event-registration-form__star-5" src="star-50.svg" />
      <img class="event-registration-form__star-6" src="star-60.svg" />
      <img class="event-registration-form__star-7" src="star-70.svg" />
      <img class="event-registration-form__star-8" src="star-80.svg" />
      <div class="event-registration-form__text-on-a-path2"></div>
      <div class="event-registration-form__text-on-a-path3"></div>
      <div class="event-registration-form__text-on-a-path4"></div>
      <div class="event-registration-form__rectangle-5"></div>
      <div class="event-registration-form__register">REGISTER</div>
      <div class="event-registration-form__rectangle-6"></div>
      <div class="event-registration-form__rectangle-7"></div>
      <div class="event-registration-form__full-name">FULL NAME</div>
      <div class="event-registration-form__text-on-a-path5"></div>
      <div class="event-registration-form__rectangle-8"></div>
      <div class="event-registration-form__register-number">REGISTER NUMBER</div>
      <div class="event-registration-form__rectangle-10"></div>
      <div class="event-registration-form__rectangle-11"></div>
      <div class="event-registration-form__age">AGE</div>
      <div class="event-registration-form__rectangle-12"></div>
      <div class="event-registration-form__rectangle-13"></div>
      <div class="event-registration-form__e-mail-address">E-MAIL ADDRESS</div>
      <div class="event-registration-form__rectangle-14"></div>
      <div class="event-registration-form__events-to-register">
        EVENTS TO REGISTER
      </div>
      <div class="event-registration-form__rectangle-15"></div>
      <div class="event-registration-form__department">DEPARTMENT</div>
      <div class="event-registration-form__gender">GENDER</div>
      <div class="event-registration-form__phone-no">PHONE NO</div>
    </div>
```
## RULES AND REGULATIONS PAGE (FRAME 4):
## CSS:
```
    .rules-and-regulations,
    .rules-and-regulations * {
      box-sizing: border-box;
    }
    .rules-and-regulations {
      background: #d35252;
      height: 956px;
      position: relative;
      overflow: hidden;
    }
    .rules-and-regulations__rules-and-regulations2 {
      color: #5d0b0b;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 23px;
      top: 93px;
      width: 401px;
      height: 171px;
      -webkit-text-stroke: 1px #e52626;
    }
    .rules-and-regulations__please-read-carefully-the-policy-before-filling-it {
      color: #7fdb39;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 76px;
      top: 264px;
      width: 318px;
      height: 672px;
      -webkit-text-stroke: 1px #88dd60;
    }
    .rules-and-regulations__star-9 {
      width: 29px;
      height: 45px;
      position: absolute;
      left: 25px;
      top: 257px;
      overflow: visible;
    }
    .rules-and-regulations__star-10 {
      width: 29px;
      height: 45px;
      position: absolute;
      left: 25px;
      top: 383px;
      overflow: visible;
    }
    .rules-and-regulations__star-12 {
      width: 29px;
      height: 45px;
      position: absolute;
      left: 23px;
      top: 711px;
      overflow: visible;
    }
    .rules-and-regulations__star-13 {
      width: 29px;
      height: 45px;
      position: absolute;
      left: 25px;
      top: 864px;
      overflow: visible;
    }
    .rules-and-regulations__incase-you-forgot-username-and-password-simply-click-forgot-password-we-are-not-responsible-if-its-hacked {
      color: #7ce651;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 96px;
      top: 398px;
      width: 298px;
      height: 210px;
      -webkit-text-stroke: 1px #77c137;
    }
    .rules-and-regulations__participants-should-be-reach-the-venue-before-10-mins-game-starts {
      color: #6df363;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 76px;
      top: 669px;
      width: 286px;
      height: 135px;
      -webkit-text-stroke: 1px #63d95b;
    }
    .rules-and-regulations__all-they-need-to-carry-their-registration-pass-to-participate-in-the-event {
      color: #35ed3b;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 76px;
      top: 816px;
      width: 326px;
      height: 140px;
      -webkit-text-stroke: 1px #79f293;
    }
```
## HTML:
```
    <div class="rules-and-regulations">
      <div class="rules-and-regulations__rules-and-regulations2">
        RULES AND REGULATIONS
      </div>
      <div
        class="rules-and-regulations__please-read-carefully-the-policy-before-filling-it"
      >
        PLEASE READ CAREFULLY
        <br />
        THE POLICY BEFORE FILLING
        <br />
        IT.
      </div>
      <img class="rules-and-regulations__star-9" src="star-90.svg" />
      <img class="rules-and-regulations__star-10" src="star-100.svg" />
      <img class="rules-and-regulations__star-12" src="star-120.svg" />
      <img class="rules-and-regulations__star-13" src="star-130.svg" />
      <div
        class="rules-and-regulations__incase-you-forgot-username-and-password-simply-click-forgot-password-we-are-not-responsible-if-its-hacked"
      >
        INCASE YOU FORGOT USERNAME
        <br />
        AND PASSWORD SIMPLY CLICK FORGOT
        <br />
        PASSWORD WE ARE NOT RESPONSIBLE
        <br />
        IF ITS HACKED.
      </div>
      <div
        class="rules-and-regulations__participants-should-be-reach-the-venue-before-10-mins-game-starts"
      >
        PARTICIPANTS SHOULD BE REACH THE VENUE BEFORE 10 MINS GAME STARTS
      </div>
      <div
        class="rules-and-regulations__all-they-need-to-carry-their-registration-pass-to-participate-in-the-event"
      >
        ALL THEY NEED TO CARRY THEIR REGISTRATION PASS TO PARTICIPATE IN THE EVENT.
      </div>
    </div>
    
```
## CONTACT DETAILS PAGE (FRAME 5):
## CSS:
```
    .contact-details,
    .contact-details * {
      box-sizing: border-box;
    }
    .contact-details {
      background: #e66969;
      height: 956px;
      position: relative;
      overflow: hidden;
    }
    .contact-details__contact-details2 {
      color: #e90707;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 74px;
      top: 94px;
      width: 433px;
      height: 184px;
      -webkit-text-stroke: 1px #e93131;
    }
    .contact-details__contact-no-4534678909-contach-no-2-7876754321-e-mail-address-savevents-4-gmail-com-if-any-queries-please-free-to-ask {
      color: #390606;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 39px;
      top: 297px;
      width: 345px;
      height: 410px;
      -webkit-text-stroke: 1px #b32020;
    }
    .contact-details__we-are-eagerly-waiing-you-to-particate-in-the-events-supports-us-to-organize-such-events-in-future {
      color: #7c1919;
      text-align: left;
      font-family: "Inter-Regular", sans-serif;
      font-size: 24px;
      font-weight: 400;
      position: absolute;
      left: 47px;
      top: 715px;
      width: 367px;
      height: 190px;
      -webkit-text-stroke: 1px #640b0b;
    }
    .contact-details__line-10 {
      margin-top: -1px;
      border-style: solid;
      border-color: #ffffff;
      border-width: 1px 0 0 0;
      width: 433px;
      height: 0px;
      position: absolute;
      left: 0px;
      top: 185px;
      transform-origin: 0 0;
      transform: rotate(0.136deg) scale(1, 1);
    }
```
## HTML:
```
    <div class="contact-details">
      <div class="contact-details__contact-details2">
        CONTACT DETAILS
        <br />
        <br />
      </div>
      <div
        class="contact-details__contact-no-4534678909-contach-no-2-7876754321-e-mail-address-savevents-4-gmail-com-if-any-queries-please-free-to-ask"
      >
        CONTACT NO:4534678909
        <br />
        <br />
        CONTACH NO 2: 7876754321
        <br />
        <br />
        E-MAIL ADDRESS: savevents4@gmail.com
        <br />
        <br />
        <br />
        IF ANY QUERIES PLEASE FREE TO ASK....
      </div>
      <div
        class="contact-details__we-are-eagerly-waiing-you-to-particate-in-the-events-supports-us-to-organize-such-events-in-future"
      >
        WE ARE EAGERLY WAIING YOU TO PARTICATE IN THE EVENTS SUPPORTS US TO ORGANIZE
        SUCH EVENTS IN FUTURE
      </div>
      <div class="contact-details__line-10"></div>
    </div>
```
## output:

![alt text](<Screenshot 2025-11-18 104318.png>)
![alt text](<Screenshot 2025-11-18 104318.png>)
![alt text](<Screenshot 2025-11-18 104333.png>)
![alt text](<Screenshot 2025-11-18 104340.png>)
![alt text](<Screenshot 2025-11-18 104346.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
