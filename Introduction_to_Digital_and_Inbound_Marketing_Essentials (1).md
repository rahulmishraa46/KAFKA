Here's the problem statement formatted as a GitHub-ready `README.md` file:

```markdown
# MongoDB CRUD CLI Application

## Problem Statement

### Objective
Develop a **command-line interface (CLI) application** using Python and MongoDB that allows users to perform **CRUD (Create, Read, Update, Delete) operations** on a database of person records. The application should provide an interactive menu-driven system for managing records.

## Requirements

### 1. Functional Requirements
The application must support the following operations:

#### A. Add a New Record (Create)
- Prompt the user to enter:
  - First Name
  - Last Name
  - Date of Birth (YYYY-MM-DD)
  - Gender
  - Hair Color
  - Occupation
  - Nationality
- Insert the record into MongoDB
- Display success/error message

#### B. Find a Record (Read)
- Search by First Name and Last Name
- Display full record if found
- Show error if not found

#### C. Edit a Record (Update)
- Search by First Name and Last Name
- Display current values
- Allow field-by-field updates
- Preserve existing values if user presses Enter
- Confirm update success

#### D. Delete a Record (Delete)
- Search by First Name and Last Name
- Show record and request confirmation (y/n)
- Delete if confirmed, else cancel

#### E. Exit Application
- Close program gracefully

### 2. Technical Requirements
- Python CLI interface
- PyMongo for MongoDB interaction
- Database collection: `people`
- Record structure:
  ```json
  {
    "first_name": "string",
    "last_name": "string",
    "dob": "date",
    "gender": "string",
    "hair_color": "string",
    "occupation": "string",
    "nationality": "string"
  }
  ```
- Proper error handling

### 3. User Experience Requirements
- Intuitive menu navigation
- Clear operation feedback
- User-friendly prompts

## Expected Output
```
--- MongoDB CRUD CLI ---
1. Add a Record
2. Find a Record
3. Edit a Record
4. Delete a Record
5. Exit
Select an option (1-5):
```

## Deliverables
1. Python script (`mongo_project.py`)
2. MongoDB database with `people` collection
3. README.md containing:
   - Setup instructions
   - Dependencies
   - Usage examples

## Evaluation Criteria
✅ **Functionality** - All CRUD operations work  
✅ **Code Quality** - Well-structured and documented  
✅ **Error Handling** - Handles invalid inputs  
✅ **User Experience** - Clear and intuitive  

## Bonus Features (Optional)
🔹 Partial name search  
🔹 Input validation  
🔹 Export/import records  

```

This markdown file:
1. Uses proper GitHub-flavored markdown syntax
2. Includes clear section headers
3. Has consistent formatting
4. Presents information in a structured way
5. Uses emojis and code blocks for better readability

You can copy this directly into a `README.md` file in your project repository. Would you like me to make any adjustments to the formatting or content?
