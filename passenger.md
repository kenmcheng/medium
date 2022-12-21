# Pre/Post Callback Routines With Action Pipeline APIs

## Intro
As modern applications have been more and more complicated, the growing need for web services challenges software developers to work in a scalable yet efficient fashion. Disseminating the gigantic code base into pieces of modules, named Service Oriented Architecture(SOA), started to become a mainstream design because its ease of maintenance and cooperative nature. As our team adopted SOA for the app development, web actions triggered by users, such as browsing websites, logging accounts and submitting forms, are handled through multiple remote processes via remote procedure calls(RPCs), which is also where some issues come in. In this scenario, the terminal service didn't know what exactly the client needs, so the client had to send multiple RPCs to exactly the same remote service to get all required information when, especially, the table regarding the data has foreign relationships. Therefore, the performance of our web application suffered. Here, we want to bring some ideas that help us to bring down the times of RPCs and reduce the response time by about 20%.

## Passenger

## The Tradeoffs