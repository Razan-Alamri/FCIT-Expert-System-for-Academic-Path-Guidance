# FCIT Expert System for Academic Path Guidance

This project is an expert system designed to assist students at the Faculty of Computing and Information Technology (FCIT), King Abdulaziz University (KAU), in choosing the right academic path. The system evaluates the student's interests and tendencies to recommend the most suitable major within the fields of Computer Science (CS), Information Technology (IT), or Information Systems (IS).

---

## Introduction

### Purpose of the System
The system aims to help students avoid unnecessary confusion and effort when deciding on their academic major. By understanding their interests and tendencies, the system provides personalized recommendations.

### Users of the System
- Students at FCIT  
- Academic advisors  

### Experts of the System
The system serves as a virtual academic advisor by determining the most suitable study path for students based on their skills and interests.

### Resources
- Official FCIT website for study plans and pathways  
- Academic advisors at FCIT for characteristics of each path  

---

## Program Implementation Idea

### Knowledge Base: A List of Rules
The system uses a predefined set of rules based on students' specialization, interests, and skills to recommend academic paths. Examples of recommendations include:  
- **Intelligent Systems** for students interested in mathematics, algorithms, and technology advancements  
- **Computer Networks** for students skilled in IoT, network protocols, and data analysis  
- **Database** for students focused on database management and design  

Refer to the [full report](FCIT%20Expert%20System%20Report.pdf) for detailed rules.

### Techniques Used to Acquire Knowledge
The system employs **Backward Chaining**, a method in Artificial Intelligence where reasoning starts from the goal and works backward to determine the supporting facts. 

Example:  
If a student has analytical skills, knowledge of IoT, and network protocols, the system recommends the **Computer Network** path.

---

## References
- [FCIT Official Website](https://fcit.kau.edu.sa)  
- Academic advisors and resources provided by FCIT  

---

## Appendix

### Source Code
The project was implemented in Python using backward chaining logic. Access the complete code [here](ExpertSystem.ipynb).  

