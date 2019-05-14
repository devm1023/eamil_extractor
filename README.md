<p align="center">
  <img width="560" height="400" src="https://github.com/DiegoCaraballo/Email-extractor/blob/master/EmailExtractor.PNG">
</p>

# Working: 19-01-2019
- Exclude images - Add search option with images - SATUS (OK)
- Multi-thread to reduce search times - STATUS (PENDING)
- Search of several texts - STATUS (PENDING)
- Change the code to OOP - STATUS (PENDING)

# Email Extractor Functions

## English 
- (1) Extract emails from a single URL
- (2) Extract emails from a URL (Two Levels) - Search on the page and all its URLs
- (3) Do a Google search, save the Urls found and search the emails
- (4) You can list the saved emails
- (5) You can save the mailing list in a .txt file
- (6) Delete Emails from data base

- The emails are stored in a Sqlite database ("Emails.db")

**Versión:** Python 3.x.

# Required modules - Modulos necesarios

**Update 26/07/18**

if you use windows try pip update and then:
- pip3 install google

If you are in Linux, update pip and then:
- sudo apt-get install python3-pip
- sudo pip3 install google

Then Install:
- google-search
- BeautifulSoup
- fake-useragent (NEW)

