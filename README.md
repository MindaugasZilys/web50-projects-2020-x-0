# web50-projects-2020-x-0

# Project 0

Web Programming with Python and JavaScript

Requirements:

  Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.

    1. index.html,
    2. services.html,
    3. about.html,
    4. contact.html


  Your website must include at least one list (ordered or unordered), at least one table, and at least one image.

    ul at about.html
    table at services.html
    img at index.html


  Your website must have at least one stylesheet file.

    style.css, style0.css


  Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.

    CSS properties:
      at style.css:
        1. width,
        2. background-color,
        3. padding,
        4. text-align,
        5. color.

    CSS selectors:
      at style0.css:
        1. Type Selectors
        2. Class Selectors
        3. Universal Selector
      at style.css:
        4. ID Selectors
        5. Descendant Selectors

    #id selector:

      #navLinks at style.css

    .class selector

      .topLogo at style0.css  


  Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.

    At style0.css:
    @media (max-width: 599px),
    @media (max-width: 799px).


  You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.

      at least one Bootstrap component:
        Grid at:
        index.html,
        services.html,
        about.html,
        contact.html.



  Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.

    at least one SCSS variable:
      $navTextColor: white;
      $backgroundHeader-Footer: #777;

    at least one example of SCSS nesting:

    footer {
      @extend %header-footer;
      text-align: left;
      p {
        margin-left: 30px;
      }
    }

    at least one use of SCSS inheritance:

    footer {
      @extend %header-footer;
      text-align: left;
      p {
        margin-left: 30px;
      }
    }


  In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

    Record a 1- to 5-minute screencast in which you demonstrate your app’s functionality and/or walk viewers through your code.

      Video link: https://youtu.be/3ducV8Sn_yk

