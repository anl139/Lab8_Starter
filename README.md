# Lab8-Starter
1.How are graceful degradation and service workers related?
Service workers allows us to be able to use our website by allowing us to use it when the user suddenly is offline and caching data in which when the network features are set to offine or are slow(represented by slow wifi) it would allow the website to continue operation. Being that when the network is stable it will cache through the network but when network request fails or user is offine the service worker will provide data that was stored previously to ensure that the website doesnt suddenly crash due to lack of data. With this it relates to graceful degradation in that we start with the network being able to cache our data and generate it so the user can access it, but when addressing lower issues such as not internet access degrading our features toward basic functionality when needed(aka when a lack of resources are given).

https://anl139.github.io/Lab8_Starter/ 
![alt text](pwa.png)