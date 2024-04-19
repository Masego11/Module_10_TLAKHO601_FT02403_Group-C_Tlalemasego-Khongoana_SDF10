## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.

[An API is a software with a distinct function that two seperates systems one on the publishing side and one on an accessing side agree to follow. Through APIs website data can be made digestable. for API'S to be utilised we need a server which provides the API, the client which is a seperate program that knows which data is avalable through the API and can manipulate it, and the user who makes the request to the client. An example would be when you press the refresh button on your weather app, the app who is the client requests information from the server through the API which returns the latest info to the app for the user to see.]

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API? 

[APIs provides a way for softwares systems to interact with each other (the interaction is limited to systems), while interface provides a way for end-users to interact with the software at a high level]

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

[In order for an API to be utilised one needs to consider the Request-response cycle. This cycle details the communication between the client and server through the API. For the communication to take place the client needs to make a request, for the request to be valid the client needs to include four things:
1. A unique address in the form a URL, 
2. A method which tells the server what kind of action the client wants to take, ie. GET (which instructs the server to retrieve a resource), POST (which asks the server to create a new resource) and Delete (which asks the server to delete a resource)],
3. Headers which provide meta-information about the request, information such as the type of device a user is using can be found in a type of header called "user-agent".
4. Lastly the body which contains the data the client wants to send to the server. 
A response is then sent back to the client by the server after receieving a request with a similar structure but instead of a method and url it includes a status code, which are three digit numbers that each have a unique meaning-the outcome of the request.
We have four types of APIs mainly:  
1. Internal- which are meant to control systems housed within one organisation,
2. External - also referred to as open APIs which are accessible to the public and can be accessed by third parties.
3. Partner- which allow one organization to link their data only to approved third parties. 
4. Composite- which accomodate the use of additional APIs on the same call to improve server speed or link seperate but related APIs into a single process. 
I find the composite API intriguing for it's unique ability to function alongside other APIs which aims to improve server functionally. 

4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

[N/A]

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

[Considering the key concepts I will be spending more time learning more about APIs, how can I can utilise them in coding excercises, from the resources provided and other available resources online.]