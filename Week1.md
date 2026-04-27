## Learning Burp Suite
- Burp Suite is a java-based framework that is designed to serve as a solution for doing web application penetration testing.
- It captures and enables manipulation of all HTTP/HTTPS traffic between a browser and a web server.

# Features of Burp Community
- Proxy: It allows interception and modification of requests and responses while interacting with web applications.
- Repeaer: This allows you to capture, modify and resend the same request multiple times. Useful for crafting payloads through trial and error or testing the functions of an endpoint for vulnerabilities.
- Intruder: Allows for spraying endpoints with requests. Used for brute-force attacks or fuzzing endpoints.
- Decoder: Offers services for data transformation. It can decode captured information or encode payloads before sending them to the target.
- Comparer: Allows the comparison of two pieces of data at either the word or byte level. The ability to send large data segments directly to a comaprison tool with a single keyboard shortcut significantly accelerates the process.
- Sequencer: Assessing randomness of tokens, such as session cookies values or other supposedly randomly generated data.

## Question and Answers for each task
# Task 1:
Q: Where do experienced AppSec hackers do majority of their testing from?

A: Burp Suite

# Task 2:
Q: Which edition of Burp Suite runs on a server and provides constant scanning for target web apps?
A: Burp Suite Enterprise
Q: Burp Suite is frequently used when attacking web applications and ______ applications.
A: Mobile
Q: What company made BurpSuite?
A: Portswigger
Q: If you want to learn more about application security from PortSwigger, what of their offerings would you use?
A: Web Security Academy

# Task 3:
Q: By default what IP address and port does the Burp Proxy make use of?
A: 127.0.0.1:8080
Q: What is the hotkey to send a request to the Repeater?
A: CTRL + R
Q: What is the hotkey to send a request to the Intruder?
A: CTRL + I
Q: What decoding scheme is pink?
A: binary
Q: When testing for Race conditions you want to effectively send a number of requests at the same time, this is often done using a "Last-byte sync" attack. Where would you send this type of attack in Burpsuite?
In the format Component -> Button -> Option 
A: Repeater -> Send -> Send Group in Parallel

# Task 4:
Q: In which category can you find a reference to a "Cookie jar"?
A: Sessions
Q: In which base category can you find the "Updates" sub-category, which controls the Burp Suite update behaviour?
A: Suite
Q: If we have uploaded Client-Side TLS certificates, can we override these on a per-project basis (yea/nay)?
A: yea

# Task 5:
Q: Where can I see all requests proxied through Burp?
A: HTTP History
Q: What tool allows me to see all the endpoints in an application (that I know of)?
A: Site Map
Q: What functionality do I use to make Burp avoid intercepting or logging requests from a specific domain?
A: Scope
Q: Where can I find some Application Security vulnerability knowledge in Burp?
A: Issues
Q: Is it better to use a the in-built browser or the Burp Browser?
A: Personal Preference

# Task 6:
Q: What attack type cycles through the payloads inserting one payload at a time into each position defined in the request?
A: Sniper
Q: What attack type can be used to test for race conditions?
A: Battering Ram
Q: What is the maximum number of payload sets we can load into Intruder in Pitchfork mode?
A: 20
Q:We have three payload sets. The first set contains 100 lines, the second contains 2 lines, and the third contains 30 lines.
How many requests will Intruder make using these payload sets in a Cluster bomb attack?
A: 6000
Q: Which Payload processing rule could we use to add characters at the end of each payload in the set?
A: Add suffix
Q: What symbol defines the start and the end of a payload position?
A: §
Q: Test out running an intruder attack, when down it start to slow down dramatically (round down to the nearest 10)?
A: 30

# Task 7:
Q: Which sections gives us a more intuitive control over our requests?
A: Inspector
Q: Which section in Inspector is specific to POST requests?
A: Body Parameters
Q: Which option allows us to visualize the page as it would appear in a web browser?
A: Render
Q: Which view will populate when sending a request from the Proxy module to Repeater?
A: Request

# Task 8:
Q: Base64 encode the phrase: Let's Start Simple.
What is the base64 encoded version of this text?
A: TGV0J3MgU3RhcnQgU2ltcGxl
Q:URL Decode this data: %4e%65%78%74%3a%20%44%65%63%6f%64%69%6e%67.
What is the plaintext returned?
A: Next: Decoding
Q: ZW5jb2RpbmcgaXMgdmVyeSBrZXdsCg==
A: encoding is very kewl
Q: What Linux tools allows you to perform base64 encoding and decoding
A: base64
Q: Encode this phrase: Encoding Challenge.
Start with base64 encoding. Take the output of this and convert it into ASCII Hex. Finally, encode the hex string into octal.
What is the final string?
A: 24034214a720270024142d541357471232250253552c1162d1206c
Q: What characters used in base64 encoding are stripped in JWTs?
A: +,=,/

# Task 9:
Q: What similar linux utility exists?
A: diff 

# Task 10:
Q: What does Sequencer allow us to evaluate?
A: Entropy

## Welcome to the end of your first assignment. Well done!
If you enjoyed this task or just want to delve a bit deeper, try out the following exercises:

THM Burp Module (some of these rooms require premium): https://tryhackme.com/module/learn-burp-suite
Pickle Rick CTF - https://tryhackme.com/room/picklerick 
Basic DNS - https://tryhackme.com/room/dnsindetail 
Learn more about HTTP - https://tryhackme.com/room/httpindetail 
Learn more about Websites - https://tryhackme.com/room/howwebsiteswork 
Putting it together - https://tryhackme.com/room/puttingitalltogether 
Want to dive into Race conditions I mentioned? https://tryhackme.com/room/raceconditionsattacks 
Want to try something practical? Play around with the Juice shop for a bit. But don't worry we will cover most of this in the course - https://tryhackme.com/room/owaspjuiceshop 
