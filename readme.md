# Student Result Sheet 

## Database Structure 

```
-------- tables --------
👉 students
- id
- name 
- roll (unique) 
- class

👉 subjects
- id
- name


👉 results
- id
- student_id
- subject_id
- marks 

student_id, subject_id, marks == All of them are primary key


------ relationship ------
1. A student hasMany subjects 
A subject is belong to a student

2. Student have many results
Subject has many results
Result is belongs to Students and Subjects
```

## TODO

 - [x] Migrations 
 - [x] Relationships
 - [ ] Controller and Route
 - [ ] Views