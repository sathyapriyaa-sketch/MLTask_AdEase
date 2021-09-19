# MLTask_AdEase
#This's about scraping ads in a website alongside extracting the logo's, background image, texts constituting the ad.
Download and open this task_AdEase.py file in VSCode
Open cmd prompt
Navigate to the file's location in cmd prompt
type "pip install bs4"
then, "pip install requests"
then, "pip install lxml"
then, "pip install parse"
If there's some package yet to be installed, that would be shown underlined in the VSCode. So, when you click there, the package would be automatically installed.
then, type this command in the cmd prompt "python task_AdEase.py" to run the file.
Upon running "python task_AdEase.py", You can see the http requests of the ad getting printed in the course of which the ads in a website gets saved in the "images" folder in your system.
Eventually, you can see that the folders logo, text, background_image getting created where the corresponding contents are stored.
Stepping into the "text in button" extraction, ofcourse there are many ways in python to scrape them provided it's in html format since the ads in this webpage are of purely image format and also that the ads keep changing dynamically, for this instance we can't really scrape the text from the button here.
Had it been usual html, this is how we would've scraped it:
bt = Button.text (the div content of button)
print(bt) //this would display the text in a button.
