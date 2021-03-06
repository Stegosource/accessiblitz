# Accessiblitz

Let's make the web more accessible together.

#### What is Accessibility?

When we talk about accessibility in web development, a lot of people jump to the assumption that we mean making websites that blind people can use. While that is certainly part of it, that's really just one specific demographic of users. In fact, accessibility affects many different demographics, and it can be broken down to the simple concept:

Users should be able to access the contents of your website independent on their circumstances.

#### What are some circumstances that might make your website inaccessible?

* Visual impairment relying on screen-readers and keyboard navigation
* Physical or mental impairments so the mouse cannot be used
* Color-blindness or fuzzy vision making it hard to read small text
* Technical limitations such as connectivity, screen size, or browsers

#### Why it's important

* Accessible sites means more users, which may have an impact your goals
* There's a growing number of web-accessibility-related lawsuits
* If you are a govenment funded institution, you HAVE to be accessible
* Accessible design patterns often encourage better development practices
* It's just the right thing to do

#### Steps to make things more accessible:

1.  Visually hidden content for screen readers.
2.  Toggle menu visibility with just the keyboard.
3.  Create a "skip to content" link.
4.  Image alt attribute.
5.  Accessible custom radio buttons.
6.  Accessible custom checkboxes.
7.  Accessible custom switch input.
8.  Mimic system-specific focus styles.
9.  Add another visually hidden class without focus state.
10. Give plain text inputs accessible labels.
11. Switch to using semantic markup.
12. Make external links open in same tab.
13. Things work with or without JavaScript.

Other considerations no covered here:

* Color contrast
* Font-size and legibility
*

### Helpful Tools & Resources

Understanding the laws and guidelines:

* [Section 508 of the Rehabilitation Act](https://section508.gov/)
* [Title II of The Americans with Disabilities Act (ADA)](https://www.ada.gov/pcatoolkit/chap5toolkit.htm)
* [The Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/TR/WCAG21/)

Tools for testing/auditing your site:

* [HTML_CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/) - Webapage accessibility auditing bookmarklet
* [aXe Developer Tools](https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/) - Webapage accessibility auditing browser extension
* [Chrome Lighthouse](https://developers.google.com/web/tools/lighthouse/) - Webapage accessibility auditing browser feature (Chrome)
* [Tenon](https://tenon.io/) - Webpage accessibility auditing service
* [WAVE](http://wave.webaim.org/) - Webpage accessibility auditing service
* [ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn) - Screen reader browser extension (Chrome)
* [NoCoffee](https://addons.mozilla.org/en-US/firefox/addon/nocoffee/) - Visual-impairment simulating browser extension
* [Colorblind Web Page Filter](https://www.toptal.com/designers/colorfilter) - Colorblind simulating browser extension

Build tools:

* [Access Lint](https://www.accesslint.com/) – Automatically test your pull requests
* [Colorsafe](http://colorsafe.co/) – Test font and color combinations
* [Tanaguru contrast finder](http://contrast-finder.tanaguru.com/) – Color contrast tester
* [RANDOMA11Y](https://www.randoma11y.com/) – Random, high-contrast color combination
