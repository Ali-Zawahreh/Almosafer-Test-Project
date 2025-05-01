# Almosafer Automation Test Project
This project is a Java-based automated test suite using Selenium WebDriver and TestNG, designed to test the functionality of the Almosafer website.

📁 Project Structure
AppTest.java: Contains test cases for language, currency, UI elements, hotel search, and dynamic selection of room configuration.

TestData.java: Holds test data such as expected values and random room configurations.

🚀 Technologies Used
Java

Selenium WebDriver

TestNG

Maven (recommended for dependencies)

ChromeDriver

✅ Features Tested
Language and currency defaults

WhatsApp contact number

Qitaf logo presence

Departure and return flight date checks

Hotel tab availability

Hotel search functionality with dynamic city and room selection

Page content validation post-search

🔧 Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/Ali-Zawahreh/Almosafer-Test-Project.git
cd Almosafer-Test-Project
Install dependencies (if using Maven):

bash
Copy code
mvn clean install
Make sure ChromeDriver is installed and its path is set.

Run the tests with TestNG:

bash
Copy code
mvn test
🧠 Notes
The hotelSearch() test randomly chooses a hotel room configuration.

The language and URL can dynamically switch between Arabic and English.

Room selection is driven by data-testid values.

Tests are disabled by default using enabled = false, except for hotel search and result verification.

📄 License
This project is licensed under the MIT License.
