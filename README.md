# Ahmet Kaya Weekly Hits


## Project Summary
This project collects Ahmet Kaya's weekly top 5 songs using Spotify API, retrieves the lyrics of these songs from alternatifim.com using a web scraping method, and then saves the data in a CSV file. 
This CSV file is automated to be sent to the user via an email at certain intervals.
The project is built using the Python programming language and aims to develop practical skills in web scraping, data processing, and automation.


## Technologies Used

- **Python**: Basic programming language
- **Spotipy**: Communicating with Spotify API
- **BeautifulSoup**: Web scraping
- **smtplib**: Sending emails
- **CSV**: Storing data
- **Requests**: Sending HTTP requests to web pages
- - **Windows Task Scheduler**: Automating tasks


## Project Steps

1. **Retrieving Data with Spotify API**:

- I pulled Ahmet Kaya's 5 most popular songs on Spotify using the Spotipy library.

2. **Web Scraping to Collect Lyrics**:

- I scraped the lyrics of these songs from Alternatifim.com.

3. **Data Processing and Saving to CSV File**:

- I combined the songs and lyrics from Spotify and saved them in a CSV file

4. **E-mail Sending**:

- By sending emails with Python, I automatically sent this data to a recipient.

5.**Automation**

- Automated with Windows Task Scheduler. Will be sent via e-mail every Sunday at 10:00


## Usage

Spotify API Keys: Create a Spotify Developer account to access the Spotify API and get your API keys. Make sure to place these keys correctly in the Python code.

Email Settings: You need to enter the correct SMTP information to send emails. The project uses the Gmail SMTP server, but if you are going to use another provider, you need to change the relevant SMTP information.

Scraping Data and Sending Emails: When the code is run, popular songs from Spotify and lyrics from Alternatifim.com will be pulled. The data will be saved in a CSV file and sent to the specified email address.

Automation with Task Scheduler: The script is configured to run on a specific day every week using the Windows Task Scheduler. In this way, the system automatically collects data and sends emails.


## Project Structure

- spoitfy_ahmetKaya_webScraping.py    # Main Python script
- ahmet_kaya.csv                      # CSV file with 5 popular songs of the week
- README.md                           # Project description
- explanation_video.mp4               # Project description


## Conclusion

This project helped me improve my web scraping and automation skills. It also gave me the opportunity to practice collecting data and automating it with a task scheduler.
