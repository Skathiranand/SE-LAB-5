# Exp - 5 STUDENT ENROLLMENT SYSTEM

# AIM:

To study the problem statement, SRS document and draw all the UML diagrams of a Student Registration System.

# SRS (Procedure):
## UseCase Diagram
- First, identify the **actors** (like `Student`, `Admin`, `Faculty`) and the **system boundary** (the "Student Registration System" box). Then, list all the **use cases** (functions like `Register Courses`, `Manage Courses`, `View Grades`) inside the boundary and connect each actor to the functions they perform.

## Class Diagram
- Identify the main **classes** (nouns like `Student`, `Admin`, `Faculty`, `Course`). For each class, define its **attributes** (data like `+StudentID`, `+CourseName`) and **methods** (actions like `+EnrollCourse()`, `+ManageCourse()`). Finally, draw solid lines to show the **associations** (relationships) between the classes.

## Activity Diagram
- Map the step-by-step **workflow** for a single use case (like "Student Course Registration") from a start node to an end node. Use **action** boxes for steps (`Student Login`, `Course Enrollement`), **diamond** shapes for decisions (like "If Slot Available?"), and arrows to show the sequence of activities.

## Sequence Diagram
- Show how objects interact **over time** for one specific scenario (like "Course Enrollment"). Place the objects (`Student`, `Institution Portal`, `Faculty`) as vertical **lifelines** across the top. Then, draw **numbered messages** from top to bottom to show the exact sequence of calls between them.

## Communication Diagram
- This diagram shows the **relationships** between objects for a scenario (like "Enrollment Request"). Place the objects (`Student`, `Institution Portal`, `Faculty`) on the diagram, draw links between them, and then add **numbered messages** along those links to show the sequence of communication.

## Package Diagram
- Group related classes or components into **packages** (like folders, e.g., `Student`, `Admin`, `Faculty`, `Course`). This organizes your system into logical modules. Then, draw dashed arrows (dependencies) to show which packages rely on information from other packages.
- 


# DIAGRAMS:

## UseCase
![UseCaseDiagram1](https://github.com/user-attachments/assets/94f45f7d-424b-4681-aa0f-4ba0658eba77)


## Class
![ClassDiagram1](https://github.com/user-attachments/assets/5efb36ec-ea9c-4678-ab70-843816becd76)


## Activity
![ActivityDiagram1](https://github.com/user-attachments/assets/fa5181e5-c10a-42cd-a62d-b9ea209711af)


## Sequence
![SequenceDiagram1](https://github.com/user-attachments/assets/005c0241-c614-488b-83b4-0cdd2852c704)


## Communication
![CommunicationDiagram1](https://github.com/user-attachments/assets/02d9f6a7-e0b2-4521-b185-5635ceb8c9d0)


## Package
![PackageDiagram1](https://github.com/user-attachments/assets/b6771ac4-7a94-42e1-9f05-002dec180483)


# RESULT:

Thus the Student Registration System project was executed and the output was verified.
