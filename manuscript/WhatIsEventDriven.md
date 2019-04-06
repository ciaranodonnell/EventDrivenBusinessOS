## What is Event Driven?
Applications and there architectures are said to be "X Driven" when the X in question is the made mential model used to solve other problems. 

Event Driven systems are therefore systems whereby the primary method for solving problems is through the use of **Events**

### So What's an Event?
Well I'm glad you asked. A Event is generally a thing that happens. Events in the computer systems world are really little packets of information that describe something that has happened. This could be a Single statement, perhaps a JSON document that has fields about what happened exactly, it could be XML, plain text, a binary format, it doesnt really matter. 

What matters here is that there is a blob of data that describes someting that **has happened**. 
Because this thing has already happened, the information about it cant really change, therefore **events are immutable** blobs of data. 