To Execute this code:
  1) pip install captcha or pillow
  2) make an object of a class 'anyVariable = recaptchaTest()'
  3) Generate a random string from 'captcha_text = recaptchaTest.capRandomText()'
  4) pass Generated string in as an argument in 'recaptchaTest.capImage(captcha_text)'
  5) At the end Validation 'retVal = recaptchaTest.capValidate(captcha_text,input_captcha)'
      Note : Here I returned Int 1 = True , -1 = False
