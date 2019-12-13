# Miva_GoogleReCaptcha
Adds Google ReCaptcha validation capability to Miva backend

Use this to configure the Miva backend to check a Google ReCaptcha token before proceeding with whatever default actions are associated with an event.

General installation / setup instructions:

1. download the .mv file here
2. download Miva's LSK (https://apps.miva.com/miva-merchant-limited-source-kit.html)
3. compile the .mv file
4. upload the .mvc file to your website
5. install and configure the module admin under system extensions:
- enter which Miva Actions you want it to watch (for example, ICST)
- enter the corresponding tolerance levels you want it to use (for example, .2)
- enter your Google ReCaptcha keys
6. add Google ReCaptcha javascript to your site (https://developers.google.com/recaptcha)
- be sure to use 'GoogleReCaptchaResponse' as the name of the form field for the ReCaptcha token
