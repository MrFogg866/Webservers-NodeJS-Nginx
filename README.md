## Webservers - NodeJS - NGINX


### How do Webservers work?

- When a user specifies a URL in the browser address bar, the web browser will then obtain the IP Adrress of the domain name through DNS (Domain Name System).
- This then goes gives access to the Web server, the browser requests the specific file from the web server by HTTP request
- The web server then responds, sending the browser the requested page through HTTP

# How does NODEJS work?

- Node.JS it is not a web server and it runs on the VB JavaScript Engine
- Nodejs allows us to have multiple threads (a thread is like a request) on a single CPU
- Node.JS will split the CPU time evenly between the threads



### How does NGINX work?

- NGINX is one of the most reliable servers for speed and scalability
- Used by online giants are Google, Netflix, Adobe, Cloudflare, WordPress.com
- NGINX uses worker connections contained in worker processes the worker process then handles all of the requests of the worker connection, the worker process then send to the master process to receive the results
- One worker connection may take care of unto 1024 requests
- This is why NGINX is the fastest web server




### Use cases of NodeJS

gffg




### What are the dependencies of Nodejs?




### What is NPM?




### What is a Reverse Proxy?