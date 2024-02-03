# Custom Checkbox - Accesibility

This frontend application leverages plain HTML and CSS to craft a custom checkbox that maintains the accessibility features of a native checkbox, including keyboard interactivity. The implementation showcases an exclusive display of the custom checkbox, which retains all the functionality and accessibility of the native checkbox, even when the latter is hidden, all without using JS, only HTML5 and CSS3.

## Table of Contents 

- [Stack](#stack)
- [Installation](#installation)
- [Functionality / Code Decisions](#functionality)
- [Known Bugs](#known-bugs)
- [To Improve](#to-improve)
- [Acknowledgements](#acknowledgements)
- [Author](#author)


## Stack 

![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=for-the-badge)
![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=for-the-badge)

## Installation 

Get a copy of the project up and running on your local machine for development and testing purposes.

```sh
git clone https://github.com/Dave86dev/customcheckb
cd customcheckbox
```
Feel free to launch the application with your favourite live server plugin.

<div align="center">
    <a href="https://dave86dev.github.io/customcheckb/" target="_blank"><strong>PRODUCTION LINK</strong></a> 
</div>

## Functionality

Our custom checkbox is meticulously crafted to maintain the accessibility standards and behaviors expected of a native HTML element. In the process of designing our custom checkbox, we prioritized concealing the native checkbox while ensuring that both the custom and native checkboxes' behaviors are perfectly synchronized.

To accomplish this, we skillfully employed CSS3 pseudo-classes like :focus-visible, which targets styles specifically for elements focused through keyboard interactions. Additionally, we utilized the :checked pseudo-class, enabling us to style the custom checkbox in response to interactions with the native one. This thoughtful integration of CSS3 ensures that our custom checkbox not only looks good but also functions seamlessly, mirroring the accessibility features of its native counterpart.

## Author

- **David Ochando Blasco** - Full Stack Developer
  - [GitHub](https://github.com/Dave86dev) - [LinkedIn](https://www.linkedin.com/in/david-ochando-blasco-90b2ba1a/)
