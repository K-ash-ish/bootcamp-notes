# Java Bootcamp Notes

>An application always follows a three-tier architecture.

 | Frontend        | Backend  (Mid tier) | Database  |
------------- |:-------------:| -----:|

---
## Basic Architecture
 **CDN** <---(Initial Page Load)---**Browser** ---- (REST API's )--->**Backend Services** ---> **Database**.
 
 1. First, the browser calls the static page elements via **CDN**.
 2. **CDN** returns the static elements **Browser** Loads them.
 3. Then the ``Javascript`` loaded makes the call via **API** to backend services.
 4. If needed **Backend** calls to the DB and returns the expected response.



