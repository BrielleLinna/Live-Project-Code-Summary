LIVE PROJECT INTERNSHIP OVERVIEW 

PROJECT OVERVIEW:
For 2 weeks I was able to collaberate with a team of developers and a project manager to work on an exisitng and live local website.  This website was made using a ASP.NET MVC Entity Framework. This website's purpose is to be a Content Managing Service to help easily manage what displays, manage login capability for subscription users, and to maintain a wiki of past performers and performances. Below is a description of some front and back end stories that I got to work on during this sprint.

FRONT STORY:
-Donor List Dropdown/ Link to Nav Bar

Adding Donor List Dropdown/ Link Dropdown/ Link to Nav Bar
This story required me to add in a new NavBar section for the currently existing page, Donor List.  The purpose of this was to allow the admin or back end user of this functioning website a quick link to a list of Donors using the NavBar only seen by the admin user.

 ![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story1-code.PNG?raw=true)
 
 Navbar Before:
 ![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Before-admin_donorlist.PNG?raw=true)
 
 Navbar After:
 ![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/After-admin_donorlist_nav.PNG?raw=true)
 
 BACK END STORY:
 Create Survey Model and CRUD (

This story required me to build a new SurveyModel, and then a secondary RentalSurvey model which was to extend from the SurveyModel. I needed to create a table-per-hierarchy table for the Survey model. Additionally,  I needed to create a 1-1 relationship between the existing RentalRequest and the new RentalSurvey models and change RentalRequests  Survey property to type RentalSurvey. Lastly, I needed to create a SurveyController that generated CRUD view pages.

Here is an example of the image provided as a launching point:

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story104.png?raw=true)

Create new Survey Model and define properties

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story107.PNG?raw=true)

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story109.PNG?raw=true)

Create a TPH relationship with Rebtal Survey and Survey Model

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story111.PNG?raw=true)

Create a 1:1 relationship

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story108.PNG?raw=true)

Make RentalRequest's Survey property of type RentalSurvey

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story106.PNG?raw=true)

Create Survey Controller with CRUD pages.

![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story113.PNG?raw=true)

PROJECT RECAP:
During the course of this 2 week long sprint, I strengthened my knowledge of using an Agil/Scrum methodology and Azure Ops to manage local and master branches.  What I took away the most was how to use existing code that the site was built off of such as HTML, CSS, JavaScript, Ajax, Jquery, Bootstrap, and C# as a starting point for creating new content.  Even when approaching new methods that were put in place to optimize the flow and make the code as efficent as possible, I was able to find many existing resources to pull from and mimick when trying to implicate similar functions.  The most common error I encountered during this course was merge conflicts.  I learned the importance of always pulling most recent master branch commits prior to pushing up your changes to ensure a smooth transaction.  These are all things I am confident I can take my new knowledge of and apply it to my future coding career.

OTHER SKILLS I LEARNED:
- Adding in bootstrap features to replace existing code
- Using CSS to target specific containers and rows
- Writing daily summaries 
- Daily stand up recaps with a dev ops team
- Participation in scrum retrospectives




