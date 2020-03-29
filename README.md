# How does the internet work
I will try to write about how does internet work, what happens when you browse a website and more

<h3>How does my computer at home/office work?</h3>

- First and foremost, your computer needs to be connected to a Local Area Network(LAN) before it could browse on the Internet either via Ethernet or Wireless connection.
- From your LAN or WAN it will go to your Internet Service Provider(ISP). Your ISP is the company that you are paying for internet services.

<h2>IP Addresses</h2>

IP addresses are the mailing addresses for any electronic device which has internet connection. 
Ther are two different standards for IP adrreses: IPv4 and IPv6. IPv4 is an older version and uses only 32 bits, an example to IPv4 address is: 192.168.2.1 IPv6 on the other hand uses 128 bits and it could look like this: 542d:a1ff:3a32:1933:d8bb:9690:1d9d:8cf5


<h2>What happens when you type github.com in your browser</h2>
The moment you press enter - 140.82.114.3 -, your browser will get a 301 response which will return you the domain name of the associarted website. 
Then the browser will act like as if you typed github.com.

The result should be the bones of the website. On the top lines of the HTML, Github includes dns-prefetch links.

>DNS-prefetch is an attempt to resolve domain names before resources get requested. This could be a file loaded later or link target a user tries to follow.

The websites uses this to reduce the latency. Later in the HTML, there will be a request to a 3rd party source. For that request to be sent, browser needs to know the IP address. DNS prefect will help resolving it earlier in load.

Then comes the CSS file(s). 
The requests are made to those addresses and they return the CSS, the styling they need on the page. 

Next is the assets and the JS files which is important for the look of the website as well as some other functions that the page needs.


<h3>What happens if you acctualy type an IP address to your browser?</h3>

<h3>Conversion</h3>

It is important for Partners in the loop to to know about the conversion rate. When an ad is seen, Publisher is going to place a cookie into user's browser. This cookie allow advertiser to track the user's behaviours. 

Advertiser will need to set up the conversion action in their account and they will get a piece of code/tag to add the conversion tag to the website.


<h4>Conversion Window</h4>
This is a time frame for conversion to be considered successful. If the value us 20 day, the conversion that happens within 20 days will be recorded. 

<h4>Tracking Pixel</h4>
Implementing the Tracking pixel will let you see and learn more about your visitor's behaviour.

