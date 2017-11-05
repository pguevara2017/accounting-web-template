# accounting-web-template

How to import using Eclipse/Spring Tool Suite
1. Open Github
2. Go to File menu > Clone repository
3. Set url to https://github.com/pguevara2017/accounting-web-template.git
4. Open to Eclipse/Spring Tool Suite IDE
5. Go to File > Import > Existing Maven import
6. Open application.properties > Input the DB name Ex. test2
*Make you MySQL server is open.
spring.datasource.url=jdbc:mysql://localhost:3306/test2
7. Right click the project > Run As > Maven build...
8. Type in Goals field. spring-boot:run
9. Go to browser and type localhost:8080