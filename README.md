# LetterboxdUnfollowers
Find who unfollowed you on letterboxd.

1) You have to use Chrome or Chromium based browser to use this extension. Download the extension from this website and add it to your browser.
https://chrome.google.com/webstore/detail/web-scraper-free-web-scra/jnhgnonknehpejjnehehllkliplmbmhn/

2) Go to your letterboxd page and open Inspect (Right Click>Inspect or you can use your keyboard according to your computer.) Then you will see the "Web Scraper" on one of the tabs. Click to the Create new sitemap button and "Import Sitemap".

3) Insert the code i gave in the repository included in the file named "letterboxdUnfollowers.txt" and change "###YOURUSERNAME###" to your username. Then open the letterboxd profile of yours and click Scrape from Sitemap button. 

4) Then wait. The script will be collecting all your information. After the scrape finished clicked "Export data" and export as .XLSX file.

5) After downloading the file open it on Excel or Google Sheets (My choice) and delete the duplicated ones. I seperated the followed and following ones in A and B column so i used this code in C1 "=unique( { A1:A; B1:B }, false, true )"

6) Then copy all of the column and paste it to this website "https://capitalizemytitle.com/tools/column-to-comma-separated-list/#Settings" and add " (Quotation mark) to the prefix and suffix.

7) Go to scraper again and create new sitemap that i added to this repostiry as #LetterboxdUnfollow but change the ###USERLINKs### area to your userlinks. 

You are ready to go just start scraping and script will remove all of your unfollowers.

Hope it works for you like it worked for me.
I searched a lot of websites and i wasn't able to find anything about this situation so i came up with this. 
