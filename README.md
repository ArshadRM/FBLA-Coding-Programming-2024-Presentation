### Presentation of the [Coding and Programming Event](https://connect.fbla.org/headquarters/files/High%20School%20Competitive%20Events%20Resources/Individual%20Guidelines/Presentation%20Events/Coding--Programming.pdf) for the 2024 Georgia FBLA State Leadership Conference
*  We won 2nd and qualified to represent Georgia in the 2024 National Conference.
*  Source Code available upon [request](mailto:rafeekarshad@gmail.com).
  
# 2023-2024 Topic
Create a program that allows your school’s Career and Technical Education Department to
collect and store information about business and community partners. This program should
include information on at least 25 different partners (real or fictional), with details such as,
but not limited to, the type of organization, resources available, and direct contact
information for an individual. The program should enable users to search and filter the
information as needed.


## Presentation Slides
<img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/1.png?raw=true" alt="intro-slide"/>

<details>
  <summary>Mission & Architecture</summary>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/2.png?raw=true" alt="Our-Mission"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/3.png?raw=true" alt="Architecture"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/19.png?raw=true" alt="Tech Stack"/>
</details>

<details>
  <summary>Front-End</summary>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/5.png?raw=true" alt="User Interface"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/6.png?raw=true" alt="Themes"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/7.png?raw=true" alt="Search Report"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/8.png?raw=true" alt="Search Report (Cont.)"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/9.png?raw=true" alt="Managing Partners"/>
</details>

<details>
  <summary>Administration Features, Documentation, Credits</summary>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/11.png?raw=true" alt="Administration Features"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/12.png?raw=true" alt="Data Storage"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/13.png?raw=true" alt="Documentation and Credits"/>
</details>

<details>
  <summary>Source Code Snippets</summary>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/15.png?raw=true" alt="Server Code Snippet"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/16.png?raw=true" alt="Client Code Snippet 1"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/20.png?raw=true" alt="Client Code Snippet 2"/>
</details>

<details>
  <summary>Getting the award 😄</summary>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/winning.png?raw=true" alt="image-description"/>
  <img src="https://github.com/ArshadRM/FBLA-Coding-Programming-2024-Presentation/blob/main/presentation_images/images/18.png?raw=true" alt="Client Code Snippet 2"/>
</details>

# AAI Partners - The partner search app. (Original README.md)

## Features

*  Search partners using a tag/resource system and sort functions.
*  Smooth UI for users and admins.
*  Multiple themes for each user's taste.
*  Live partner database management.
*  Database backup and logging for each edit.

## Backup Documentation

The default location for the database is /database/data.sqlite.

If you would like to load a version of a database before an edit, use !dbEditLog.txt to find the time of the undesired edit. Then copy the most recent database backup BEFORE the date of the edit.

Example: You want to revert a deleted organization. 

> /database/backup/!dbEditLog.txt
```
DBEDIT	ADD	ORGANIZATION: Example Organization      2024-03-21T20-52-39
DBEDIT	DELETE	ORGANIZATION: Example Foundation  ID: 11    2024-03-21T20-52-49
```
> In this case, you would overwrite (/database/data.sqlite) with (/database/backup/data.sqlite_2024-03-21T20-52-39).


## Run Instructions

Requires node.js to run.

`node app.js` to run.

If you are running on Linux, you may need to reinstall the sqlite3 module from npm (CRLF and LF mismatch issues).

## Technologies Used

*   [Visual Code Studio](https://developer.android.com/studio/) - used to create this application.
*   [NodeJS](https://nodejs.org/en) - used to run the server-side code.
*   [Github](https://github.com/) - used for version control.
*   [picsum.photos](https://picsum.photos/) - used to get placeholder images.
*   [sqlite3](https://www.sqlite.org/index.html) - used to make and manage lightweight databases.
*   [JSON](https://www.json.org/json-en.html) - a lightweight data-interchange format.
*   JavaScript
*   HTML5/CSS

## Dependencies (npm)

*   [express.js](https://expressjs.com/) - used to host the server-side code.
*   [sqlite3](https://www.npmjs.com/package/sqlite3) - used to make connections to the sqlite3 databases.

