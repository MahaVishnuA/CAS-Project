**Project Name: News Around Cognizant**


# Overview
This project aims to automate the News Section of Cognizant using Selenium WebDriver. The automation process involves navigating through the Be.Cognizant portal, extracting user information, verifying Around Cognizant News section , Get all the News headers in Around Cognizant News Section, and verifying whether News header and Tool Tips of News are same, clicking the See All and validating the news are displayed, clicking the each news header and verifying the news header and tooltip for each news, printing the news details of first five news.



## Libraries and Dependencies
- **Maven Repository:** Maven 3.9.3
- **Apache POI:** 4.1.2
- **TestNG:** 7.9.0
- **Extent Report:** 5.1.1
- **Selenium WebDriver:** 4.16.1


## Automation Flow
1. Navigate to Be.Cognizant portal.
2. Extract user information from the profile.
3. Verify the presence of Around Cognizant news section.
4. Get all the news headers in Around Cognizant news section.
5. Verify the header and the tooltip of the news are same.
6. Click SeeAll link.
7. Check the news are displayed.
8. Get the each news header.
9. Click the each news header and check the tooltip of the each header.
10. Get the news content of the first five news.
11. Print the news details of the first five news.



## Libraries Explanation
- **Maven Repository:** Used for project management and dependency resolution.
- **Apache POI:** Handles Excel operations for data-driven testing.
- **TestNG:** Facilitates test case organization and execution.
- **Extent Report:** Generates comprehensive test reports.
- **Selenium WebDriver:** Automates browser interactions.


## Screenshots
Screenshots are captured at relevant steps for documentation and analysis in the Extents reports documentations.

## How to Run
1. **Open Eclipse IDE:**
   - Launch Eclipse IDE on your machine.

2. **Import Project:**
   - Select `File` -> `Import` from the menu.
   - Choose `Existing Maven Projects` and click `Next`.
   - Browse to the directory where you cloned the repository and select the project.

3. **Update Maven Project:**
   - Right-click on the project in the Project Explorer.
   - Choose `Maven` -> `Update Project`.
   - Click `OK` to update dependencies.

4. **Set Up Configuration:**
   - Open the xml file.
   - Update any configuration parameters like browser type, URLs, etc., as needed.

5. **Run Test Suite:**
   - Locate the test suite file (`Single.xml`)
   - Right-click on the file and choose `Run As` -> `TestNG Suite`.

6. **View Reports:**
   - After execution, open the `Extent_Reports` folder.
   - Find the TestNG file (`My_CAS_Reports.html`) for detailed test case reports.

## Reporting
1. **Locate Test Reports:**
   - After the execution, navigate to the `Extent_Reports` folder in the project directory.

2. **Open Extent Report:**
   - Inside the `Extent_Reports` folder, find the Extent Report HTML file named `My_CAS_Reports.html`.

3. **View Test Reports:**
   - Open the `My_CAS_Reports.html` file using any web browser.
   - This report provides a detailed overview of test executions, including passed and failed tests, test duration, and any exceptions encountered.

4. **Screenshots and Logs:**
   - screenshots captured during test execution and relevant logs for test cases.

5. **Analyze Results:**
   - Utilize the visual representation in the TestNG Report to quickly identify test status and any issues encountered during the test run.

## Contributors
- Maha Vishnu A 	:2318459
- Baradwaj E 		:2318452
- Kumaran Selvaraj 	:2318580
- Praveen A 		:2318578
- Mukilan R 		:2318461

## Known Issues
- **Issue 1: Slow Performance on Large Data Sets**
  - Description: The automation script may experience performance issues when dealing with large data sets in the News Section.
  - Workaround: Consider optimizing the script or running it on a machine with higher processing capabilities.

- **Issue 2: Dynamically changes in the News**
  - Description: The automation script may experience performance issues when dealing the scrolling in the news page and get the headers of the news because of the network connections.
  - Workaround: Consider optimizing the script or running it on a machine with higher network connection capabilities.



## Future Enhancements

- **Enhancement 1: Parallel Execution**
  - Description: Enable parallel execution of tests to improve overall test suite efficiency.
  - Timeline: Investigating implementation feasibility.

- **Enhancement 2: Integration with CI/CD**
  - Description: Integrate the automation script with popular CI/CD platforms for continuous testing.
  - Timeline: Targeting a future release for streamlined workflows.


