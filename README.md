
# CODE REFACTOR

Explore the [project page](https://github.com/cynthiwu/code-refactoring-homework-9.8.20)

View the [github-pages](https://cynthiwu.github.io/code-refactoring-homework-9.8.20/)


## Table of Contents

* [About the Project](#about-the-project)
  * [HTML Changes](#html-changes)
  * [CSS Changes](#css-changes)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


## About The Project

The focus of this project was on refactoring an existing codebase to increase the usage of semantic HTML, ultimately increasing the web accessibility of the resulting product. The existing code included an HTML and CSS file for a company webpage (i.e., Horiseon), along with a "User Story" and set of "Acceptance Criteria". The webpage outlines Horiseon's company offerings, along with the benefits associated with leveraging these offerings. There are a number of images and figures included to supplemnt the literary content. 

![Project Screenshot](assets/images/readmeimg.png)

### HTML Changes

* Updated the &#60;title&#62; to reflect the name of the company, more descriptive. 
* Changed the &#60;div&#62; containing &#60;h1&#62; and &#60;ul&#62; to be a &#60;header&#62;, with the aria role of "banner". 
* Changed the &#60;div&#62; containing the &#60;ul&#62; to be a &#60;nav&#62;
* Changed the &#60;div&#62; containing of the main content to be a &#60;body&#62;, and added the &#60;main&#62; tags.
* Added an role and aria-role to the &#60;div&#62; containing the background image. 
* Added &#60;section&#62; tags in place of &#60;div&#62; tags for may content sections, and &#60;header&#62; tags fro titles. 
* Added alt content for each image of the main section.
* Changed &#60;div&#62; of the right-hand content to be an &#60;aside&#62;, and added &#60;figure&#62; tags in place of divs for each benefit.
* Added alt content for each image of the aside section. 
* Added &#60;header&#62; tags to contain the heading of each figure. 
* Changed the bottom &#60;div&#62; to be a &#60;footer&#62;, and changed the &#60;h2&#62; to an &#60;h4&#62; to follow the logical flow of the document. 

### CSS Changes

* Updated the relative paths of all nested CSS selectors based on changes above.
* Combined the individual classes for each section, header, and image of the main container as styling had been the same. 
* Reordered classes and selectors to be in line with the HTML flow (ex., moved body selector down after the header).
* Combined classes for the aside headers, content, and images as the styling had been the same. 


### Built With

* No frameworks were used in the creation of this project.


## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

None

### Installation

1. Clone the repo
```sh
git clone git@github.com:cynthiwu/code-refactoring-homework-9.8.20.git
```

## Roadmap

Currently no known issues, but track track [open issues](https://github.com/cynthiwu/code-refactoring-homework-9.8.20/issues) for proposed features (and known issues) in the future.


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License

Unknown

## Contact

Cynthia Wu - [@cynthia21wu](https://twitter.com/cynthia21wu) - cynthia21wu@gmail.com

Project Link: [https://github.com/cynthiwu/code-refactoring-homework-9.8.20](https://github.com/cynthiwu/code-refactoring-homework-9.8.20)
