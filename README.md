<a name="readme-top"></a>

# normalize-reset

Custom css baseline styles

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

The goal of a reset/normalize stylesheet is to reduce browser inconsistencies.

While browser inconsistencies have improved over the years,
many of the most popular css normalize and css reset stylesheets have not updated in years.

This project is somewhat between a modern reset and normalize (mostly a normalize though), so I just named it normalize-reset ¯\\\_\_(ツ)\_\_/¯

Normalize-reset was created by mixing other css-reset and css-normalize stylesheets (see acknowledgments) to cater to my own needs.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Getting started with normalize-reset should be fairly straightforward. Just follow these simple steps.

### Installation

1. Download the `normalize-reset.css` file
2. Place the normalize-reset.css-file in your project folder or subfolder (e.g. `/styles`)
3. Import normalize-reset.css **BEFORE** your main stylesheet ([CSS: order of appearance](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade))

   ```html
   <!-- HTML -->
   <link rel="stylesheet" href="yourPath/normalize-reset.css" />
   <link rel="stylesheet" href="yourPath/style.css" />
   ```

   or

   ```js
   /* JavaScript */
   import "yourPath/normalize-reset.css";
   import "yourPath/style.css";
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Make sure to have your own styles imported after the normalize-reset.css import.
The normalize-reset is just a starting point, feel free to overwrite the styles when needed in your main stylesheet.

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Project Link: [https://github.com/aaronharinck/normalize-reset](https://github.com/aaronharinck/normalize-reset)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Joshua Comeau](https://www.joshwcomeau.com/css/custom-css-reset/)
- [Modern-normalize](https://github.com/sindresorhus/modern-normalize)
- [Eric A. Meyer](https://meyerweb.com/eric/tools/css/reset/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
