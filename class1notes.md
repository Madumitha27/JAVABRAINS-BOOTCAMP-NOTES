Java applications follows 3 tier architecture .
Browser->API/Rest call->Backend server->Database
MICROSERVICES:multiple services are integrated through an API gateway 
CDN-Content Delivery Network : It is a distributed server architecture that delivers contents from original server to the 
edge servers placed in different geographic locations
WEB REQUEST : 
Browser sends request to the DNS server which matches the hostname with the corresponding IP address and return the IP address of the nearest 
edge server .The browser sends request to the nearest edge server . If the edgse server contains the cache it returns the cached version else 
it sends request to the original server to send the required content and stores it in cache and return it to the users.
