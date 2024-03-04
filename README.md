# Practical 9 (week 5, practical 1): Web Accessibility
Today you’re going to be working on developing an accessible version of our favourite website… [the York Sport website](https://www.york-sport.com/). 

## Exercise 1: WCAG 2.0
But first, we need to have a better understanding of what web accessibility means and what guidelines are in place for designers and developers. So, open the [WCAG 2.0 guidelines](https://www.w3.org/TR/WCAG20/) and explore them. Make notes on what it means for a website to be:
- perceivable,
- operable,
- understandable and
- robust.

The WCAG guidelines are often intimidating and verbose. Record your notes in language that is accessible for you to quickly understand and apply to a website. 

## Exercise 2: York Sport Analysis
Open the York Sport website and try to use the site using ONLY the keyboard and not the mouse. Nielson has written [some guidance](https://www.nngroup.com/articles/keyboard-accessibility/) on how to approach this.

Take notes on whether you can:
- Navigate through the different menu items.
- Tab through all the page content in a logical order.
- Easily identify what is in focus from the keyboard. When you tab through the content the current active link is shown in the bottom left of the google chrome window.
- Use the forms on the webpage (e.g. the sign-up form)

Next, put the website through the Chrome Developer Tools accessibility audit, as we did in lecture:
1.	With the website open in Chrome, open Developer Tools by going to View > Developer > Developer Tools
2.	In the Developer Tools pane, go to the Lighthouse tab. It’s quite a few places right from the first tab, Elements. If your browser window is small, you might need to click the >> symbol to find the Lighthouse tab.
3.	Lighthouse presents a number of options. Under "Mode", select "Navigation". Under "Device", select "Desktop". Under "Categories", tick "Accessibility" and untick any other options. Finally, click "Analyze page load" to generate the report. It will take a few seconds.

What accessibility problems are identified? Note, these problems are identified in terms of the WCAG 2.0 criteria that may (or may not) be violated. You can find more detail on each problem, including the specific elements affected, by clicking on the problem description. For each problem, follow the "Learn more" link in the problem details.

## Exercise 3: York Sport Redesign and Implementation
Working in pairs or threes, use the [WebAIR resource](https://www.cs.york.ac.uk/hci/webair/) and WCAG 2.0 to implement a basic, accessible version of the YorkSport home page.

We haven’t covered input forms yet (that content is covered later in the module, so ignore any input fields and forms for now…). However, I do also recommend reading [this excellent blog post](http://adrianroselli.com/2016/01/links-buttons-submits-and-divs-oh-hell.html) about links and buttons 

Think carefully about what information is needed on the home page (don’t just copy the structure they have implemented), and how the HTML should be structured so that it is accessible.

Take any images that you need from the site and add them into your own version of the web page. What alt text would you add?

