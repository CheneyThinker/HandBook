- **javac -cp .:lib/\*.jar:\*.jar: Application.java**
- **javac -Xlint:deprecation -cp .:lib/\*.jar:\*.jar: Application.java**
- **java -cp .:lib/\*.jar:\*.jar: Application**

- **Created File(MANIFEST.MF)**
	- context:
		- Manivest-Version: 1.0
		- Class-Path: *.jar
		- Created-By: Cheseny
		- Main-Class: Application

- **jar -cfm Application.jar MANIFEST.MF \*.class**
- **java -jar Application.jar**
