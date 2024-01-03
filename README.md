# Zillow Data Entry

## Requirements

Run these commands on the local terminal on Pycharm:

pip install bs4     
pip install --upgrade pip     
pip install selenium     
pip install --upgrade pip      
pip install requests     

## What is Zillow Data Entry?

It is a python bot created with beautiful soup, selenium, requests, and google forms. Beautiful Soup is used for web scraping the rent per month, selenium for automatization and google form for data entry. Zillow is a very strick website with extremely aggressive anti-robot policies. See https://www.zillow.com/robots.txt. Instead of [zillow.com](https://www.zillow.com/), a clone website is being used which allows the user to do the web scraping: https://appbrewery.github.io/Zillow-Clone/

## How does it work?

Step 1. Go to https://docs.google.com/forms/ and create a form. Add 3 questions to the form, and make them short-answer.

<img width="447" alt="Screenshot 2024-01-02 at 8 23 06 PM" src="https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/f63c91e9-ede5-4598-859e-a37c01c1c663">

Step 2. Beautiful requirements
<ol>
  <li>Use BeautifulSoup/Requests to scrape all the listings from the Zillow-Clone web address</li>
  <li>Create a list of links for all the listings you scraped. e.g.</li>
  <img width="521" alt="Screenshot 2024-01-02 at 8 25 07 PM" src="https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/61ec3601-bf9e-4bba-9e0a-f7080a9d8d61">

  <li>Create a list of prices for all the listings you scraped. e.g.</li>
  <img width="520" alt="Screenshot 2024-01-02 at 8 25 53 PM" src="https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/134b2973-14d7-4eb0-b797-2e9a07a5a564">

  <li>Create a list of addresses for all the listings you scraped. e.g.</li>
  <img width="520" alt="Screenshot 2024-01-02 at 8 26 50 PM" src="https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/8195c983-e8ad-468d-83d6-450b036d1cd1">
</ol>

Step 3. Selenium Requirements
<ol>
  <li>Use Selenium to fill in the form you created (step 1,2,3 above).</li>
  <li>Once all the data has been filled in, click on the "Sheet" icon to create a Google Sheet from the responses to the Google Form.</li>
</ol>

## Demo

https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/28df98af-0f8c-4d7b-a755-f5e9cde3ad27

<img width="1440" alt="Screenshot 2024-01-02 at 8 48 57 PM" src="https://github.com/CoboAr/Zillow-Data-Entry/assets/144629565/74e9b3f8-54a8-42fa-94ba-54a7db918168">

Enjoy! And please do let me know if you have any comments, constructive criticism, and/or bug reports.
## Author

## Arnold Cobo


  

