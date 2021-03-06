# bar-chart
Bar Chart Project

This project will consist of building a library that will allow other developers to generate bar charts on their web pages using HTML, CSS and JavaScript. You'll also be using jQuery to access and manipulate the DOM in order to draw the charts.

There are intentionally no visuals provided with this project, and many aspects of the UI are left intentionally vague. We are leaving you freedom to get creative with the UI. We encourage you to make the charts look presentable and even add extra flare with things like CSS transitions and animations.

Getting Started

    1. Use this gist as the basis for your application

    2. Create a new GitHub repo, then clone it to your computer. Check out this guide for getting started with GitHub.

    3. Take a look at adding a linter into your text editor of choice, there is ESLint for Atom, ESLint for Sublime Text or ESLint for VSCode. Otherwise you can use the command line by running eslint from the command line. Take a look at the ESLint documentation for instructions.
    
    4. Set up an HTML page to be the basis of your application. You should be able to just open the page directly from your file system, you shouldn't need to set up a server for this project. Also, make sure this HTML page also pulls in jQuery.

Tips

    - Read through the jQuery documentation or find some simple tutorials on jQuery. This will help you get a handle on how to access and create DOM elements using jQuery.
    
    - Commit at every step. No commit is too small, but at the same time commit code that is not going to throw an error. One massive commit with all your work is going to result in an unsatisfactory submission.
    
    - Don't look at the code for other charting libraries to see how they're implemented, because it will either be overwhelming, overkill, or cheating.
    
    - This should be completed in only HTML, CSS and JavaScript w/ jQuery. You may find references to using SVG or Canvas for your solution. However we strongly advise that you stay away from those approaches.
    
    - Try to break your solution down into small functions that will work together to solve the problem. One massive function will not be accepted, for example.

Functional Requirements

  You should have a simple API to draw a bar chart. The function should be used by your HTML page to render the chart into your demo page. The signature of the function should be as follows:

    drawBarChart(data, options, element);

  The data parameter will be the data the chart should work from Start with just an Array of numbers

    e.g. [1, 2, 3, 4, 5]

  The options parameter should be an object which has options for the chart.
  
    e.g. width and height of the bar chart

  The element parameter should be a DOM element or jQuery element that the chart will get rendered into.

Display Requirements
Bar Chart

  Display a list of single values, horizontally as a bar chart

    Numerical values should also be displayed inside of the bar
    The position of values should be customizable too:
        Top, centre or bottom of the bar.

  Bar sizes should be dependent on the data that gets passed in

    Bar width should be dependent on the total amount of values passed.
    Bar height should be dependent on the values of the data.

  Bar properties that should be customizable:

    Bar Colour
    Label Colour
    Bar spacing (space between bars)
    Bar Chart axes

  X-axis should show labels for each data value

    Think about how you would need to structure your data to associate a label to each value

  Y-axis should show ticks at certain values

    Think about where you would configure these values. Should they be part of the data or the options to the bar chart function.

  The title of the bar chart should be able to be set and shown dynamically

  The title of the bar chart should also be customizable:

    Font Size
    Font Colour

Multiple Value (Stacked) bar charts

  Allow the user to pass multiple values for each bar.

    Think about how you would need to structure this data compared to a single bar chart.

  This should also support all the features of the single bar chart, including

    Customizable bar colours, per value
    Customizable label colours

