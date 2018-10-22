# 08-Project1_v2

Crypton is a crypto currency tracker that gives users the ability to monitor every crypto currency and exchange that exists.  On the left hand side choose an exchange. Your selection will appear on the button and news about the exchange will populate on the right hand side of the page.  

After you have made your exchange selection, use the coin button at the top of the page to select which coin your interested in.  A graph tracking the price  of your coin will appear, and your selection is stored in firebase.  You can choose different time frames to monitor your currency as well.  

The biggest challenge with this project was handling APIs.  Nearly every API had a CORS error that would not allow the user access.  The error was resolved by contacting the owner of the API and whitelisting the Github domain.  Also, there was a challenge with the news API and calling news pertinent to the exchange selected.  Some exchanges have very little news, so there are a lot of duplicate news articles.
