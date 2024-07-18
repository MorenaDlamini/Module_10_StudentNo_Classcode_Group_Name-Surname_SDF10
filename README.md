## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.

* An API is like a meesenger that will take your request from a application then tells the back-end system what to do. it then takes the response from the back-end and sends it back to your application so you as the user can see the results.

**Practical Scenario**
In an Uber application there's 5 things that happen in order to get a ride which are *requesting a ride*, *matching with a Driver*, *The driver acceptance and Navigation*, *Ride Progress and Updates*, *Payment and Rating*, *Data Processing*. All of these mentioned steps utilize a API 


2. **Conceptual Distinctions**: How would you differentiate between an interface and an API? 

**Interface:** What you see and interact with directly as a user
**API** This is the behind the scenes technology that enables the application to perform certain operations on your behalf by connecting to the back-end of the system 

**Example**

Interface: within a banking application, the user is able to interact with the application, whether checking your balance, transferring money or playing the lotto.
API: behind this banking application interface, there is a API that connects it to the bank'system. This allows the application to securely retrieve your account information,       process your trasaction. 

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

* The most common methods which are used are:
  'GET', 'POST', 'PUT', 'DELETE' 

* The 'GET' method retrieves data from the API.
* The 'POST' creates new data or submits data to be processed.
* The 'PUT' updates existing data
* The 'DELETE' this will remove the data 

One which we commonly use is the one I mentioned above which is Restful API. This API is widely used in web and mobile applications to interact with the database and services. 


4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs?

**Example**
* Users must test their cap lamp on a lamp room panel.
* The lamp room panel sends a pass/fail message to the data server.
* Based on the pass/fail message, the interface sends a message to the time and attendance system.
* The time and attendance system controls the turnstile based on the message received.

**API Endpoints**

*Lamp Room Panel to Data Server:*

* Endpoint: POST /lamp-test
* Body: user_id, lamp_id, test_result

*Data Server to Time and Attendance System:*

* Endpoint: POST /turnstile-control
* Body: user_id, access_granted

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

* Area where I feel confident would be the HTTP basics which is the common use for communication. 
* Area of improvement would be error handling and authentication and security. 
* I plan on reading up on documentation and diving into API tutorials for more understanding 