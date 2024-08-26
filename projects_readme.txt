
Summary of projects Completed: 

1 Car Automation:
- Goal: To monitor the car via 4 external cameras mounted on the mirror 24x7. Using raspberry pi and external powerbanks with solar power as backup, the 4 cameras work 24x7 and catch outdside sorroundings.
Videos are saved on board and can be transmistted to NAS at home once the car is in wifi range. 
Glass Break sensors connected to glasses deter thieves. 
The cameras also show the side lanes while driving thereby making the driver aware of the vehicles in the lanes to it. 
Proximity sensing in the cameras saves the images of people if they're extremely close to the car while the car is not running just like Tesla. 


2 Home Automation: 
This consists of a suite of sensors. 
There is a camera connected to RPi which saves recording if motion is detected. 
Thermal sensor is places on the gas stove which keeps checking the temperature of the stove and informs the user if the temperature remains hot even after a certains period of time. 
There are laser, sound and motion, door alarm sensors in the house to keep monitoring for presence of unwated humans and infrom the user. 
Once motion is detected the user is informed. 
The clip with the motion is saved on the phone via remote access to the video clip. 
The video clip from the camera is stored by default on NAS. 


3 Financial App: 
This consists of the user providing the financial information to the project and the code then shows the following information: 
- If user has bank accounts, it checks for rate of interest information and updates the balance of the user based on the itnerest given by the bank for each month. 
- If user has CD/ FD account anywhere, the app takes the ROI from the bank and updates the user balance for that financial institution. 
- If the user has bonds etc, the app updates the balance based on the current ROI 
- If user has stocks, the app calculates the current value and the net profit/ loss. 
- It also shows the 401k balance information of the user. 
- It comapres that balance with other people in similar age group and shows where teh suer stands currently and how much they need to start savings to beat inflation. 


4 Stock Recommendation App: 
- There are various ways in which the app can be run. 
It essentially needs a list of stocks that need to be monitored. The script can create that list of stocks by itself or the user can provide that list based on their interest. 
The script then runs 50 different parameters on each stock.
Each param value like PE ratio etc is then evaluated and given a number between 0 to 1. 
For each of thr 50 params a number is assigned between 0 and 1. All stocks that have higher value than a given threshold are then plotted thereby from around 6500 companies on the NASDAQ, there are only about 100 companies that show up in the end in the plot. 


5 Streamlit App to view live stocks: 
This app shows the live stocks entered by the user. 
Each stock is updated evey 30 seconds. 
There are multiple rows of stocks, each row represents a given category fo stocks. Example: Retial, Tech, software, aviation, transportation, crypto etc. 


6 Streamlit app for stocks:
This App calculates the current value of all stocks owned by the user. it incldues all the stocks, crypto, RSU, ESPP stocks etc. 
It shows indivudal profit/loss from each stock as well along with showing how many stocks does user own etc.


7 Webscraping: 
Scraping through differnet websites to find the best price for a product User is looking for. 
This search is currently on google shopping, bhp, amazon. 
It looks at the product pricing on all websites along with its reviews and shows on the console. 


8 Linkedin Job Search: 
This tool looks for jobs based ont eh search criterion entered by the user. 
it downloads a list of jobs that meet the requirements along with the job link, details, salary, benefits etc and shows it to the user. 



9 QR Code generator: 
- To keep all the purchase records in oder. Most of the times we lose the receipt after some time. 
- This code, it creates a QR code for purcahse receipt that can be places on the product itself. Scanning the QR code shows the date and price of purchase along with the link to the receipt. No more worries of losing the receipt or doubts on proof of purchase as asked by the customs. 

10 Real Time Video Stitching/ Bird's eye view:
It takes multiple feeds (from 3 cameras), stitches them together to show a 360 view of the place. 

Multiple Other Projects that not just help with household but define the nature of user interaction with IoT. 
