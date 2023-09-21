# Resume
PORTFOLIO now.
My name is Jann Adalla. I build a variety of software and I work mostly with web applications. 
Projects
1. WordPress breakdown
Overview
This section serves the purpose of describing the whole of WordPress and its workings from the highest level downwards. What default pages does a starting WordPress site have, what type of content can be published in the site, and what defines users of a site, including their associated permissions.
What a WordPress website looks like
A typical website will have static pages like Contact Us and About Us. It will also have pages that display dynamic content that changes over time.
How templates work with content
WordPress has a template engine which it uses to render content stored in the database onto HTML documents. This engine defines how content will be displayed on a webpage. It defines what the design will look like, how certain content will look like, where they will be placed, and what properties and behaviour they will have. It defines various templates, which include code that takes content from the database and populate the returned data into the templates to produce HTML documents.
The template engine follows a predefined template hierarchy to determine which template should be used to render certain pages. Depending on the name of a page, WordPress decides which template it will use for rendering. If the specified template is unavailable, a fallback template is used. If no fallbacks are available, the engine will use index.php to render the page.
template hierarchy:
BLOCK THEMES
