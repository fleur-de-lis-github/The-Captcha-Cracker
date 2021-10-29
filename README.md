# The-Captcha-Cracker

A website uses Captchas on a form in order to keep the web-bots away. However, the captchas it generates, are quite similar each time:
- the number of characters remains the same each time  
- the font and spacing is the same each time  
- the background and foreground colors and texture, remain largely the same
- there is no skew in the structure of the characters.  
- the captcha generator, creates strictly 5-character captchas, and each of the characters is either an upper-case character (A-Z) or a numeral (0-9)/.  

![image](https://user-images.githubusercontent.com/73738414/139384903-0b5dbf66-baec-4a79-9f0d-32be0a4f130e.png)
![image](https://user-images.githubusercontent.com/73738414/139384908-aa0a640c-f659-4adf-8e61-587e237cb10c.png)
![image](https://user-images.githubusercontent.com/73738414/139384922-c74051a8-b726-4bf8-bd0a-8e81dcf91a46.png)

You are provided a set of twenty-five captchas, such that, each of the characters A-Z and 0-9 occur at least once in one of the Captchas' text. From these captchas, you can identify texture, nature of the font, spacing of the font, morphological characteristics of the letters and numerals, etc. Download this sample set from here for the purpose of creating an offline model for this task.

Given a set of unseen captchas on the same web form, your task is to identify the text on each of the captchas.
