# Thomas Jefferson Elementary School Dashboard

This project is a web application designed for Thomas Jefferson Elementary School to modernize their information management system. The application aims to replace their paper records with a digital solution for managing student enrollment, class management, and school events. The application is built using React for the frontend and Firebase for the backend.

[TJ Elementary School Dashboard Project.pptx](https://github.com/user-attachments/files/16042768/TJ.Elementary.School.Dashboard.Project.pptx)


### Key Features
- **Home Page**: View and navigate to various features of the web app.
- **Overall Dashboard**: View all classes.
- **Class Page**: View class details, including the roster and average grades.
- **Teacher Dashboard**: Teachers can add grades to students.
- **Student Directory**: View basic information of all students.
- **Teacher Directory**: View basic information of all teachers.
- **School Calendar**: View all school events.

### Functionality
- **CRUD Operations**: Create, Read, Update, Delete Students, Teachers, Classes, and School Events.
- **Roster Management**: Add and remove students and teachers from class rosters.
- **Grade Management**: Edit grades of students in rosters.
- **Database**: Store all items in Google Firebase.

### Design
- Professional and appealing design suitable for real school use.
- Consider basic UI principles for usability and navigation.

## Database Structure
- **Students**: Name, birthday, etc.
- **Teachers**: Basic information.
- **Classes**: Student enrollments and teacher assignments.
- **School Events**: Event details for the school calendar.

## Installation and Setup

### Prerequisites
Before setting up the project, ensure you have the following installed:

- **Node.js**: A JavaScript runtime environment.
- **npm**: Node package manager (comes with Node.js).
- **Firebase CLI** : Command-line tools for Firebase.

### Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/jzhuang03/TJ-Elementary-Dashboard.git
    cd TJ-Elementary-Dashboard
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up Firebase**:
    - Create a Firebase project.
    - Add your Firebase configuration to a `.env` file in the root directory.
    ```env
    REACT_APP_FIREBASE_API_KEY=your_api_key
    REACT_APP_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
    REACT_APP_FIREBASE_PROJECT_ID=your_project_id
    REACT_APP_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
    REACT_APP_FIREBASE_APP_ID=your_app_id
    ```

4. **Run the application**:
    ```bash
    npm start
    ```

