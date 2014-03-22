- In Eclipse  
    - Install `Spring` IDE by using [Eclipse Marketplace](http://www.mkyong.com/spring/how-to-install-spring-ide-in-eclipse/)  
    - [Install GAE](https://developers.google.com/appengine/docs/java/tools/eclipse)  
- Import this maven project into Eclipse  
- Run on local  
    - Click "Run On Server" and choose "Google -> Goolge App Engine" & "server host name -> local host"  
    - Module instance default is running at [http://localhost:8888/](http://localhost:8888/)
    - The admin console is running at [http://localhost:8888/_ah/admin](http://localhost:8888/_ah/admin)    
- Deploy on GAE  
    - Modify the field `<application>gaemvnspring</application>` with your own `google app ID` in file `src/main/webapp/WEB-INF/appengine-web.xml`  
    - Click "Run As -> 5 Maven build"  
    - Fill in `appengine:update` in the **Goals** field and click **Run**    
    - [http://gaemvnspring.appspot.com/](http://gaemvnspring.appspot.com/)    

- [Reference](https://developers.google.com/appengine/docs/java/tools/eclipse) 

