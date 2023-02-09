# Java Bootcamp Notes

An application always follows a three-tier architecture.

 | Frontend        | Backend  (Mid tier) | Database  |
------------- |:-------------:| -----:|

---
## Basic Architecture
 **CDN** <---(Initial Page Load)---**Browser** ---- (REST API's )--->**Backend Services** ---> **Database**.
 
 1. First, the browser calls the static page elements via **CDN**.
 2. **CDN** returns the static elements **Browser** Loads them.
 3. Then the ``Javascript`` loaded makes the call via **API** to backend services.
 4. If needed **Backend** calls to the DB and returns the expected response.

## CDN Content Delivery Network
Distributed servers that deliver web content to users based on their Geographical Location.

## WEB Request
The Browser sends a request to the DNS server. DNS returns the IP of the closest CDN edge server. The browser then req to CDN edge Server and CDN returns the requested data if available in the cache of the edge server or else the req goes to the origin server.


