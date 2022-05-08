

# Django introduction
- Django is a high-level Python web framework for building secure and maintainable websites quickly.
- Django's advantages include its versatility, security, and scalability.

**Versatile**<br>
Django has been used to create nearly every form of website, from content management systems and wikis to social networks and news sites. It can integrate with any client-side framework and serve material in nearly any format (including HTML, RSS feeds, JSON, XML, etc). Django was used to create the website you're viewing right now!

**Secure**<br>
Django provides a framework that has been engineered to "do the right things" to defend the website automatically, which helps developers avoid many common security blunders. Django, for example, avoids typical pitfalls like keeping session information in cookies (instead, cookies merely hold a key, and the actual data is saved in the database) and directly storing passwords rather than a password hash.<br>

SQL injection, cross-site scripting, cross-site request forgery, and clickjacking are all vulnerabilities that Django protects against by default (see Website security for more details of such attacks).

**Scalable**<br>
Django employs a "shared-nothing" architecture based on components (each part of the architecture is independent of the others, and can hence be replaced or changed if needed). Because the different pieces are clearly separated, it can scale to handle more traffic by adding hardware at any level: caching servers, database servers, or orls application servers. Django has successfully scaled to meet the demands of some of the biggest websites (e.g. Instagram and Disqus, to name just two).<br>

Django is a framework with "pretty strong opinions." It has a few strategies for doing jobs that it prefers.<br>
- URLs: While it is possible to process requests from all URLs with a single function, writing a separate view function for each resource is far more maintainable. Based on the request URL, a URL mapper is used to redirect HTTP requests to the appropriate page. The URL mapper can also look for specific patterns of strings or digits in a URL and transmit them as data to a view function.
- View: is an HTTP request handler function that receives and responds to HTTP requests. Models provide views with the data they need to fulfill requests, while templates handle the return formatting.
- Models: are Python objects that define the data structure of an application and provide techniques for managing (add, change, delete) and querying database entries. mplates.
- Templates: is a text file that defines the structure and layout of a file (such as an HTML page), with placeholders for actual content. A view can use an HTML template to dynamically construct an HTML page and populate it with data from a model. A template can be used to specify the structure of any file, not just HTML!<br>

[Page Link](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)

# How django works behind the scenes
- Django is an open source web framework that can be found on Github.
- Django's open source financing is maintained by a non-profit foundation, whereas React's is maintained by Facebook.
- To arbitrate disputes/arguments, there is a Benevolent Dictator for Life a la Python.

[Page Link](https://wsvincent.com/how-django-works-behind-the-scenes/)