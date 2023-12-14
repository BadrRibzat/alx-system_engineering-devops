
For Example: if you type a path in the browser like www.googl.com a browser is a local program like chrome or firefox is running on your local computer.

when you click on the browser icon the operating system loads the program like chrome or firefox.

It opens a window which is locally hosted on your desktop.

after you enter the website name in the URL and when you hit enter after entering the URL. For Example: www.google.com in the browser it has to translate the URL to the IP address servers communicate with IP address and not a domain name.

that is why the domain name needs to be translated, a DNS or domain name system server is used to translate the IP address to hostname. For Example:

www.google.com is translated to 10.9.8.7 by the DNS server.

The browser searches for the IP address translation in the DNS cache of the browser, if it does not find it in the browser cache then it looks up the operating system and checks the hosts file of the local computer and then the operating system cache , if it does not find it in the operating system cache then it looks up at the ISP or the internet service provider .

When it is able to translate the DNS name to DNS IP your browser knows that it has to send packets to the domain name www.google.com the URL in HTTP cloud.com forward slash home page ca be split into three parts, which is the protocol or schema which is the HTTP protocol a domain name which is cloud.com and a path which is home page  in order to establish a connection between the browser and the remote server first it has to establish a connection with a three-way handshake TCP's three-way handshaking technique is often referred to as since in ACK because there are three messages transmitted by TCP to negotiate and start a TCP session between two computers SIN is for synchronized SYNACK for synchronized acknowledged ACK for acknowledged one the TCP session has been established then, both sides now that the other side exists and are trying to communicate with each other.

The HTTP is sent over the connection that is established with a TCP protocol .

When you type https google.com into your'e browser the first thing that happens is that a domain name server DNS matches https://google.com to an IP address.

then the browser sends an http request to the server, and the server sends back an http response the server is going to take the request that came in, Looks up the domain name it was requested for it and resource that was requested, and the program on the remote website is going to evaluate it.

example like apache Microsoft  inks php the browser begins rendering the html on the page while also requesting any additional resources such as css, javascript, images, etc ...

each subsequent request completes a request response cycle and is rendered in turn by the browser, then once the page is loaded some sites will make further a synchronous requests .

Let us see what happens again:

1-You enter a url into a web browser.

2-The browser looks up the ip address for the domain name via dns

3-The browser sends a http request to the server.

4-The server sends back a http response .

5-The browser begins rendering the html .

6-The browser sends requests for additional objects embedded in html, images, css, javascript and repeat steps 3-5.

Once the page is loaded the browser sends further async requests as needed .
