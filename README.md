# GIUP- A JOB HOSTING PLATFORM APPLICATION

## Overview
GIUP is a web application designed to connect employers with individuals seeking temporary work in the hospitality and event industry. Using ReactJS for front-end, Node.js for back-end, and MongoDB as database management, our platform connects businesses in this sector with skilled temporary workers, offering seamless account authentication, application tracking and job management with an interactive design.

The Name 'GIUP': in Vietnamese, 'giúp' means help, and that is the spirit of the app, is to assist business to find staff and worker to find work.

Similar to: Seek (job hosting) and Uber (operating system)


## Business Use Case
Why focus on temporary/ contract work? 

• The seasonal demand: Temporary job searches within the hospitality and event industry offer flexibility for both employers and employees to accommodate fluctuations in demand during seasons, holidays, and events. 

• Flexibility and cost-effectiveness: The platform offers businesses the ability to adjust staffing levels without long-term commitments, saving costs associated with full-time employment.

• Skills access: Temporary workers provide access to diverse skill sets, enabling hospitality establishments to meet specific needs during peak periods.

## Benefit
### For employer:
• Staff Quality: Large and diverse pool of candidates, allowing businesses to find the right talent more efficiently.

• Cost-Effective Recruitment: Posting jobs on platforms can be more cost-effective than traditional methods like advertising in newspapers or using recruitment agencies.

• Time Savings: The process of posting jobs, screening candidates, and managing applications can be omitted through these platforms, saving time for HR departments.

• Targeted Recruitment: Reach relevant candidates based on criteria like location, experience, and skills.

• Brand Visibility: Enhance a company's visibility and reputation as an employer, attracting top talent.

• Data Insights: Data insights that can help businesses understand trends in the job market and optimize their recruitment strategies.

### For employee:  
• Flexibility: Flexibility in terms of scheduling and work arrangements, allowing balance work with other commitments.

• Skill Development: Workers can develop new abilities, refine existing skills, and gain valuable experience through different areas in the industry.

• Time Savings: Reducing the time spent searching for employment and providing a more immediate source of income.

• More Job Opportunities: Wide range of temporary or contract work opportunities, allowing workers to gain diverse experiences and skills.

• Networking Opportunities: Connect with professionals in their field, potentially leading to future job opportunities or career advancement.

• Competitive Pay: Contract work can offer higher hourly rates or project-based pay compared to traditional full-time employment.


## Features

### Employer Features

1. **User Registration and Authentication:**
   - Employers can securely register and authenticate their accounts.

2. **Job Posting:**
   - Employers can post temporary/contract job listings with details such as title, description, location, duration, required skills, and compensation. 

3. **Applicant Tracking:**
   - Admin Access for employers to track and manage job applicants efficiently- accept/reject applicants

4. **Job Management:**
   - Employers can edit (open/close job status), or delete job postings

### Job Seeker Features

1. **User Registration and Authentication:**
   - Job seekers can securely register and authenticate their accounts.

2. **Job Search:**
   - Job seekers can search for temporary/contract job listings based on various criteria.

3. **Application Submission:**
   - Job seekers can submit applications for desired positions.

4. **Application Tracking:**
   - Job seekers can track the status of their applications (pending/rejected/accepted).


### Flow
Admin:
Sign Up -> Log In -> Post Job -> Accept/Reject Applicants (Reject/Accept)-> Close The Job -> Rate Employee -> Pay the app 

User:
Sign Up -> Log In -> Apply Job -> Work if got accepted -> Rate Employer -> Get payment from the app

## Non-Functional Requirements

1. **Security:**
   - Generate token after logged in to check if the user is logged in on certain pages
   - Username is saved in local storage when logged in to authorize user for certain tasks

2. **Performance:**
   - Optimize platform performance for fast loading times
   - Optimize for small/ large screen size
   - Intuitive and user-friendly interface

## Technical Requirements

1. **Technology Stack:**
   - Frontend: React.js
   - Backend: Node.js

2. **Hosting and Infrastructure:**
   - Not yet implemented

3. **API Integration:**
   - mock-up user data: https://jsonplaceholder.typicode.com/users
   - internal API

4. **Libraries:**
   - Back End: Axios (fetch data), Mongoose (MongoDB object modeling tool), cors (cross origin request), jsonwebtoken (generate token for authentication)

   - Front End: material UI, framer-motion (animations), react-fast-marquee (review marquee), react-router-dom (routes), react-type-animation (animated sentence)


## Data
   - Database: MongoDB
User: username, password, emailId
Job: title, description, payRate, location, time, company, status: open/close
Application: jobId, applicant with status: pending/accepted/rejected



## Future Implementation
 - Notification system 
 - Profile management
 - oauth (fb, google)
 - messaging feature (communication between employer and applicants)
 - Rating system (after the job finished)
 - payment plans 
 - update security 
 - filtering system for job (by date, by rate,...)


## Conclusion

The Job Hosting Platform GIUP aims to provide a comprehensive solution for temporary/contract work, meeting the needs of both employers and job seekers. By implementing the specified features and adhering to the outlined requirements, the platform offers a seamless and efficient experience for job posting, applicant tracking, and the hiring processes.

## DEMO
### Landing Page


https://github.com/giahp/giup_jobsearch/assets/139728559/19114a70-8ab9-4a85-9a66-87cb9bb581a0



### Applicant Flow


https://github.com/giahp/giup_jobsearch/assets/139728559/509a93d6-7b8e-420b-afd5-eb44bcd73c2d



### Employer Flow


https://github.com/giahp/giup_jobsearch/assets/139728559/616be6e4-9807-4e88-b128-31a1fceb5a66







