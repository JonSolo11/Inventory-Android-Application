# Inventory-Android-Application
Android application developed in Android Studio using Java. App allows users to track item counts, scan barcodes, take pictures, and quickly sort results. 

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The application was designed to allow users to create inventory items and track their quantity. My goal was to focus on a professional, easy-to-use UI that allows the user 
to quickly access item details and perform small inventory adjustments right on the home screen. I intentionally added functionality in deeper menus to make larger adjustments 
to force the user to interact with the application in more detail when making larger, more impactful changes. 

The application also required CRUD functionality and a login/register activity with verification. The application uses SQL lite for the database and offers encryption for data
protection. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application was centered around the idea that the user will be able to access the most vital functionality on the main screen. My next focus was ensuring that users can quickly access
specific products in various ways to promote versatility and ease of use when many items are added. The main activity centers around the idea that the user should be able to access
broad item lists, apply sorting functionality, and easily display buttons to navigate to other pages to allow for specific interactions like product lookup, low inventory items, and
barcode scanning. 

The design keeps users in mind by understanding that inventory apps are meant to be used as a secondary tool to a menial but important task. I wanted to ensure the main screen 
offered ample functionality with more detailed tasks only a click away. understanding that users may want to access their data in various ways allowed me to introduce sorting 
techniques, barcode scanning, and text searching either on the main screen or one click away. I wanted to ensure the app provided functionality if the user was away from their inventory
and if they had an item in their hand. These designs were successful because they considered many ways a user would want to interact with the app instead of forcing them into a linear
process that may not suit their needs. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

This is an ever-changing process as I continue to reflect on my own projects. For this application, I focused on the theme first to develop a basic UI that would operate as the background 
for the entire application. This provided me with a base that I could build on to add UI elements and functionality. I then focused on the core functionality of the app and built out each 
necessary function focusing first on the main page. I then added buttons and nav bars to the main page and implemented functionality to the buttons one at a time. 

The goal of this process was to choose a small task, bring it to completion, and then move on to the next path. This allowed me to have clear goals for every session and allow me to stop 
without actively building out a function. I do not like stopping development for the day in the middle of building something, so I work around that by breaking the application down into small 
manageable tasks. It’s easier for me as a solo developer to construct the application as a flow chart so to speak and fully implement a functional component before moving on to ensure I am 
engaged and aware of the necessities as opposed to slowly building out many functions at one time. That would be cumbersome and impossible to track for me personally. 

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

Constant testing on both an emulator and my personal device were incorporated in both a structured and unstructured manner. Every single unit was tested throughout development as well as the 
overall functionality of the app. This process not only revealed bugs and errors but allowed me to incorporate new ideas and adjust design aspects that didn't feel optimized. For example, the search 
bar was placed on its own activity. When the user pressed the button to switch to the search activity, they then had to press in the search bar to type. After testing, I realized the only 
intent for a user at this screen is to type in the search field so I adjusted the functionality to immediately open the keyboard and prepare for a search query. This saved the user one click but 
is a good example of the focus on making sure all user interactions serve a purpose. 

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

My biggest innovation was the willingness to incorporate functionality that was new to me and attack what I felt was a personal weakness. My goal was to challenge myself to deliver a UI that looked 
professional. This took research into existing applications and tools that I had not used before. For example, I implemented a barcode scanner which I felt was an integral piece of any inventory
application. When designing the UI, I worked from back to front and started with a background and color scheme that I liked and slowly built out and designed buttons and cards that accented and added
to the overall look of the system. The biggest innovation and revelation to my personal process was researching other apps and incorporating their design into my own project. 

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

This application was a clear example of my ability to understand the main goal of an application and the various ways a user will want to interact with it. Adding camera access to take photos of items
and a barcode scanner displayed my commitment to the user to optimize their experience. A lot of these concepts I learned from researching the Spotify app and realizing their design is based on their 
application being a secondary activity. I used that concept to ensure that user input isn't overly required unless they are taking advantage of a more detailed functionality. Even then I ensured
the process was as easy as possible. For example, when adding a new item, you can simply scan the barcode instead of typing it in. Not only does this speed up item entry, but it also removes user error 
from the equation. 

