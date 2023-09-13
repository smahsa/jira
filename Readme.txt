1. Install Jira and do not run it
2. Stop jira service from task manager
	Copy "atlassian-extras-3.2.jar" to :
        Windows: C:\Program Files\Atlassian\JIRA\atlassian-jira\WEB-INF\lib\
        Linux: /opt/atlassian/jira/atlassian-jira/WEB-INF/lib/

	Copy "atlassian-universal-plugin-manager-plugin-4.0.1.jar" to: 
        Windows: C:\Program Files\Atlassian\JIRA\atlassian-jira\WEB-INF\atlassian-bundled-plugins\
        Linux: /opt/atlassian/jira/atlassian-jira/WEB-INF/atlassian-bundled-plugins/

3- Start Jira service
    In Windows:
	 With task manager
    In Linux:
   	 /etc/init.d/jira start

4. Run jira in Browser: http://localhost:8080
5. Config Database
6. Copy "Jira Software License" Code from license.txt and paste to jira
7. Fisnish config and login with admin user. from setting select "Application"
8. In "Versions and Licenses" Copy and paste "Jira Core License" from License.txt

Note:
Do not update
you can update add-ons except "Universal Plugin Manager"
=================
www.downloadly.ir