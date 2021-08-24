# Project 1 - Clicker Game
- Goal: To build a Cookie Clicker like game using a theme that is designed by you.  Use the main website as a reference (http://orteil.dashnet.org/cookieclicker/)

## I. Requirements

### Required App Features for Milestone #1 (see dropbox for due date)
***This is worth 15% of the Project 1 grade***

  - For this first deliverable, the theme of the project will be defined and documented.
  - Create a Word Document with the design of the clicker game
  - There is no fixed format for document.
  - Label things as needed verses nice to have or stretch goals.
  - Plan out the display and all of the possible screens
    - Example screens (This are not all screen and are an example only)
        - Main page
        - About Page
        - Splash screen
        - Settings Page
        - Stats Page
        - Mini Games
  - Plan out all of the things that can be purchased

<hr><hr>

### Required App Features for Milestone #2 (see dropbox for due date)
***This is worth 15% of the Project 1 grade***

  - The app is universal and runs on both phones and tablets. (*-2% if not done*)
  - The app uses Xamarin or Maui (*-2% if not done*)
  - The app will start up with the "cookie" to click on. (*-2% if not done*)
  - Display a score and a accumulation rate. (*-2% if not done*)
  - Save progress when you reopen the app. (*-2% if not done*)
  
*Tip: This might be a little tricky for you. *
			
- The app has a custom App icon - designed and created by you - for all tablet and phone sizes. [Here is a tutorial on how to create an app icon](https://designmodo.com/ios-app-icon-photoshop). If you already have an image file you think could work as your icon (at least 1024x1024 pixels ideally), services like https://makeappicon.com/ios12icon will generate all of the required icon sizes for you. (*-3% if not done*)
- Create a Splash Screen that has the name of your app and your name on it. Use an image (drag out an `Image`) and make sure it looks good on both phones and tablet sizes. (*-3% if not done*)

<hr><hr>

<a id="checkpoint2"></a>

### Required App Features for Milestone #2 (see dropbox for due date)
***This is worth 30% of Project 1 grade***

- Add a Collectionview/Listview with all of the potential purchases (*-5% if not done*)
- Add a viewmodel containing the data for all of the purchases and the game itself (*-5% if not done*)
- Add a page for instructions for the user (*-3% if not done*)
- When the current accumulated amount is high enough to purchase one of the enhancements, enable the row in the CollectionView/ListView and allow the purchasing.
- Add UI to allow you to sell things that you own.
- Add UI for you to be able to buy/sell 1 or 10 (even 100 if you want) of a purchase
- Hide the status bar - you can do this on the main settings page for the app (<i>-2 if not done</i>)
- Make sure your app name matches the name on the icon  - see <a href="">[developer.apple.com  - Updating the Display Name of Your App](https://developer.apple.com/library/content/qa/qa1823/_index.html) and [Making the app name on a device consistent with the name in iTunes Connect](https://developer.apple.com/library/archive/qa/qa1892/_index.html) (<i>-2 if not done</i>)
- Get rid of all compiler warnings - including those for unused variables and broken Storyboard constraints (<i>-1 per compiler warning</i>)

<hr><hr>

<a id="finalsubmission"></a>

### Required Final App Features  (see dropbox for due date)
***This is worth 30% of Project 1 grade***
- Add styling and animations to make it look more professional
- Add "Lucky Cookies" that will pop up from time to time to give the user extra cookies, higher accumulation rates, etc.
- The app should by now been thoroughly tested on hardware:
  - The app should display properly on either landscape OR portrait orientation, and on both phones and tablet. I recommend choosing one orientation for the app, either portrait or landscape, and making that the sole orientation of the app
  - There should be no obvious usability issues
  - State Preservation. The user's current state will be stored in `Preferences`
- The user can share their progress with others using Social Networks with the Xamarin Essentials Share Plugin (https://docs.microsoft.com/en-us/xamarin/essentials/share?tabs=android)
- The app meets all requirements of previous milestones (*-5% per requirement not met*)
- Code Conventions
  - Class names are capitalized, instance variables begin in lowercase (*-1 per incidence*)
  - Code files in the solution are organized in groups for example, *Pages or Views*, *Model*, *ViewModel*, *Helpers*, *Images* etc...(*-5 if not done*)
  - Get rid of all compiler warnings - including those for unused variables and broken Storyboard constraints - but don't wory about missing icon warnings (*-1 per compiler warning*)
  - Use `#region <Some Category>` in your view controller classes to organize your code - possible categories include:
    - `variables`
    - `Private Helper Methods`
    - `Public Methods`
    - `Initialization`
    - `GestureRecognizer Methods`
    - and so on
  - If the app crashes, there will be an additional penalty of -10%

<hr><hr>

## II. Extra Features:

- Adding extra things to a project help you to stand out better and make for better demos for employers. Be sure to document your extras in a seperate file or in the comments field of the dropbox. If you don't, you will not get credit for them. Here are some ideas:
  - Working in both orientations
  - Supporting multiple languages
  - Add mini games like the website has now
  - Add the popcorn like the website has now
  - If you would like, I could setup a fake ad server where you can add ads to your game. You would need to call the ad server and display the ad.
  - you decide!!! ...

<hr><hr>

<hr><hr>

## III. Code Hints

### Hint #1
- Animating parts of the game can really change the look and feel.  Use this as an example of how to do it.

  (https://www.grapecity.com/blogs/how-to-add-animation-in-xamarin-forms#:~:text=Xamarin%20provides%20API%20infrastructure%20for%20creating%20animations%20that,let%20you%20quickly%20add%20animations%20to%20almost%20everything)

 
### Hint #2
*Sick of everything in your app being gray?*

Xamarin controls allows you to change the styling of UI elements for either your entire app, or just for for specific elements. Styles (or CSS stylesheets) can be used to have a consistant look and feel for all of your pages.

- See this tutorial for an introduction: https://docs.microsoft.com/en-us/xamarin/get-started/quickstarts/styling?pivots=windows



### Hint #3
- When doing the final testing your app, be sure to delete it off of the simulator and your device, reinstall it, and be sure that it works in the "first run" state.
- This is necessary to do so that you can be 100% sure that your settings code is properly written


<hr>
<hr>

