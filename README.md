# Resume Builder
## This serves as the repository for a resume builder web app
### The app serves to create a 1 page resume optimized for a job description given the user's inputs of their resume details
### This README file is the project management tool I will be using to keep track of this project

## Overall Features
- [ ] Take in input as a JSON file of resume details
- [ ] Convert JSON file to a latex PDF file
- [ ] Include required details to resume
- [ ] Select details per section of the resume
- [ ] Download latex PDF file
- [ ] Optimize resume based on job description
- [ ] Take in data regarding resume performance
- [ ] Machine learning resume optimization
- [ ] Take in form field and save as JSON file
- [ ] API call to create resume based on JSON file
- [ ] Print all details if CV, limit to 1 page if resume
- [ ] Add 'Expected' to Graduation date if not yet finished
- [ ] Add option to remove Graduation date
- [ ] Separate first and last name form fields

### Resume Database Model
1. Work Experience
- Company Name
    - string
- Job Position
    - string
- Start Date
    - datetime
- End Date
    - datetime
- Location
    - string
- Mode
    - string (Full onsite, Remote, Hybrid)
- Details
    - list of (detail, importance level)
        - detail is string
        - importance level is int
- Tech stack
    - list of strings
2. Education
- School Name
    - string
- Graduation Date
    - datetime
- Course
    - string
- Location
    - string
- Details
    - list of (detail, importance level)
        - detail is string
        - importance level is int
- Courses covered
    - list of strings
3. Organizations
- Organization Name
    - string
- Position
    - string
- Start Date
    - datetime
- End Date
    - datetime
- Details
    - list of (detail, importance level)
        - detail is string
        - importance level is int
4. Skills & Interests
- General Field
    - list of strings
5. Projects
- Project name
    - string
- Github link
    - string link format
- Details
    - list of (detail, importance level)
        - detail is string
        - importance level is int
- Tech stack
    - list of strings
6. Character Reference
- Name
    - string
- Email
    - string email
- Contact number
    - int phone number
- Job position
    - string
- Location
    - string
- Description
    - string
7. Header
- Name
    - string
- Email
    - string email format
- Phone number
    - int phone format
- Website link
    - string link format
- Linkedin link
    - string link format
- Github link
    - string link format
8. Footer
- Last name