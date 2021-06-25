# IST146_Module08_CP

For the course project, you will finish a simple weather application that accesses the National Oceanic and Atmospheric Administration (NOAA) Climate Data Online (CDO) site to get all of the recorded high temperatures for a specified month, in any US county.

## Instructions

1. Log on to your replit account. 
2. Click the "+ New repl" button to create a new repl. 
3. Click on the "Import from GitHub" tab. 
4. Type or paste the following URL into the "Paste any repository URL" text field: `github.com/mmeysenburg/IST146_Module08_CP`
5. Click on the "Import from github" button.
6. Click the "Done" button in the ".replit" dialog that appears.
7. THIS IS DIFFERENT: in the terminal area, execute this command: `mv replit .replit`. Executing this will set the classpath to allow the program to read a JSON file.
8. Code the `WeatherModel` class, as an implementation of `WeatherModelTemplate`. 
9. At any time you can run the code from the user's perspective, or, from a developer's point of view, execute the unit tests that have been provided.
  * To run the code, click the "Run" button.
  * To execute the unit tests (if any), enter the following command in the "Console" tab: `bash test.sh`
10. Once you have completed the code correctly, the unit tests (if any) should pass, and running the code should produce results that make sense.
11. When you are finished, submit your `WeatherModel.java` file via the Canvas assignment.

## Files in the repository

* `counties.csv`: CSV data to derive states, counties, and FIPS values from.
* `Main.java`: Main program to run the code from a user's perspective. This file's `main()` method is invoked when you click the "Run" button.
* `NOAAReader.java`: Class with static methods to query the NOAA CDO site in order to fetch temperature data.
* `WeatherController.java`: Controller for the application.
* `WeatherModel.java`: This file doesn't exist! You mush write this class, implementing WeatherModelTemplate
* `WeatherModelTemplate.java`: Interface describing the methods the WeatherModel must have.
* `WeatherModelTest.java`: JUnit tests for the WeatherModel class.
* `WeatherView.java`: Console-based UI for the application.
* `sample.json`: Sample of the JSON data that is returned by the NOAA CDO site.
* `README.md`: This README file.
* `test.sh`: Bash script to execute the JUnit4 unit tests in WeatherModelTest.java
* `LICENSE`: GNU General Public License v3.0 for these materials.
* `jars`: Directory containing JSON libraries.
* `replit`: File with code to enable the Run button in this project.
