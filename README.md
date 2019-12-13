# Miva_GoogleReCaptcha
Adds Google ReCaptcha validation capability to Miva backend

Use this to configure the Miva backend to check a Google ReCaptcha token before proceeding with whatever default actions are associated with an event.

General installation / setup instructions:

- choose Option A or B below, then proceed to the next section

*Option A: Download and install compiled module*
1. download the .mvc file here

*Option B: Download the uncompiled module and compile it yourself (do this if you want to make changes)*
1. download the .mv file here
2. download Miva's LSK (https://apps.miva.com/miva-merchant-limited-source-kit.html)
3. compile the .mv file

*Proceed with module installation*
1. upload the .mvc file to your website
2. install and configure the module admin under system extensions:
- enter which Miva Actions you want it to watch (for example, ICST)
- enter the corresponding tolerance levels you want it to use (for example, .2)
- enter your Google ReCaptcha keys
3. add Google ReCaptcha javascript to your site (https://developers.google.com/recaptcha)
- be sure to use 'GoogleReCaptchaResponse' as the name of the form field for the ReCaptcha token
