**Summary:**  
A Simple Hello,World! Jersey2 webapp configured over https  

**Installation:** mvn clean install  
**access api:** https://localhost:8444/webapi/myresource  
**note:** set tomcat port to 8444  
**tomcat ssl configuration:** https://flicsdb.wordpress.com/2016/08/15/httpsssl-configure-tomcat-8/  
inorder to disable the https on the app, set the transport-guarantee  to "NONE" in web.xml  

`<user-data-constraint>  
<transport-guarantee>CONFIDENTIAL</transport-guarantee>  
 </user-data-constraint>`  
 


