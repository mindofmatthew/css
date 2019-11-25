# css

When I create new projects, I find that I wind up making a lot of the same CSS changes, since I have a fairly
consistent set of ideosyncratic preferences when it comes to web design. With this package, I'm attempting to
create a baseline set of rules so that I can more easily create projects (especially examples and demos) with
nice styling.

This code is guided by the following constraints:

* __Focus on built-in HTML tags:__ The focus here should be on the basic set of tags supported by HTML, especially those (like form elements) that already have a sophisticated default styling.
* __Infer as much as possible:__ Use contextual information such as text size and currentColor to control styling as much as possible.
* __Prefer CSS Variables:__ Define a manageable set of CSS variables that can be used for easy theme customization, especially color scheme.