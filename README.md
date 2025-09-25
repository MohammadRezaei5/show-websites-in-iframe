# show-websites-in-iframe

2 important points to consider:

1. What are the sites that do not allow, then click on the browser console to check the errors and investigate.

2. When you want to display a site with iframe, you must have permission to do this. Some allow this by default, but some do not, so why?

Explanation of security headers related to iframes:

🎯 X-Frame-Options:
It is an HTTP header that tells the browser whether it is allowed to display a web page inside an iframe or not.

🎯 :Content-Security-Policy (CSP) - frame-ancestors
It is a newer and more powerful header that specifies multiple security policies.

💯 Why are these headers important?

Preventing Clickjacking Attacks: If a site allows an iframe to be displayed anywhere without restrictions, someone may load its page on a malicious site and trick users into clicking on malicious buttons, for example, to control security and protect user privacy.

sources for further reading:

[MDN Web Docs about X-Frame-Options](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options)

[MDN Web Docs about Content-Security-Policy frame-ancestors](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Content-Security-Policy/frame-ancestors)

[OWASP Clickjacking Explanation and Solutions](https://owasp.org/www-community/attacks/Clickjacking)

--------------------------------------------------------------

Some features:

* css --> flexbox/transition/box-shadow/@media/:hover
* js --> function-declaration/getElementById
--------------------------------------------------------------

Live-Demo ----> [Click Here](https://mohammadrezaei5.github.io/show-websites-in-iframe/)

--------------------------------------------------------------

GIF:
![show-websites-in-iframe](https://github.com/user-attachments/assets/1ab7ff17-0d10-472a-b0d0-f928ee2c3a3d)

