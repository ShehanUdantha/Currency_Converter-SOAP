# Currency_Converter-SOAP
Create a Soap web service for currency conversion

To Installation

Step 1: Clone the project
git clone https://github.com/ShehanUdantha/Currency_Converter-SOAP.git

Step 2: Open the project in your IDE
Once the project is cloned, open the IDE and locate in to the project clone folder and open WebServer folder.

Step 3: Configure the JDK version
Make sure that the JDK version used by your IDE is set to 1.8.

Step 4: Add the json-simple library to the project
This project uses the json-simple library to parse JSON data. In order to run the project, you will need to download the json-simple-1.1.1.jar file and add it to the project's external libraries.

Step 5: Run the WS java file
Once the project is set up and configured correctly, you can run the WS java file to start the web service. This will start a web server on your local machine and create the WSDL file.
 
Step 6: View the WSDL file
To view the WSDL file, open a web browser and navigate to the following URL:
http://localhost:8888/WebService?wsdl
This will display the WSDL file, which contains information about the web service's methods.

Now Server Side is finished, let move to Client Side

Step 1: Open the project in your IDE
Once the project is cloned, open the IDE and locate in to the project clone folder and open WebClient folder.

Step 2: Install the required Python packages
Before you can run the main.py file, you may need to install some additional Python packages.
pip install zeep
pip install flask
pip install jsonify

Step 3: Run the main.py file
This will start the client application and display a message in the terminal indicating that the server is running.

Step 4: View the client web page
To view the client web page, open a web browser and navigate to the following URL: http://127.0.0.1:5000/

Step 5: Convert currencies
To convert currencies using the client web page, select the currency codes in selectors and enter the amount in the input fields and click the "Convert" button. The web page will display the result of the conversion.
