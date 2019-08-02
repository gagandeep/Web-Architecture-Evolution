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

Shannon proposed a mathematical theory of digital communication in his paper *A Mathematical Theory of Communication*. Shannon mathematically proves the possibility of Digital systems in 1948. That's why he sometimes called as *The Father of The Information Age*. Because of Shannon, we have all the modern communication devices working on digital systems. Shannon work was not only applied to Computer Science but also Cryptology, Linguistics, Physiology, Physics, etc.

There is some criticism of Shannon Model of Communication,
- It didn't consider the semantics of Information passed
- It mimics only one-to-one communication not group or mass communication
- Reciever plays a passive role in communication. Sender actively passing the information to the passive receiver. That don't happen in a real-world scenario.
- It considers the continuous system as an extension to discrete and discrete on top of Binary data (dot and dash of telegraphy).

Despite its criticism, Shannon paper along with Transistors invention in 1947 changed the course of history and brought the Digital Era that we are experiencing daily. 

Transistors introduced a second-generation computer. If you remember from our [Prologue](Prologue.md), computing devices were primarily used for computations at a central location. With **Integrated Circuit** (IC) breakthrough in the late 1950s and advancement of IC technology with increasing computing power through the 1960s, It was the advent of other possibilities.

Computer to Computer Communication was always key for Defense that's why it was the next step with the increasing power of ICs. One of the early Computer Network, ARPANET was built by Advanced Research Projects Agency (ARPA) of the United States Department of Defense. ARPA is now known as DARPA. ARPANET was an early implementation of **TCP/IP protocol suite** also known as Internet protocol suite. TCP/IP is now standard for Internet Communication. 

There were few other network stacks and Models came along and some tried to standardized the Networking stack like OSI Model. However, TCP/IP got practical implementation in US defense institutes and universities. This led to widespread TCP/IP in the early era of networking, because of that TCP/IP never became obsolete.

## Internet protocol suite

Internet protocol suite also commonly known as TCP/IP protocol suite because of its two foundational protocols namely Transmission Control Protocol (TCP) and the Internet Protocol (IP). There are four layers of Protocols in TCP/IP suite that work at different layers for different purpose. Layers are kind of grouping that define what group protocols do in generic sense. There are no true layer definition that TCP/IP suite enforce, there are protocols that spill over to different layers.

### Layers of Internet Protocol Suite

The four layers of Internet Protocol Suite are, 

#### Link Layer


#### Internet Layer


#### Transport Layer


#### Application Layer


### Why are there four layers?


## Different Protocols of TCP/IP stack



### Link Layer Protocols

#### PPP

### Internet Layer Protocols


### Transport Layer Protocols


### Application Layer Protocols




## References
A Mathematical Theory of Communication By C. E. SHANNON [http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf](http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)

<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstMTI5NzM2NTA5OCwtMTc3MjM0
MDY2LDEwMTI4Nzg5NDIsLTExNTc5MTg0MDUsLTE0Mzc0NzkyNz
IsMTcyNDYwODEzNiwtMTExMjA5MTM5OCw3NDE1MTU5NTMsLTE1
NDgwNTY3NjQsLTM4NjI3MTc2Nyw0ODg2NDAzMTQsODc5MjI5OT
kyLDc1NzIyNzA0MiwtMTc0NDk0MjIyNiw1MjAyNjU0NTMsMTgz
NDU0MzE4MiwtMTMxNTM2NTU4MSw4MTkwNzA2MTQsLTEwMTY0NT
c3NTEsMTk3MDQ1OTE4XX0=
-->