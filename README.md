# Resume Filter App
A simple javascript resume template that can filter words and view resumes of multiple employees or candidates.


You are working as a front end developer in an organization and the organization has job openings in various departments. The organization has also received various applications for these positions and the data is available in JSON format. Use the data shared along with this problem statement. You, as a front end engineer, should develop a single User interface where you can see the details shared by the candidates or the applicants. Below are the detailed requirements which you have to achieve as a first version of the web page design.

## In Login Page: 
1.Store the username and password in local storage
2.Create a simple login page
3.Validate the username and password. If successful, direct the user to Resume Page
4.Once the user is in the Resume page restrict the user from going back to the login page. (When clicked on the back button in the browser, restrict the user from going back to the login page).
5.If the user has entered invalid credentials, print invalid username/password.

## In Resume Page:
1.Each applicant's details should be fetched from the JSON file and displayed in the web page.
2.When clicked on Next or Previous Buttons in the web page, the next or previous applicant details should be displayed irrespective of the job they applied for.
3.The web application should also have filtering capability where when searched for a particular job, only applications of that job openings should be displayed.
4.In case if there is one application when searched for a job opening, the left and right buttons should not be seen. If the shown application is the first application, then previous buttons should be hidden and vice-versa.
5.If there are no job openings for the searched value, then print “Invalid search or No applications for this job”.


## Samples
<img width="625" alt="image" src="https://github.com/CodeMuscle/resume-filter-app/assets/83324110/51daa9e5-e552-4e6b-b54f-1dae587129e9">

<img width="360" alt="image" src="https://github.com/CodeMuscle/resume-filter-app/assets/83324110/c8f26178-950c-4221-804d-cedbe5bd64e0">

<img width="506" alt="image" src="https://github.com/CodeMuscle/resume-filter-app/assets/83324110/22a80332-e830-4c35-b350-b39d6139923c">
