Jenkins Setup:

1. Install JDK 11 and create environment variables
2. Install Jenkins from jenkins.io
3. After installing both the tools, refer below link to follow step-by-step installation
	https://www.jenkins.io/doc/book/installing/windows/
4. Once installation and setup is done, log into the UI using credentials you have selected

P.S. java -jar jenkins.war - command to start jenkins job on your local machine if you are using jenkins war file

Creating free style job:

1. Click on new item on jenkins dashboard
2. Enter an item name ex. Hello-World (avoid using name with spaces which may trouble in future)
3. Select freestyle project and proceed
4. go to add step section and select shell script
5. enter echo "Hello World", click apply and then save button. Project page will appear
6. In left panel, click on "Build Now" button which will run a job 
7. The result of job will appear in build history section in left panel
