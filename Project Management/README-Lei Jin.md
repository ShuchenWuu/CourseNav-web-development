# Project Roles
In the early stage of the project, I was the data administrator of my team that responsible for setting up MongoDB, writing API to connect MongoDB to our web application, collecting course dependency data, uploading and maintaining data collections in our database.
In the middle to late stage of the project, I was one of the frontend developers in our team that responsible for developing the Course Relationship search function and the Course Advisor input function. 

# Contributions
## CourseNav web application
### Database
- Registered and set up a private server on MongoDB Atlas for our project.
- Collected course dependency data and created a corresponding data collection in our MongoDB.
- Refined our data collections to improve our query efficiency.
### Backend
- Wrote API to connect our applicaiton to the MongoDB Atlas server. (GitHub: Team-05/backend/app.js)
- Wrote API to acquire course list from couses data collection then returned the data to the frontend. (GitHub:  Team-05/backend/routes/course.js /courseList)
### Frontend
- Converted our old Course Relationship search (developed by a function-based component) to a new search function (developed by a class-based component) with an autocomplete feature. (GitHub: Team-05/frontend/src/Components/SearchBox.js)
- Created an axios instance to help transmit data from the frontend to the backend. (GitHub: Team-05/frontend/src/axios.js)
- Created a component withRouter to make the react hook "useNavigate" can be used in any class-based components. (GitHub: Team-05/frontend/src/Components/withRouter.js) 
- Developed the Course Advisor input function. (GitHub: Team-05/frontend/src/Components/AddCourse.js)
- Completed advisorAction (GitHub:  Team-05/frontend/src/actions/advisorAction.js), advisorConstants (GitHub:  Team-05/frontend/src/constants/advisorConstants.js), advisorReducer (GitHub: Team-05/frontend/src/reducers/advisorReducer.js) to make sure users' tokens are always valid while using the Course Advisor function.

## Project Documentation
Our documentation tasks were evenly allocated to each team member (except meeting minutes and meeting agendas, which were completed by our scrum master Shuchen). Except our Final (Second) Milestone Plan was finished and submitted by me. I was being part of the following deliverables:
- Pitch Presentation
- Business Case & Draft Plan
- Milestone 1 Report
- Testing Plan
- Poster
- Testing Report

# Project effort
## Total hours
332.5 hours 
## Average hours per week
25.6 hours
