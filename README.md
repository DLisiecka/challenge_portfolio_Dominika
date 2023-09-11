# :pencil2: TASK 1 
## Subtask 1
10/10 :sunglasses:
## Subtask 3
Hello, my name is Dominika. :wave:\
\
I chose this project to learn the secrets of manual testing through practice. I want to start working in the IT field, because I have always liked new technologies, creative, unconventional thinking and problem solving.
I would like to create a suitable portfolio to start a new career path. I hope, this challenge will help me with that!\
Sooo...Welcome and follow my work. :point_down:
## Subtask 4
### Description
As a talent scout you can use the 'Scouts Panel' application to track and add information about football players. There is also a panel for managing matches and creating reports.
### Functionality
**1. Login window:**
- login
- password reminder
- change the application language (Polish/English)
  
**2. Main page:**
- logout
- add a new Player
- dev team contact
- change the application language (Polish/English)

**3. Players:**
- sort and filter columns
- download csv file
- print the report about Players
- selection of visible columns
- search bar
- edit information about the Player
- reset filtering

**4.Matches:**
- add a new Match
- edit information about the Match
- create a report

**5.Reports:**
- adding a new Report
- editing reports

### Interface evaluation
The application interface is simple, but does not attract the user's attention. There are no standout elements. As for the home page, it has good performance and accessibility. Other tabs are not responsive.

### Intuitiveness
The application is not entirely intuitive. You have to figure out the Player edit options - there should be an icon for this purpose.
No redirection to the home page after clicking 'Scouts Panel' in the header. Possibility to download a .csv file and print a report only for the currently displayed list of Players. You can't do this for everyone or your chosen ones.
After typing words in the search bar and clicking the magnifying glass icon nothing happened, only when you click 'enter' button.

### Is everything OK?
* inability to create a new User
* click 'remind password',then leave the field 'email' empty or enter an incorrect email format and click the 'send' button, the message 'message sent successfully' appears,also when you provide the correct email address, the status code is 400
* add a new Player and changing the language from English to Polish, the names of the 'Submit' and 'Clear' buttons remain in English. Change the language back to English and some labels remain in Polish ('Łączy Nas piłka', '90 minut'). The same thing happens when editing an existing Player. Submit' and 'Clear' buttons stay in English while adding a new Match
* try to add a new report and be redirected to the 'Matches' tab
* 
