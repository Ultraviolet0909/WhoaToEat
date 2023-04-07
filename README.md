Presentation:
https://warpwire.duke.edu/w/39EGAA/

# To function properly, add package FirebaseAnalytics and Firebase Auth 
- open xcode
- go to file, add package
- search for the package: https://github.com/firebase/firebase-ios-sdk
- click add package
- select FirebaseAnalytics and Firebase Auth as packages to add
- click add package again
- wait for packages to install
- build app

for use in app: 
- enter email and password and click create new account to create new account
- enter email and password and click login to login to existing account
- click reset password if you forget your password
    - a link will be sent to the email associated with the account with link to reset password

# Goal
- Restaurant Recommendations based on location and weather (Map Framework)

# Features
- Get current user location and weather information
- Use recommendations algorithm to pick appropriate restaurants
- Filter locations by the food categories
- Display possible food categories and allow user to select
- Mark and display those locations in a Map

# Architecture
- 4 view controllers: home page, list of restaurants/categories, map page with relative restaurant locations, detail page of selected restaurant
- Back end
  - get current location and then use weather api to get weather info
  - recommendation algorithm to recommend restaurants based on weather information
  - Map framework to search and display
