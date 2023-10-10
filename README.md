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
- login (password is hidden behind asteriks and you can't change its visibility)
- password reminder
- change the application language (Polish/English)
  
**2. Main page:**
- logout
- add a new Player
- dev team contact (redirect to slack)
- change the application language (Polish/English)

**3. Players:**
- sort and filter columns
- download csv file (Possibility to download a .csv file and print a report only for the currently displayed list of Players. You can't do this for everyone or your chosen ones)
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
The application interface is simple, but does not attract the user's attention. There are no standout elements. As for the home page,based on Lighthouse report from DevTools, it has good performance and accessibility. When it comes to tabs like Player or Matches, page is not responsive.

### Intuitiveness
The application is not entirely intuitive. You have to figure out the Player edit options - there should be an icon for this purpose or pointer cursor.
No redirection to the home page after clicking 'Scouts Panel' in the header.
After typing words in the search bar and clicking the magnifying glass icon nothing happened, only when you click 'enter' button.
You cannot add a new player in a dedicated tab, only on the home page.
Generally, contact information is provided in the footer of the page, but here it is in the same place as the information describing the application. 

### Is everything OK?
* inability to create a new User
* click 'remind password',then leave the field 'email' empty or enter an incorrect email format and click the 'send' button, the message 'message sent successfully' appears,also when you provide the correct email address, the status code is 400
* add a new Player and changing the language from English to Polish, the names of the 'Submit' and 'Clear' buttons remain in English. Change the language back to English and some labels remain in Polish ('Łączy Nas piłka', '90 minut'). The same thing happens when editing an existing Player. 'Submit' and 'Clear' buttons stay in English while adding a new Match and change language to Polish.
* try to add a new report and be redirected to the 'Matches' tab
* possibility of adding negative,zero or unlimited number of weight and height of the Player, invalid phone number, date of birth from the future, many empty language fields
* the name and lastname field accepts numbers and special characters, for example you can type only '???' as name and lastname
* possibility of adding date from the future during adding a new match, also negative number and unlimited time played

# :pencil2: TASK 2
## Subtask 1
:point_right: [Check the document with test cases based on User Story ('Scouts Panel' app)](https://docs.google.com/spreadsheets/d/1JGg9uS7v3NDC_WYtkTtfBaefP9C-ARCKsDIYsF6J02U/edit?usp=drive_link)
## Subtask 2
:point_right: [Check the document with test cases based on "own experience" ('Scouts Panel' app)](https://docs.google.com/spreadsheets/d/1nNLI9MonP90easj0mgYLymLPnwAG2i-kftSs5grTijE/edit?usp=drive_link)
## Subtask 3
We write **test cases** to clearly document the various possibilities of handling modules within a given application. They gives us confidence during testing that we have not omitted any important functionality. Test cases are extremely important for many reasons: quality assurance, compliance verification, error identification, reporting, understanding software behavior.
## Subtask 4
:point_right: [Check the document with test cases based on "own experience" ('Pick Eat Up' app)](https://docs.google.com/spreadsheets/d/1yuKN49691dh2n0CElP1xA_3VRpGSM08heX2H4KZnGeg/edit?usp=drive_link)

# :pencil2: TASK 3
## Subtask 1
:point_right: [Testing according to test plans and reporting bugs](https://docs.google.com/spreadsheets/d/1C3jmhiCSO1VpqXf9C5msDXclF6IbzSzdcYXTnTI3o4I/edit?usp=drive_link)
## Subtask 3
:point_right: [Report on the tests performed](https://docs.google.com/spreadsheets/d/1K7V4aD6Hcr5pzeEQpC5QUHM0TUDcxbTzrjwI8xuf0ts/edit?usp=drive_link)

# :pencil2: TASK 4
## Subtask 2
:point_right: [Exploratory testing and bug reporting](https://docs.google.com/spreadsheets/d/1dBrlJPVxzBJa_XVi8oyo8-tNqYBKvNSuIC3pp_DqJIc/edit?usp=drive_link)
## Subtask 3
### What is this application for? What is the purpose of this application?
The application is a popular online advertising platform that is used to buy and sell various types of goods and services. The main purpose of the app is to allow users to post ads for items they want to sell or are looking for and connect with others who may be interested in those items.
### How would you describe the end user of the application?
The end user is a person who uses this application to buy or sell various products and services on the platform.Users are people with different needs and preferences.
### Do you think the application is user friendly?
Yes.Interface and functionalities are tailored to the needs of users.The application is easy to use, intuitive and with clear navigation.Appropriate labels, icons and buttons that clearly inform users about available functionalities.
### How would you improve the app?
I would definitely speed up app loading times, which means users can now access content and features faster. This greatly improves overall performance.
### What differences do you see between testing a web application and a native application?
Testing web and native applications differs in several important ways due to differences in the technology, platforms, and environments in which these applications operate.
Native mobile apps have their own unique user interfaces that are more optimized for a specific platform. UI testing includes platform-specific elements such as gestures, scrolling, and special controls.The user interface of a web application is typically based on web technologies such as HTML, CSS, and JavaScript. UI testing takes place across browsers and devices, and browser responsiveness and compatibility are key.
Web applications run in web browsers on various platforms.Native mobile apps are written specifically for specific mobile platforms, such as iOS (for Apple devices) or Android (for Android devices).
## Subtask 3
:point_right: [Mobile and web application tests (SwipeTo app). Link to JIRA.](https://olgagrzywa.atlassian.net/jira/software/projects/DCP/boards/3/backlog)

# :pencil2: TASK 5
## Subtask 1
:mag: Queries and operators learned during the course:
- SELECT
- FROM
- WHERE
- GROUP BY
- HAVING
- ORDER BY ASC/DESC
- DISTINCT
- BETWEEN
- IN
- LIKE
- NOT
- IS / IS NOT NULL
- COUNT()
- MIN()
- MAX()
- AVG()

## Subtask 3
1.Display the actors table in alphabetical order sorting by the surname column.
```sql
SELECT *
FROM actors
ORDER BY surname;
```
<img width="295" alt="1" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/efd91d0d-5fc8-4100-a7ae-bb23872c8fb1">

2.View a video that was made in 2019.
```sql
SELECT *
FROM movies
WHERE year_of_production = 2019;
```
<img width="341" alt="2" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/aff6512c-9a14-47b8-894d-de9b18490df1">

3.View all films made between 1900 and 1999.
```sql
SELECT *
FROM movies
WHERE year_of_production BETWEEN 1900 AND 1999;
```
<img width="496" alt="3" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/fa39a62a-c280-4ae6-a80b-84247be47aa3">

4.ONLY display the title and price of movies that are under $7.
```sql
SELECT title,price 
FROM movies 
WHERE price < 7;
```
<img width="287" alt="4" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/be3c9d6a-38fc-4396-9ea3-e9f2ef9289a6">

5.Use the logical AND operator to display actors with actor_id between 4-7 (4 and 7 should display). DO NOT USE the BETWEEN operator.
```sql
SELECT *
FROM actors
WHERE actor_id >= 4 AND actor_id <= 7;
```
<img width="290" alt="5" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/e644dce2-8964-46d4-807a-8e9fbec95223">

6.Display customers with id 2,4,6 using a logical condition.
```sql
SELECT *
FROM customers
WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6;
```
<img width="402" alt="6" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/9ad864f7-30ea-4e63-98fb-01c08bcf2ba5">

7.Display clients with id 1,3,5 using the IN operator.
```sql
SELECT *
FROM customers
WHERE customer_id IN (1,3,5);
```
<img width="387" alt="7" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/57aa4f48-6878-407e-9355-747ce6459848">

8.Display data for all people in the 'actors' table whose name starts with 'An'.
```sql
SELECT *
FROM actors
WHERE name LIKE 'An%';
```
<img width="250" alt="8" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/abc5184d-95a4-459e-bed5-69d7f9ff4104">

9.View details of a customer who does not have an email address provided.
```sql
SELECT *
FROM customers
WHERE email IS NULL;
```
<img width="304" alt="9" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/b6da0cf9-c59b-44d2-b206-30647e62a213">

10.View all movies priced above $9 and whose ID is between 2 and 8 movie_id.
```sql
SELECT *
FROM movies
WHERE price > 9 AND movie_id BETWEEN 2 AND 8;
```
<img width="382" alt="10" src="https://github.com/DLisiecka/challenge_portfolio_Dominika/assets/26362737/b96bb015-06ea-48fe-8919-0c3813ff6cf5">



















  
