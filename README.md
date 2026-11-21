
# Student Management System
![ GitHub followers ](https://img.shields.io/github/followers/rudradcruze?style=social) ![ GitHub Repo stars ](https://img.shields.io/github/stars/rudradcruze/student-management-system-shell-script?style=social) ![ GitHub repo size ](https://img.shields.io/github/repo-size/rudradcruze/student-management-system-shell-script) ![ YouTube Channel Subscribers ](https://img.shields.io/youtube/channel/subscribers/UCTZN1mzW0AwackW7axf7-OQ?style=social)

[Detailed Video on YouTube](https://youtu.be/JUPlUZW-z88)

This is simple student management system project by using shell scripting. By this project or program we can automate the manual track of student management. For example studnts enrollment, teacher assign, multiple teacher marks update, etc. By this program we can do that easily. Because of using the **CSV** file as the **database** we woulden't loose any data and we can perform operation realtime.

This project is for those we are excited and learning shell scripting and want to automate a simple and robust project. You and clone/fork this project and update it. Yes!! there is lots of places where I made mistakes and because of the time I wouden't correct them. Couse I need to submit the project.

In this project we have three acting users:
 * Admin
 * Teachers
 * Students

**Admin**
Admin has the conrol over the whole program. To loginto the admin the password id `admin123`. Admin can:
 * Create Teachers
 * Create Students
 * Delete Students
 * Create Semester
 * Create Course
 * Assign Teacher into the Course
 * Enroll Students into the Course
 * Modify assign Teacher
 * View all action and data

**Teacher**
Teacher is a restricted actor then the admin. A teacher only can update marks and view those students which specific course the teacher is assigned by the admin.

**Student**
Student is fully restricted actor. A studnets only can view his marks.
## Documentation

To run the Shell Script program flow the below steps

### Clone and Run
 If you want to run the script then first things first you need clone the project. For cloning just:
  * Open Terminal (Alt + Ctrl + T)
  * Run the `.sh` file

## Run Locally

Install banner package
```bash
  sudo apt install sysvbanner
```

Clone the project

```bash
  git clone https://github.com/rudradcruze/student-management-system-shell-script.git
```

Go to the project directory

```bash
  cd student-management-system-shell-script
```

Run the script

```bash
  bash studentManagementSystem.sh
```

 If you successfully run those command then you definitely successful to run the program.

NOTE: Admin default password was **admin123**

## Features

- Automatic student mark calculation
- Multiple User
- User Authentaction
- Track Student, Teacher
- Report Generate
- Handel Multiple Course Load
- Handel Complex Database



## License

[MIT License](https://github.com/rudradcruze/student-management-system-shell-script/blob/main/LICENSE)

