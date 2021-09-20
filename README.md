# MLTask_AdEase
#This's about scraping ads in a website alongside extracting the logo's, background image, texts constituting the ad.
1. Download and open this task_AdEase.py file in VSCode
2. Open cmd prompt
3. Navigate to the file's location in cmd prompt
4. type "pip install bs4"
5. then, "pip install requests"
6. then, "pip install lxml"
7. then, "pip install parse"
8. If there's some package yet to be installed, that would be shown underlined in the VSCode. So, when you click there, the package would    be automatically installed.
9. type this command in the cmd prompt "python task_AdEase.py" to run the file.
10.Upon running "python task_AdEase.py", You can see the http requests of the ad getting printed in the course of which the ads in a website gets saved in the "images" folder in your system.
11. Eventually, you can see that the folders logo, text, background_image getting created where the corresponding contents are stored.
12. Stepping into the "text in button" extraction, ofcourse there are many ways in python to scrape them provided it's in html format    since the ads in this webpage are of purely image format and also that the ads keep changing dynamically, for this instance we can't really scrape the text from the button here.
13. Had it been usual html, this is how we would've scraped it:
bt = Button.text (the div content of button)
print(bt) //this would display the text in a button.
