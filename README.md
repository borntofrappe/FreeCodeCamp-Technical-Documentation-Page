Link to the working pen right [here](https://codepen.io/borntofrappe/full/VXrQdR/).

# The Task

> Complete the aptly named project in the beta curriculum @freecodecamp. 
>
> In the line of "Applied Responsive Web Design Projects": *Build a Technical Documentation Page*.

More specifically build a page similar to [this one](https://codepen.io/freeCodeCamp/full/NdrKKL), which contains the following HTML structure.

1. ## Navigation bar

    The page should have a `nav` element, with `id="navbar"`. This one should itself contain:

    - a `header` element describing the topic of the documentation;

    - anchor link elements with `class="nav-link`, redirecting visitor to the named sections of the page;

    Moreover, this navigation bar ought to be displayed on the left of the screen for regular-size screen sizes (desktops and laptops). And always on these devices, the navigation bar should be *fixed* to the left of the screen.
  
1. ## Main content

  Beside the navigation bar, the page should contain a `main` element with `id="main-doc"`. 

  This element is used for the actual content of the technical documentation page. Content which is structured in several `section` elements with `class="main-section"`. 

  In these sections the content of the page should present itself through:
  
  - `header` elements, each with an id aptly referring to the header's text;
  
  - `p` elements, which describe the text of the technical documentation;
  
  - `code` elements, displaying code-formatted text;
  
  - `li` elements, to include some sort of list.
  

  
## First thoughts

By itself the specifics detailed in the user stories depict a structure with two macro-areas. These macro areas should be laid side by side, at least on desktop-size devices, and should present the described HTML markup.

While the structure of the page is thusly "fixed", there are still lessons to be learned behind the simple implementation of the structure and fulfillment of the user stories. Lessons regarding 1) how to properly display code in a page 2) how to lay elements side by side and still make one of them fixed to the page.

Considerations regarding style are always present, even though rarely stressed, but the main challenges behind the page reside in the layout portion and the correct display of different types of content.

# Lessons learned

// TODO: include logic behind the choices made in the page


