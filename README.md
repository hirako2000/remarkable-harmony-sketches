<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Uptime][uptime-shield]][uptime-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license][license-shield]][license-url]
<!-- for some reason those can't work yet [![w3c-validation][w3c-validation-shield]][w3c-validation-url]
[![OSSF-Scorecard Score][score-shield]][score-url] -->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="images/logo.png" alt="Logo" width="80" height="80">

  <h3 align="center">Sketch Collection</h3>

  <p align="center">
    A collection of sketches made with on the reMarkable tablet, using harmony
    <br />
    <a href="https://github.com/hirako2000/remarkable-harmony-sketches/#about-those-sketches"><strong>Explore »</strong></a>
    <br />
    <br />
    <a href="https://remarkable-harmony-sketches.surge.sh">View Sketches</a>
    ::
    <a href="https://github.com/hirako2000/remarkable-harmony-sketches/issues">Report Bug</a>
    ::
    <a href="https://github.com/hirako2000/remarkable-harmony-sketches/issues">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-those-sketches">About</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#dev-server">Images folder/s</a></li>
        <li><a href="#build">Build</a></li>
      </ul>
    </li>
    <li><a href="#asset-size-stats">size stats</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About those Sketches

[![Product Name Screen Shot][product-screenshot]](https://remarkable-harmony-sketches.surge.sh)

[Harmony](https://rmkit.dev/apps/harmony) is a side loaded application for the reMarkable that supports some interesting procedural brushes, and even has a layers feature to compose pieces. It is part of rmkit, an ecosystem of unofficial apps and dev tools compatible with the multiple devices.

Could use a pen, could use an advanced drawing app on an iPad, but no. Here's why:

* Can eassily erase, a pen is a bit more tricky
* Procedural patterns, that's a time saver
* 4096 pressure sensitivity, I doubt the iPad can do that

Of course, nothing is perfect, but I'm trying to contribute to harmony to make it better.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

The site is rather simple and is built via the scripts contained in this repo.

More to come.

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Git clone/checkout this repo.

You need python3 if you want to build the content. 

### Images folder/s

- Put photos in the `/photos` folder. Flat list of images, or add subfolders are supported
- Each of sub folder becomes the album name

**Example**: You can use `tree photos /F` to see all of your file in `photos` folder
```
├───photos
│   ├───sketches
│   │   ├───sketch-1.jpg
│   │   ├───some-other.png
│   │   └─── ...
│   ├───albums2
│   │   ├───IMG2_01.jpg
│   │   ├───IMG2_02.jpg
│   │   └─── ...
│   ├───albums3
│   │   ├───IMG3_01.png
│   │   ├───IMG3_02.jpg
│   │   └─── ...
│   └─── ...
```

then...

### Build

```
$ npm run build
```

It generates the files for the entire page.
  
#### Host / Deploy

Deploy the html along with the photos and dist folder as a static site. 
There are free hosting services out there, e.g on surge.sh, Netlify.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Customize 

- Personalize the contents of the website by editing `info.json`.

## Asset size stats

| asset      | size    | gziped |
| ---------- | ------- | ------ |
| index.html | 2.38 kB  | 1.5 kB |
| styless | 9.01 kB | 5.7 kB |
| scripts  | 10.2 kB | 3.7 kB |
	
These don't include vue.js dependency size and web font load.

## Roadmap

- [x] Layout POC
- [x] Better layout
- [ ] Superb layout
- [ ] Provide details view of entries


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**, although there isn't much to add to this project.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/some-feature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature/some-feature`)
5. Open a Pull Request

## License

[![license][license-shield]][license-url]

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][license-url].

[license-url]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: hhttps://img.shields.io/github/license/hirako2000/remarkable-harmony-sketches?style=for-the-badge

If you too produce work and publish it out there, it's clearer to choose a [license](https://choosealicense.com).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [vuejs](https://vuejs.org/)
- [olympact.io](https://www.olympact.io/el/blog/5-principles-for-minimalism-in-ux-ui)
- [mom](https://unsplash.com/photos/7ne1ifXhI_Y)

## How It Works

- VueJS framework to render the gallery
- `setup.py` will go through all of folders in `/photos/` directory and create a `config.json` file.
- It collects all of information of each photo in the photo subfolder/s. It aggregates all data into one file called `config.json`.
- Once you've created your `config.json`, the website can use it to figure out the photos to show.

[observatory-shield]: https://img.shields.io/mozilla-observatory/grade-score/remarkable-harmony-sketches.surge.sh?publish&style=for-the-badge
[uptime-shield]: https://img.shields.io/uptimerobot/ratio/m792462927-d88b9d2ebd47a1c7ccdf9763?style=for-the-badge
[uptime-url]: https://remarkable-harmony-sketches.surge.sh
[contributors-shield]: https://img.shields.io/github/contributors/hirako2000/remarkable-harmony-sketches.svg?style=for-the-badge
[contributors-url]: https://github.com/hirako2000/remarkable-harmony-sketches/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hirako2000/remarkable-harmony-sketches.svg?style=for-the-badge
[forks-url]: https://github.com/hirako2000/remarkable-harmony-sketches/network/members
[stars-shield]: https://img.shields.io/github/stars/hirako2000/remarkable-harmony-sketches.svg?style=for-the-badge
[stars-url]: https://github.com/hirako2000/remarkable-harmony-sketches/stargazers
[issues-shield]: https://img.shields.io/github/issues/hirako2000/remarkable-harmony-sketches.svg?style=for-the-badge
[issues-url]: https://github.com/hirako2000/remarkable-harmony-sketches/issues
[license-shield]: https://img.shields.io/github/license/hirako2000/remarkable-harmony-sketches.svg?style=for-the-badge
[license-url]: https://github.com/hirako2000/remarkable-harmony-sketches/blob/main/LICENSE.txt
[w3c-validation-shield]: https://img.shields.io/w3c-validation/html?style=for-the-badge&targetUrl=https%3A%2F%2Fremarkable-harmony-sketches.surge.sh
[w3c-validation-url]: https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fremarkable-harmony-sketches.surge.sh&profile=css3svg&usermedium=all

[score-shield]: https://img.shields.io/ossf-scorecard/github.com/hirako2000/remarkable-harmony-sketches?style=for-the-badge
[score-url]: https://github.com/hirako2000/remarkable-harmony-sketches.surge.sh

[product-screenshot]: images/screenshot.png

