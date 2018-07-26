# Django-Chat

This is a basic web application intended for real time chatting. In this, channnels are being used to implement the same. Along with this, Redis is used as a backing store for storing messages. Redis is being handled through Docker system.

Channels is a project that takes Django and extends its abilities beyond HTTP - to handle WebSockets, chat protocols, IoT protocols, and more.

It does this by taking the core of Django and layering a fully asynchronous layer underneath, running Django itself in a synchronous mode but handling connections and sockets asynchronously, and giving you the choice to write in either style.
