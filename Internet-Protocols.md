# Internet Protocols

In today's world, we are searching on Google, making friends on Facebook, sharing photos/videos on Instagram/Snapchat, Chating with Friends on Whatsapp, Watching video/Livestream on youtube, etc. Ever wonder whats happen, when you see a live stream? How somebody could send a live stream video to thousands of Fans immediately.

This works when all are connected to some network, mobile data or WiFi. That's where networking and Internet Protocols work along with other layers of Protocols. It was not always that easy to see live stream or video on the Internet. It got evolved to what it is today.

## History

All of the communication in Digital Era of ours started with one landmark research paper, ***A Mathematical Theory of Communication*** by **Claude Elwood Shannon** in 1948. This one paper started the field of *Information Theory*. 

**Information theory** studies the transmission, processing, extraction, and utilization of information. Information is your text/photo/audio/video, Shannon defined Information in more generic nature that we will see later. One of the applications of Information theory covers Information (e.g. text) that needs to be transmitted over an unreliable medium, e.g. Wifi, Mobile Network, LAN, etc., then quantified again to the same information that was transmitted. One another application of Information theory covers Information storage on an unreliable medium like Disk, Optical drive, etc. and retrieval of the same information in a reliable manner. 

Shannon defined information as a resolution of uncertainty, giving it a quantifiable value which represents a stochastic approach to language. In simple terms, sending and retrieving of Information over uncertain medium and getting the same Information. Same Information that can be quantified or verified. Shannon defined his Communication system as followed,

![Shannon Communication System](./images/internet-protocols/shannon-entropy.png)

Shannon's paper defined the following basic elements of communication:
-   An information source/sender that produces a message
-   A transmitter that operates on the message to create a signal,  which can be sent through a channel
-   A channel, which is the medium over which the signal, carrying the information that composes the message, is sent
-   A receiver, which transforms the signal back into the message intended for delivery
-   A destination, which can be a person or a machine, for whom or which the message is intended

Shannon proposed a mathematical theory of digital communication in his paper *A Mathematical Theory of Communication*. Shannon mathematically proves the possibility of Digital systems in 1948. That's why he sometimes called as *The Father of The Information Age*. Because of Shannon, we have all the modern communication devices working on digital systems. Shannon work was not only applied to Computer Science but also to Cryptology, Linguistics, Physiology, Physics, etc.

There is some criticism of Shannon Model of Communication,
- It didn't consider the semantics of Information passed
- It mimics only one-to-one communication not group or mass communication
- Reciever plays a passive role in communication. Sender actively passing the information to the passive receiver. That don't happen in a real-world scenario.
- It considers the continuous system as an extension to discrete and discrete on top of Binary data (dot and dash of telegraphy).

Despite its criticism, Shannon paper along with Transistors invention in 1947 changed the course of history and brought Digital Era that we are experiencing on daily basis. 

Transistors introduced second generation computer. If you remember from our [Prologue

Computer to Computer Communication was always key for Defense that's why one of the early Computer Network, ARPANET was build by Advanced Research Projects Agency (ARPA) of the United States Department of Defense. ARPA is now known as DARPA. ARPANET was early implementation of **TCP/IP stack** also known as Internet protocol suite. TCP/IP is now standard for Internet Communication. 

There were few other network stacks and Models came along and some tried to standardised the Networking stack like OSI Model. However, TCP/IP got actual implementation in US defense institutes and universities that it never became obsolute. 

## Internet protocol suite

### Why there are 4 layers?



## References
A Mathematical Theory of Communication By C. E. SHANNON [http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf](http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstMjc5MTA5Nzg1LDc0MTUxNTk1
MywtMTU0ODA1Njc2NCwtMzg2MjcxNzY3LDQ4ODY0MDMxNCw4Nz
kyMjk5OTIsNzU3MjI3MDQyLC0xNzQ0OTQyMjI2LDUyMDI2NTQ1
MywxODM0NTQzMTgyLC0xMzE1MzY1NTgxLDgxOTA3MDYxNCwtMT
AxNjQ1Nzc1MSwxOTcwNDU5MTgsODQxMTU3MDk3LDE1OTk5OTI0
MDYsODg2MzQ0NTY5LDkzMTY4MzEwMywtOTU1MzY5MjY5LDcwOD
QzNjg5N119
-->