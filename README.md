# Fluid-UI-Responsive-Tooltip
PeopleTools | Fluid UI | Responsive and Mobile-Friendly Tooltip

Implementation Details:

This code is based on the following blog post by Osvaldo Valutis.
https://osvaldas.info/elegant-css-and-jquery-tooltip-responsive-mobile-friendly

Sample PeopleCode:

In the sample peoplecode provided, you can see that along with the text attribute we have also added the rel="tooltip" attribute to the page field element using the HtmlAttributes property.

CSS:

The CSS provided is a modified version of the CSS provided in Osvaldo's blog. The modifications update the tooltip text and background colors. You can make additional modifications if necessary based on your requirement. Create a Free-Form Style Sheet object in App Designer using the CSS (CSK_TOOLTIP_CSS) in the GitHub project.

JavaScript:

The javascript provided - is an extension of the code provided in Osvaldo's blog - wraps the code in a require block to facilitate the loading of jQuery using requireJS which is detailed in the javascript injection framework (refer link below). You could use alternate methods (instead of using the javascript injection framework) but you need to make sure that jQuery is loaded prior to execution of this javascript. Additionally, this javascript also takes care of loading the CSS (CSK_TOOLTIP_CSS) using helper functions in the javascript injection framework. Create a JavaScript (HTML) object in App Designer using the javascript (CSK_TOOLTIP_JS) in the GitHub project.

JavaScript Injection Framework: https://pe0ples0ft.blogspot.com/p/javascript-injection-framework.html

Demo:

https://pe0ples0ft.blogspot.com/2017/08/fluid-ui-responsive-tooltip.html
