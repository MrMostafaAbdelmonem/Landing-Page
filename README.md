# Landing Page Project

## Table of Contents

* [Prject Title](#landing-page-project)
* [Table fo Contents](#table-of-contents)
* [Development](#development)
* [License](#license)



## Installation

 I went to `Udacity` classroom in the Landing Page Project, there is a link I cilcked and I went to a `GitHub` page then I downloaded the sarter code from there. I found a ZIP folder, I setup it and I strated to work.
___________________________________________________________________

## Development

The project depend mostly on `JavaScript`. So, I linked the JavaScript file `app.js` with the 
`index.html`. I went to the file and I defined the global variables first (`section`, `navbar__lists`). I made a `forEach` loop on the sections to use their info separately. I created `li` element with `createElement` method and I add `innerHTML` to it, to set the links inside the list, and to get the section's link I gave the forEach function variable named it `section` to get information form the sections. So, I got the links with `section.id` and the name of sections with `section.getAttribute("data-nav");` and I named it `sectionName` then I defined both in the `innerHTML` of `li`. second I made add the active class by using `forEach`lopp function with the sections and I gave it to conditions by `if`and`else` methods that if the section have the `active` class it remove the class and if not it adds the class.
lastly, I went to the `CSS` file and I made the scroll smooth by `scroll-behavior`.
___________________________________________________________________

## License

(#GNU General Public License version 3).
___________________________________________________________________