# Eazyrecruit
### We as a company are committed towards the advancement of HR Talent Acquisition solutions. Our objective is to make the hiring process easy for employers and help them in acquiring the right talent from the market.
## Project Setup
 - **Pre-requisite**
 	* System Requirements : Ubuntu 18 (4 Core or Greater, 8 GB RAM or Greater)
	* Install [Docker](https://docs.docker.com/engine/install/ubuntu/) 
	* Install [Docker-Compose](https://docs.docker.com/compose/install/)
	
 - **Install Setup**
 	* After clone the project run below command on root directory
		> sh deploy.sh
	* After succesfull setup, All the details such as web url, Admin Username and Admin Password will displayed on the screen					
      
## Language Used
* Python
* HTML
* JS, TS
## Framework Used
* Angular
* Expressjs
## Database
* Mongo
* Redis
## Features
 - **Jobs**
	* Create different jobs
	* Add applicant into a specific job
	* Track different job status
 - **Applicant**
	
	* Create Applicant
	* Upload Resume
		> Resume contains data such as applicant info such as name, email, experience, mobile number,skills, all related information regarding applicant  is parsed by the **ML Text Recognition System**, and  related info is saved on our platform.
 - **Mail Parser**
	> We designed a automated system that parse every resume that is sent to company email id, and the ML algorithms gather information about applicant.
 - **Interview Schedule**
	 >Schedule/Reschedule an applicant interview to a specific interviewer.
 - **Interviews**
	>Track all Pending and Completed interviews,
- **Analytics**
	>Text here
 - **Email Settings**
	* Inbound Settings
		> Configure Imap to fetch  resume from specific email-id
	
	* Outbound Settings
		> Configure smtp to send email
	
	* Email template Preview
		> Preview and configure the email template that is sent to the applicant.
- **Public Job Portal**
	* Branding
		>Company details such logo,name , website can easily be customised
	
	* Publish Job Listing
		>All the publish job will be listed here
	
	* Job Apply
		>Candidate can apply job into a specific job
	
	* Social Sharing
		>Share jobs on various social platforms such as **Linkedin**, **Twitter**, **Facebook**.
