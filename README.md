# Workout Designer App (under development)
## Paused on December 2020 - Resumed in March 2021
## Brief Rundown:
This is an app created for a  physical trainer which drastically cuts down on the tedious process of designing and generating customized
workouts for their clients. The user will be able to save all necessary exercises into a local database to draw from and create detailed workouts, and in turn
will be able to save and retrieve these workouts. The workouts will be able to be generated in both Google sheets format with the option to save as a PDF. This app is written in Python, using the tkinter module for all GUI programming.

## Snapshots So Far:
### *Features and designs are not final*

**Options presented in the Main Menu**
![](https://github.com/LBellosguardo/ProjectDemos/blob/main/AppOutline.png)

**Exercise Menu: Add, Update, or Delete exercises to the database**
![](https://github.com/LBellosguardo/ProjectDemos/blob/main/ExercisesMenu.png)

**Example output of a workout in Excel format (this file was given as a roadmap)**
![](https://github.com/LBellosguardo/ProjectDemos/blob/main/ExcelExample.png)


## Checklist of Work Done / To Be Completed:
*Steps will be added and updated as development progresses*

- **Implement functionality for pages (frames) of the app and switching between pages via button commands**  :white_check_mark:
- **Main Menu basic outline and button functionality**  :white_check_mark:
- **Database Setup using SQLite3**  :white_check_mark:
- **Exercises page** :white_check_mark:
    - **Exercises table in the database**  :white_check_mark:
    - **GUI component for user to view / add / update / delete exercises** :white_check_mark:
    - **Integrate functionality between GUI and database components** :white_check_mark:
- 'Create a Workout' page (current)
- Functionality to generate a neatly formatted Google sheets document for a workout
    - **Connect to google sheets account via Google Cloud Services.** :white_check_mark:
    - Generate desired sheet formatting / create a copy from a template
    - Fill sheet with all workout components and information.
    - Functionality to save workout as a PDF file
- 'Retrieve a Workout' page
- **'Delete a Workout' page** :white_check_mark:
- Formatting and styling of the application

    
## Future Plans for this App
This app will immediately offer the utility of cutting out various repetitive processes and mindless formatting to the one local user.
Should the demand expand to several users or to include a trainer-client interactive portal, we may envision moving this app to a web-based configuration
using tools such as Django.

