# ERA-Scan

    1. Make a scraper which fills the form at https://parivahan.gov.in/rcdlstatus/?pur_cd=101 and scrapes the resultant data.
    2. I'm Using the Python library selenium, pytesseract, PIL instead of [requests, lxml along with xpath to do so.]
    3. The page contains a Captcha so write a dummy function get_captcha() which outputs the text of captcha based on the input image of the captcha, assume that the captcha can be wrong sometimes, so handle retries accordingly. For testing purposes, you can use the Python input function to enter captchas manually while scrapping, but you will be judged after we replace it with our get_captcha() and run tests on thousands of samples, so make sure to make this scrapper fault tolerant and output useful error messages.
