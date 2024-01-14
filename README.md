# simple-crud-for-spring-jdbctemplate
This is the example code respository for the medium.com article on the [Simple CRUD for Spring JdbcTemplate](https://medium.com/@ajosephmi/simple-crud-for-spring-jdbctemplate-8347211d5306).

Github project for [JdbcTemplateMapper](https://github.com/jdbctemplatemapper/jdbctemplatemapper) library used in the examples.

The main code is in class [TutorialTest.java](src/test/java/io/github/ajoseph88/jdbctemplatemapper/test/TutorialTest.java).
The example code are tests that go against a MySQL database. On your MySQL instance you will need to create a database named 'tutorial'. Make appropriate changes to [application.properties](src/test/resources/application.properties) file so you can connect to your database. The tables needed for the tests are created automatically when the tests are run so no need to manually create them. To see how JdbcTemplateMapper is configured take a look at file [JdbcTemplateMapperConfig.java](src/test/java/io/github/ajoseph88/jdbctemplatemapper/config/JdbcTemplateMapperConfig.java)


You can run the example code from the command line with:

```
mvn clean package
```

You should see all the SQL being issued on the console.





