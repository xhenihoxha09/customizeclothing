Names and Surnames:
Xheni Hoxha
Sidra Shegaj 
Erik Draçi

Project Description:
A simple application for selecting clothes with basic error handlings and data loading functionality.
Overall this project shows firstly a main page where you can customize clothes by type,color and size and then you 
click dhe view button and is going to show the customization.
Which you can also save and by saving it is going to show on the load page.Which we have named as LoadActivity.

Tasks Used:

Creating Activities: 
The project involves creating several activities including MainActivity, ClothesActivity, and LoadActivity. Each activity serves a specific purpose in the application.

UI Layout Design: 
Designing the user interface (UI) layout for each activity using XML files (activity_main.xml, clothes.xml, and load.xml and loadview.xml). 
This includes defining views such as TextViews, Spinners, Buttons, LinearLayouts, ImageViews, and ListViews.

Initializing Views: 
Initializing views within each activity's onCreate() method using findViewById() method.

Handling User Interactions:
Implementing onClickListeners for buttons (btnview, load, and btnsave) to handle user interactions such as clicking buttons to perform actions like saving data, loading data, or navigating to other activities.

Data Management: 
Managing data using SharedPreferences.This involves storing and retrieving data (positions, clothing details) using SharedPreferences to persist data across different sessions of the application.

Dynamic Listview: 
Implementing a dynamic ListView in the LoadActivity to display a list of saved clothing items. This involves creating a custom adapter (Listview2Adapter) to populate the ListView with data and customizing the layout of each item in the ListView.

Image Handling: 
Dynamically setting ImageView resources based on the type and color of clothing items selected by the user.
Validation and Error Handling: Implementing validation checks and displaying error messages (using Toast) to prompt users to complete required actions or input valid data.

Overall, the tasks involve creating a functional Android application for managing and displaying clothing items, handling user interactions, managing data persistence, and providing a smooth user experience.
