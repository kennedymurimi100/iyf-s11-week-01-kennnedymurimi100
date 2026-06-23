What Is Semantic HTML and Why Does It Matter?
Semantic HTML uses elements that clearly describe their meaning and purpose. Instead of relying on generic tags like <div> and <span>, semantic elements such as <header>, <nav>, <main>, <section>, and <footer> provide structure and context to both browsers and assistive technologies.


Benefits of semantic HTML include:
-----------------------------------
Improved accessibility for screen reader users.
Better SEO because search engines understand the page structure.
More maintainable and readable code.

Before: Non-Semantic HTML
<div class="header">
  <h1>My Portfolio</h1>
</div>

<div class="navigation">
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</div>

After: Semantic HTML
<header>
  <h1>My Portfolio</h1>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

The semantic version clearly communicates the purpose of each section, making the page easier to understand and navigate.

Accessibility Issues Found and Fixed


Issue Found
------------
- Language Attribute
- Heading Hierarchy
- Images
- Links Text
- Form Labels



How I Fixed Them
-----------------
- By adding a lang attribute to the html tag.
- By using headings in a logical, nested order.
- Providing meaningful alternative text for informative images.
- Using a descriptive text that explains the link's destination or purpose.
- By associating a label with each form field using the for attribute.


- This concludes that Semantic HTML and accessibility go hand in hand. By improving document structure, adding proper labels and other improvements which are needed.

- You can view my deployed portfolio here:

[https://kennedymurimi100.github.io]

###Final Lighthouse Accessibility Score: 100/100
