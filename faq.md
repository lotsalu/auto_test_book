** Q:浏览器不能打开html问题**
**A:**
To workaround in firefox:Go to page about:config ;Set security.csp.enable = false
For resolve your problem you must :
Connect on your jenkins url \(http:\/\/\[IP\]:8080\/\)
Click on administer Jenkins
Click on consol jenkins
Copy this into the field and execute :
System.setProperty\("hudson.model.DirectoryBrowserSupport.CSP","sandbox allow-scripts; default-src 'none'; img-src 'self' data: ; style-src 'self' 'unsafe-inline' data: ; script-src 'self' 'unsafe-inline' 'unsafe-eval' ;"\)

