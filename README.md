# FreeJAM
FreeJAM is an open source Flutter application for Job Assigment & Management.
Designed with small businesses in mind. It is aimed to be used to assign jobs to employees and to monitor and manage these jobs.

## Tool Used
- Flutter
- Firebase

## To reproduce the project in your environment
- Create your own firebase project and make sure that package name in firebase app should be same as application id which is in android gradle file.
- Download google-service.json file and paste inside **/android/app** directory.
- Run **flutter pub get** for getting dependencies.


## Features 

(Currently Employer and Employee use the same app. UI separation is managed by user role. Admin field is avaible for Employer only.)

- Admin (for Employer only)
  - Jobs
    * List unassigned jobs
	* Add new job
	* Assing a job to employee
  - Employees
    * List employees by filters
    * Add/Approve new employee

- Home 
  * Jobs pending approval
  * Upcoming jobs

- Job
  * Job Details view
  * Actions Approve, Reject, Complete, Cancel


- Profile 
  * Edit Profile Details
  * Setting avaibility filters
  * Jobs Done





- Backend
  * Database system with Firebase Firestore
  * User management with Firebase Authentication
  
