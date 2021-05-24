Somnium Sleep Tracker - Kotlin [WIP]
============================================================================
Introduction
------------
 - The prevalence of sleep disorders in India is high. A study has pegged the percentage of insomnia to be as high as 33% among adults in India. A healthy sleep Protects our mental health & physical health. Today, Technology has become one of the major reasons for sleep deprivation (by blue light emission through smartphones). The same power of technology can be used for the benefit of people. 

The Application
------------

- Using the application developed in Kotlin, a user can monitor sleep data for each night by using Start and stop buttons to stop recording. A click on the stop button redirects the user to a new fragment to assign a quality rating. The data is then stored in a room database and displayed on the home screen of the application.

- While not complete, this code is a Minimum Viable Prototype for this app. I plan to add the support for daily and weekly charts, recognition of sleep timings, resources to help patients with insomnia

Impplementation Details
------------
- This application demonstrates the use of Kotlin Coroutines, Logging data in a singleton room database and using data access obis based on the MVVM (Model–view–viewmodel) architecture in android development.
- I used ViewModel, ViewModelFactory and data binding to set up the UI architecture for the app. 
- Coroutines are non-blocking and are hence used for long-running tasks, such as all database operations. 
- Click handlers are implemented to trigger database operations. 
- A Transformations map is used to create a string from a LiveData object every time the object changes.

Screenshots of MVP
--------------
![image](https://user-images.githubusercontent.com/55680995/117707428-35539380-b1ec-11eb-8698-2dba336aa464.png)
![image](https://user-images.githubusercontent.com/55680995/117707381-253bb400-b1ec-11eb-961b-2609bafb8332.png)
![image](https://user-images.githubusercontent.com/55680995/117707403-2cfb5880-b1ec-11eb-9286-4d23d95b3383.png)
