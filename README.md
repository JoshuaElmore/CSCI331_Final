# CSCI331_Final

I decided to do my project on Web Assembly specifically Web Accessibility Initiative - Accessible Rich Internet Applications i decide to make an example site that showed off in simple terms how to use some of the most important ARIA attributes. I was group number 30 and I did this on my own.

https://csci331.cs.montana.edu/~m72z725/final/index.html

My goal in this was to make a simple site that anyone who knows HTML and look at and start implementing accessibility in the web apps they are making today. My guess in many web devs today ignore accessibility because they think it is to complicated or their clients wont care about it. That is why I tried to focus on the some of the most common an easy ist to implement ones attributes.

I didn't use any particularly advanced web frameworks. I used the built in support for ARIA in my browser. Along with some java script to to control the dynamic states. I used a combination of ARIA states and properties to make the website more usable for screen readers. Most of the states follow a simpler format of when an action is preformed on an element like hovering on clicking on it you call some java script to update the attribute and change the page.
I did this by setting up event listener and calling functions to change the attribute and display. I used this for the main expanding menu bar on the top of the page along with serval more example on each page.

As I wad the only member of this group this will be a simple paragraph. I did the whole web page all 3 pages and all the HTML CSS Java script and the PowerPoint and presentation.

I explored several ARIA properties, such as aria-expanded, aria-hidden, aria-required, aria-labelledby, and aria-live. I learned how to use aria-expanded to indicate whether a collapsible element is currently expanded or collapsed, aria-hidden to hide elements from screen readers, aria-required to indicate required input fields, aria-labelledby to associate elements with their labels, and aria-live to create live regions that screen readers will announce when updated. I also learned how to use JavaScript to dynamically update these ARIA properties. Finally, i learned that ARIA properties should be used as a last resort when the semantics of HTML elements and their attributes are not sufficient to convey an element’s role and state, and that it’s usually better to use native HTML elements and their attributes first for the best accessibility.

References
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA
https://www.w3.org/TR/html-aria/
https://web.dev/learn/accessibility/aria-html