1. Explanatory Paragraph
A website opens on the screen when a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome and presses Enter. The browser acts as a client, which sends an HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure) request to the web server using the internet. HTTPS is the secure version of HTTP because it encrypts data exchanged between the client and server. The server receives the request, processes it, and, if necessary, communicates with a database to retrieve or store information. The database stores data such as user details, product information, and website content. The server then sends an HTTP response containing resources such as HTML, CSS, JavaScript, and images back to the browser. This process is called the request-response cycle. The browser interprets these resources and displays the website on the screen. A static website displays fixed content that usually remains the same for every visitor unless its files are changed, whereas a dynamic website can generate or update content based on user input, database information, or other conditions. For example, a simple portfolio website is often static, while an online shopping website is dynamic because it displays products, user accounts, and changing order information.

2. Important Terms
Browser: Software used to access and display websites, such as Google Chrome.
Client: The device or application that sends requests to a server.
Server: A computer or software system that processes requests and sends responses.
Database: An organized collection of data that can be stored, retrieved, and updated.
HTTP: Hypertext Transfer Protocol, used for communication between a browser and a web server.
HTTPS: Hypertext Transfer Protocol Secure, which protects communication through encryption.
Request-response cycle: The process in which a client sends a request and the server returns a response.
3. Static Website vs. Dynamic Website

Static Website	Dynamic Website
Displays mostly fixed content.	Content can change according to user input or data.
Usually serves pre-written files.	May generate pages using server-side code and databases.
Often simpler to develop and host.	Often requires more complex programming and infrastructure.
Example: A basic HTML portfolio.	Example: An online shopping website.
4. Chrome DevTools — Network Tab
Steps to inspect website requests:

Open Google Chrome and visit https://example.com.
Right-click anywhere on the webpage and select Inspect, or press Ctrl + Shift + I on Windows.
Select the Network tab in DevTools.
Reload the webpage using Ctrl + R.
Observe the list of network requests, including document, CSS, JavaScript, and image requests where applicable.
Click a request and inspect its Headers, Preview, Response, and Timing tabs.
Take a screenshot showing the webpage's network requests and save it as network-tab.png.
5. Screenshot Submission
Insert your own screenshot of Chrome DevTools' Network tab here after completing the steps above.

Screenshot file: network-tab.png

Observation: The Network tab shows the resources requested by the browser, their HTTP status codes, request types, transfer sizes, and loading times. These details help us understand how the browser communicates with the server and loads a website.

Conclusion
A website works through communication between a client and a server using HTTP or HTTPS. The server may retrieve information from a database before sending a response, and the browser processes the returned resources to display the website. Chrome DevTools helps us observe this process through the Network tab.
