# Code Refractor

The main goal of this assignment was to make this webpage for this company more accessible. Even though the initial code produced a very similar webpage, the updated code provides a lot more description for the readers of the code. Along with more details the code is also slightly consolidated for more efficient coding pratices. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The only application neccessary to run this code is a source code editor.

Visual Studio Code is an example.

### Installing

Go to a browser software and download the source code editor of choice and run the code.

### Summary

The first task I dealt with was changing the non-semantic elements in the HTML file to semantic tags. I replaced the "div" and "span" tags with more specific tags so people could better understand the page solely from the HTML tags. For example I revised a certain "div" tag to be a "nav" tag in the nav bar header. I made sure all the HTML elements followed a logical structure by following the rules of inline or inline-block for each of the tags. I put all the block-level elements, which are tags such as "section" and "footer", on their own line. Inline elements did not have to be on their own line and examples of those are "a" and "input". In order to further improve the accessibility of the webpage, I inserted alt attributes to provide detail descriptions for each of the images on the webpage. Any reader viewing the HTML code could get a good understanding solely from the description and without seeing the actual image. For all the images in the input tags, the description is in the alt attritbute but for the image in the figure tag, the description is in the title attribute. I corrected any heading atttributes that were not the correct order. The footer did not need an H2 attribute as it was a much less relevant piece of the page than the services that the company provided that had an H2 tag. I added a description to the title of the page so people can know what the page is about without having to look at the whole page. Lastly, I made the style.css code much more concise. I combined the classes that had the same attributes within it so the code would not be repetitive. 

## Screenshots
![Title](Images/Title.PNG)
![EmbeddedLinks](Images/EmbeddedLinks.PNG)
![DescriptiveAltAttributes](Images/DescriptiveAltAttributes.PNG)
![ConsolidatedClasses](Images/ConsolidatedClasses.PNG)

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)


## Deployed Link

* https://rishabb02.github.io/homework-ucb/


## Authors

* **Rishab Baldua** 

- [Link to Portfolio Site](https://github.com/rishabb02/homework-ucb)
- [Link to Github](https://github.com/rishabb02)
- [Link to LinkedIn](https://www.linkedin.com/in/rishabbaldua/)



<!-- I helped a marketing company.  -->
![TestScreenshot](Images/TestScreenshot.PNG)