# spring-multi-project
testing for pushing sub-modules
This is a test project which contains sub projects from different public repositories, This project is made for testing to push sub-modules in the github through git.

If you also want to do that , follow below steps :

#cd to_your_project
#git init
#git add .
#git status
Then you will see something like this :

On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   Spring3Example/.classpath
	new file:   Spring3Example/.project
	new file:   Spring3Example/pom.xml
	new file:   Spring3Example/src/main/java/com/mkyong/core/App.java
	new file:   Spring3Example/src/main/java/com/mkyong/core/HelloWorld.java
	new file:   Spring3Example/src/main/resources/SpringBeans.xml
	new file:   Spring3Example/src/test/java/com/mkyong/core/AppTest.java
	new file:   gs-gradle-master/.codesets.json
	new file:   gs-gradle-master/.gitignore
	new file:   gs-gradle-master/.travis.yml
	new file:   gs-gradle-master/LICENSE.code.txt
	new file:   gs-gradle-master/LICENSE.writing.txt
	new file:   gs-gradle-master/README.adoc
	new file:   gs-gradle-master/complete/build.gradle
	new file:   gs-gradle-master/complete/gradle/wrapper/gradle-wrapper.jar
	new file:   gs-gradle-master/complete/gradle/wrapper/gradle-wrapper.properties
	new file:   gs-gradle-master/complete/gradlew
	new file:   gs-gradle-master/complete/gradlew.bat
	new file:   gs-gradle-master/complete/src/main/java/hello/Greeter.java
	new file:   gs-gradle-master/complete/src/main/java/hello/HelloWorld.java
	new file:   gs-gradle-master/initial/.gitignore
	new file:   gs-gradle-master/initial/build.gradle
	new file:   gs-gradle-master/initial/src/main/java/hello/Greeter.java
	new file:   gs-gradle-master/initial/src/main/java/hello/HelloWorld.java
	new file:   gs-gradle-master/test/run.sh
	new file:   gs-rest-service-master/.gitignore
	new file:   gs-rest-service-master/.travis.yml
	new file:   gs-rest-service-master/LICENSE.code.txt
	new file:   gs-rest-service-master/LICENSE.writing.txt
	new file:   gs-rest-service-master/README.adoc
	new file:   gs-rest-service-master/complete/build.gradle
	new file:   gs-rest-service-master/complete/gradle/wrapper/gradle-wrapper.jar
	new file:   gs-rest-service-master/complete/gradle/wrapper/gradle-wrapper.properties
	new file:   gs-rest-service-master/complete/gradlew
	new file:   gs-rest-service-master/complete/gradlew.bat
	new file:   gs-rest-service-master/complete/pom.xml
	new file:   gs-rest-service-master/complete/src/main/java/hello/Application.java
	new file:   gs-rest-service-master/complete/src/main/java/hello/Greeting.java
	new file:   gs-rest-service-master/complete/src/main/java/hello/GreetingController.java
	new file:   gs-rest-service-master/initial/build.gradle
	new file:   gs-rest-service-master/initial/gradle/wrapper/gradle-wrapper.jar
	new file:   gs-rest-service-master/initial/gradle/wrapper/gradle-wrapper.properties
	new file:   gs-rest-service-master/initial/gradlew
	new file:   gs-rest-service-master/initial/gradlew.bat
	new file:   gs-rest-service-master/initial/pom.xml
	new file:   gs-rest-service-master/initial/src/main/java/hello/.gitignore
	new file:   gs-rest-service-master/test/expected.json
	new file:   gs-rest-service-master/test/run.sh


#git commit -m "checking multiple submodules commits"
Now create github repository by login to your account in github.com
#git remote add origin https://github.com/ratnesh93/spring-multi-project.git
#git pull origin master
#git push origin master
