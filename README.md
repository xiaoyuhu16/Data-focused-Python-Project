# BosTrip: A Boston Hotel Recommendation App

BosTrip is a user-friendly GUI application to help travelers in Boston find the most optimal areas to stay when traveling in Boston based on various preferences, such as area safety, budget, dining option, and transportation accessibility.

Table of Contents
1. Features
2. Requirements
3. Installation & Setup
4. How to Use
5. Authors
6. Acknowledgments


## 1. Features
**Welcome Page1**: This is the first welcome page containing two buttons: Download New Data(Warning: Takes up to 2 hours), Use Previously Downloaded Data.
⋅⋅*After clicking 'Download New Data', the program will start scraping Boston hotel and restaurant dataset from websites, downloading Boston crime records, bus station, and bike station datasets from websites,and processing these datasets, which would take approximately 2 hours.
⋅⋅*After clicking 'Use Previously Downloaded Data', the program will load existing files into the environment.
**Welcome Page2**: This is the second welcome page containing three buttons: use hot, view visualizations, and exit the application.
⋅⋅*After clicking the hotel button, the user will direct to the hotel page.
⋅⋅*After clicking the visualizations button, it will direct to the visualizations page.
⋅⋅*After clicking the exit button, the user will exit, and the application will close.
**Hotel Page**: This page contains three buttons: Preference, No preference, return. Users can set their own preference or utilize the default preference.
· After clicking the Preference button the user will direct to the preference page.
· After clicking the No preference button, the user will direct to the budget page.
· After clicking the return button will go back to the previous page.
**Preference Page**: This page contains a text field, a submit button, a return button. It gives users three options:  1. Number of restaurants, 2. Number of crimes, 3. Transportation convenience. Users will be asked to enter the rank, such as 123,321,213 into the text field.
⋅⋅*After clicking the submit button will direct to the budget pages.
⋅⋅*After clicking the return button will go back to the previous page.
**Budget Page**: This page contains two text fields, one for minimum price, one for maximum price for per night, a submit button and a return button. Users can set their own budget range.
⋅⋅*After clicking the submit button will direct to the result pages.
⋅⋅*After clicking the return button will go back to the previous page.
**Result Page**: This page will show a list of hotels that we recommend to the User based on their preference and budget.
**Visualization Page**: Provides various map visualizations related to restaurants, crime rates, and transportation in Boston. These maps offer residents and visitors a clear picture of Boston's dining, safety, and commuting landscape.
···Restaurant Map: Navigate through Boston's culinary scene with our  detailed map showcasing restaurants peppered throughout the city. This map not only displays the location and basic information of these eateries but is also overlaid with the boundaries of ZIP codes in Boston, giving you a clearer geographical context.
···Crime Rate Map: Stay informed and cautious. This heat map provides a visual representation of crime rates within Boston, segregated by ZIP code boundaries. By color-coding each ZIP code based on the intensity of reported incidents, users can quickly gauge the safety of different areas.
···Transportation Map: Planning your commute has never been easier. This map features Boston's bus stops and bike stations. The bike stations are distinctly marked in blue for easy identification. And as with our other maps, the ZIP code boundaries are prominently displayed, ensuring you always have a geographic point of reference.
