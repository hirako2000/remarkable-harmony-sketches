<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

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

Harmony is a side loaded application for the reMarkable that supports some interesting procedural brushes, and even has a layers feature to compose pieces

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

Git clone/checkout this repo

You need python3 if you want to build the content. 

### Images folder/s

- Put photos in the `/photos` folder. Flat list of images, or add subfolders too!
- For each of the folder, its name will become the album name

**Example**: You can use `tree photos /F` to see all of your file in `photos` folder
```
├───photos
│   ├───albums1
│   │   ├───IMG1_01.jpg
│   │   ├───IMG1_02.png
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
$ npm run build # this require python3
```

It generates the files in the `./dist` folder.
  

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Asset size stats

FIXME

| asset      | size    | gziped |
| ---------- | ------- | ------ |
| index.html | 1.7 kB  | 1.1 kB |
| styles.css | 0.79 kB | 0.5 kB |
| script.js  | 10.4 kB | 3.5 kB |
	
## Roadmap

- [x] Layout POC
- [ ] Better layout
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

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)

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
[product-screenshot]: images/screenshot.png


- Open your terminal linux/OSX and run
```
python setup.py
```
- Personalize the contents of website at `info.json`.
- Commit all change and host your repo as a static site, for e.g on surge.sh, netlify, whatever.
- ... and that's all your gallery

## How It Works

- VueJS framework to render the gallery
- `setup.py` will go through all of folders in `/photos/` directory and create a `config.json` file.
- It collects all of information of each photo in the photo subfolder/s. It aggregates all data into one file called `config.json`.
- Once you've created your `config.json`, the website can use it to figure out the photos to show.
