First : create a self-signed SSL Certificate. Follow steps 1 => steps 5

https://www.akadia.com/services/ssh_test_certificate.html

Second :

Windows + R 
chrome.exe --user-data-dir=/tmp/foo --ignore-certificate-errors --unsafely-treat-insecure-origin-as-secure=https://localhost/

Third : when chrome open go to : 
- http://localhost:8000
- Inspector -> Lighthouse -> Progressive Web App

Then : generate pwa (icon at the right of the url)
