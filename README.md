University Course Management SystemOverviewThe University Course Management System is a text-based Java application designed to manage departments, courses, and professors in a university. The system leverages OOP concepts to ensure modular and efficient code. Users can interact with the system through a menu-driven interface to add, remove, and view various entities within the university structure.
FeaturesAdd/Remove Departments: Manage departments within the university.
Add/Remove Courses: Manage courses within a specific department.
Assign Professors: Assign professors to specific courses.
Display Information: View all departments, courses, and assigned professors.
University Statistics: Display total courses and other statistics using static methods.
Object-Oriented ConceptsComposition:
University contains Departments.
Department contains Courses.
Course is associated with a Professor.
Inheritance:
Course class inherits from Department class.
Static Members:
Track the total number of courses in the university.
Array of Objects:
Use arrays to store departments and courses.
Project StructureUniversity-Course-Management-System/
├── src/
│   ├── University.java
│   ├── Department.java
│   ├── Course.java
│   ├── Professor.java
│   └── Main.java
├── bin/
├── README.md
└── .gitignoreGetting StartedClone the repository:
git clone https://github.com/Ahmad-Mustafa-Iqbal/University-Course-Management-System.gitNavigate to the project directory:
cd University-Course-Management-SystemCompile the code:
javac -d bin src/*.javaRun the application:
java -cp bin MainContributionFeel free to fork the project, submit pull requests, or raise issues for any improvements and bug fixes.
LicenseThis project is licensed under the MIT License.
