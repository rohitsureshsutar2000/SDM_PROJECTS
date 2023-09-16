**Title: Syestem Requirement Specification for Online Assessement Portal for CDAC.

**Team:Euductional Institute, Students, Architect,Business Analyst, Quality Assurance Team, System Analyst.

**Objective(Purpose) :
The online Assessement Portal evalution based web application s intened to provide complete solution for Eductional institute,
recuritment drive organisation and Students through single portal. It will enable institute and faculty members to asses students
based on there performence in their respective selected fields.


**Scope:
This portal allows faculty members to conduct and evaluate exam for students for respective modules.
Students will be able to review their exam as the evalution by faculty are comleted and can raise there 
concerns regarding different issues regarding evalution if present their.


**Functional Requirments:

Faculty members will have administor login which allows them to upload question paper for the different modules
as per each student opted course. the students will have their auto generated unique id login which will be generated 
at the time of applying for their respectivr course exam. Faculty members will be able to add and remove different courses
and modules related these cousres.

Portal will have automated link generation system for the exam to be conducted and this link will be provided to the students
2 hrs before the exam start. The portal will have access to camera and microphone and motion capturing feature which will monitor the sudent and allow for
smooth process of cheating free exam condution.

The portal will have timer available throughout the exam process. During any technical difficulty thee students can contact the technical team
for the solution of the problem.

The portal will have automated assesment and ranking system which will check the students paper 
and evaluate them based on the answerkey provided the faculty member during question paper uploading process.
It will also provide automated ranking based on different module for different courses respectively.
This evalution will only be visible to the faculty members only and will be visible to the students
only on the date of result anouncement which will be provided by the administrator team on respective date.
 all of this data will be available to the head of the institute in the form of garph or chart which is based on the 
sudent pass and fail data in different modules of different courses.

**Non Functional Requirment:

**Security:

Only student who have unique ID and Password will be allowed to give exam.It will be dual verification process in
which they will be provided will unique exam link 30 minutes before the start of exam and after that when they visit the
through the provided link they will be asked to reverify themselves by entering their unique ID and password.
In case of them forgetting password and ID they have forget password option which
will send a mail to their respective registered email ID which consist of link to reset password.
The faculty members will have seprate administrator login for the portal which will have centralised login through
centre based or specified system only.


**Reliability:

If system or any technical failure occurs during the process of exam the server will still have 
all the data backup which is restored and the exam can be resumed from the same time the failure occured.
The portal will backup the students data and faculty data on regular basis.
During exam hours system will maintain its functional proces by managing load balacning .

**Availability:

Server availability 24*7.

**Maintainbility:

A Commercial database software will be used to maintain System data Persistence. IT operations team will easily monitor and configure System using Adminstrative tools provided by Servers. Separate enviornment will be maintained for system for isolation in production, testing, and development.

**Efficiency:

On the time of exam every student will have same response time without any delay and load will be distributed on multiple server.

**Scalability:

System will provide same and versatile exprience to students as well as faculty members.

**Accessibility:

No annonymous person other students and administrator can access the portal. The authentication must be done by checking unique ID and PASSWORD. Students can access their results, and faculty members can analyse students growth 

**Portability:

Web Application System will provide portable User Interface ( HTML, CSS, JS) through users will be able to access online assessment portal. System can be deployed to single server, multi server, to any OS, Cloud (Azure or AWS or GCP).

**Durability:

System will retain users ongoing exam for 5 minutes even though user loose internet connection and join again. User will be able to view their assessment report or marks whenever needed. System will implement backup and recovery for retaining all the users and administrator data over time.

**Modularity:

System will be designed and developed using reusable, independent or dependent different online assessment portal in the form of modules. These modules will be loosely coupled and highly cohesive. System will contain Notification option, result, assessment report, feedback system, query system , administrator specific module, faculty specific module.

**Safety:

online assessment portal will be secure from malicious attack, fishing. online assessment portal functionalilites are protected from outside with proper firewall configuration. online assessment portal will be always kept updated with latest anit virus software. Assessment data will be backed up periodically to ensure safty of data using increamental back up strategy.
