###My changes from Jan 29, Melanie

**Navigation**
- included links and id’s to sections (now you can reach the section, but the nav-bar appears above the heading)
- improved readability of the nav-bar when it appears above the background: added class “font-weight-bold” to ul and "text-decoration: underline" at hover
- same red color for navigation-items (in the _header.scss)
- when burger menu opens, i changed to "text-align: right" (_header.scss), *but at smaller screens than 440px, the burger switches to the left, so the links should again also switch to the left*

**Sections**
- made all buttons color blue with adding "class=bt-info" on the element
- regular spaces between and inside sections: had to remove the margin-top: 40px from all sections, because due to overlapping with paddings, it was irregular
- "About"-paragraph same width as in accommodation-section
- i changed all second headings inside the sections into h4, to be all the same; and i removed "font-weight: 300" from small headings because this declaration was meant to the other font