# Communicating on the web 
WhatsApp would be preety terrible if we have to manually copy our photos to our friend's phone when we wanted to share them. Modern  applications need to be able to communicate information between devices over the internet.
* Gmail doesn't just store your emails in variables on your computer, it stores them on computers in their data centers
* You don't lose your Facebook messages if you drop your computer in a lake, those messages exist on Facebook's servers

## How does web communication work?
When two computers communicate with each other, they need to use the same rules. An English speaker can't communicate verbally with a Korean speaker, similarly, two computers need to speak the same language to communicate.

This "language" that computers use is called a protocol. The most popular protocol for web communication is HTTP, which stands for Hypertext Transfer Protocol.

## Web-communication Code explanation
I wrote the `getItemData()` function for you. It retrieves items from Fantasy Quest's servers via HTTP.

I also wrote a `logItems()` function for you, call it with the `items` variable we are getting back from the `getItemData()` as a parameter.

