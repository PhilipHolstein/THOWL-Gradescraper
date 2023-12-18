# THOWL-Gradescraper
A simple web scraper that pulls your grades from the TH OWL server and notifies you by e-mail when a new grade is published

## How to use
1. Clone/Download this repository
2. Put your *.p12 Certificate in the folder of the repository
3. Change the parameters smpt_port, smpt_server, email_sender, email_password, email_receiver, cer_filename, cer_password in the file "Scraper.py"
4. run "sudo docker build -t gradescraper" 
5. run "docker run --restart unless-stopped gradescraper"

