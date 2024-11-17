## Description
This project focuses on manipulating data in JavaScript using modern ES6 features like `map`, `filter`, and working with arrays of objects. You'll learn how to perform operations like mapping, filtering, and reducing arrays efficiently.

## Project Tasks

### Task 0: Basic list of objects
- **File:** \`0-get_list_students.js\`
- **Description:** Implements a function \`getListStudents\` that returns an array of objects with attributes:
  - \`id\` (Number)
  - \`firstName\` (String)
  - \`location\` (String)
- **Example:**
\`\`\`
[
  { id: 1, firstName: 'Guillaume', location: 'San Francisco' },
  { id: 2, firstName: 'James', location: 'Columbia' },
  { id: 5, firstName: 'Serena', location: 'San Francisco' }
]
\`\`\`

---

### Task 1: More mapping
- **File:** \`1-get_list_student_ids.js\`
- **Description:** Implements a function \`getListStudentIds\` that:
  - Takes an array of objects as an argument.
  - Returns an array of \`id\` values using the \`map\` function.
  - Returns an empty array if the argument is not an array.
- **Example:**
\`\`\`
Input: [{ id: 1 }, { id: 2 }]
Output: [1, 2]
\`\`\`

---

### Task 2: Filter
- **File:** \`2-get_students_by_loc.js\`
- **Description:** Implements a function \`getStudentsByLocation\` that:
  - Takes a list of students and a city (string) as arguments.
  - Returns an array of students located in the given city using the \`filter\` function.
- **Example:**
\`\`\`
Input: students array, city = 'San Francisco'
Output: [
  { id: 1, firstName: 'Guillaume', location: 'San Francisco' },
  { id: 5, firstName: 'Serena', location: 'San Francisco' }
]
\`\`\`

---

## How to Run
1. Clone the repository:
   \`\`\`
   git clone https://github.com/<your-username>/alx-backend-javascript.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`
   cd 0x03-ES6_data_manipulation
   \`\`\`
3. Install dependencies:
   \`\`\`
   npm install
   \`\`\`
4. Run the tasks:
   \`\`\`
   npm run dev <task-file>.js
   \`\`\`
