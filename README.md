# myProjects
```typescript
type Course = { id: number, title: string, description: string; };
type Student = { id: number, name: string, courses: Course[]; };

let data_1: readonly Student[] = Object.freeze([]);
let data_2: { [student_id: string]: { name: string, courses: Course[]; }; } = Object.freeze({});

getStudent(student_id: number): Student{ }
addStudent(student: Student): boolean{ }
updateStudent(student: Student): boolean{ }
removeStudent(student_id: number): boolean{ }

getCourse(student_id: number, course_id: number): Course{ }
addCourse(student_id: number, course: Course): boolean{ }
updateCourse(student_id: number, course: Course): boolean{ }
removeCourse(student_id: number, course_id: number): boolean{ }
```
