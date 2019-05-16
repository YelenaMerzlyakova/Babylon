# Four page website
Our coaches assigned us to create a four-page website about a company we invented. The pages needed to be divided amongst the members of the group (4), each needed to design a page. Once finished the pages needed to be joined together on one page and published in one repository.

The project is on Github for the other groups to evaluate the website and to check off all te requirements of the project.

The website needed to have:
- A parralax image header
- Address (if needed)
- Google maps pinned on the location of the company somewhere on the onepager
- A working phone number
- Clickable email
- A working form

The website needed to be: 
- Responsive

## Babylon
Babylon is the company we invented. The company deals with urban farming.

> Babylon is committed to feeding people in a way that is positive for communities and the environment, today and in the future. We build kitchen gardens where people live, which means our produce is fresher, has longer shelf life and shorter food miles.



## Table of content
* [Screenshots](#screenshots)
* [Frameworks](#frameworks)
* [Built with](#built-with)
* [Getting started](#getting-started)
* [Tests](#tests)
* [Credits](#contribution)
* [License](#license)


## Screenshots

*Header with parallax*
![Babylon header](https://user-images.githubusercontent.com/49682756/57764882-a0a12280-7704-11e9-9154-d7a8d72cf26b.png)



## Frameworks
[Bootstrap](https://getbootstrap.com)

## Built with
[Visual Studio Code](https://code.visualstudio.com/)

## Getting started


- We created our **own logo** with [Photoshop](https://www.photoshop.com/) and added the logo as a favicon.

![BabylonLogo](https://user-images.githubusercontent.com/49682756/57852815-7b83e100-77e4-11e9-9ccf-eea69d3c3745.jpg)

We started with inventing a company and created four pages that needed to be on the website. 
* [Home](#home)
* About
* [Services](#services)
* [Contact](#contact)



### Home 


- **Parallax image header**:

```
<div class="parallax site-blocks-cover overlay aos-init aos-animate" data-aos="fade" data-stellar-background-ratio="0.5">
      <div class="container containerheader">
        <div class="row align-items-center justify-content-center text-center">
```




### Services

- **3 cards with [Bootstrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid/)**:

```
<div class="col-sm-4 d-flex align-items-stretch">
        <div class="card">
            <div class="card-body">

```


### Contact

- **Google maps**:
```

<div class="mapz">
    <h1>Map</h1>
    <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2505.72239293552!2d4.528598279880381!3d51.095130579669565!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c3fb4c700fda05%3A0x2d9875aeba3f244!2sZijpstraat+14%2C+2570+Duffel!5e0!3m2!1snl!2sbe!4v1557997352090!5m2!1snl!2sbe"
        width="475" height="500" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>

```

- **A contact form**:
```

<div class="contact-form">

    <h1>Contact</h1>

        <div class="textboxx">
            <label>Full Name :</label>
            <input type="text" placeholder="Enter Your Name">
        </div>

</div>
```


## Project link


## Tests



## Credits
* [Yelena Merzlyakova](https://github.com/YelenaMerzlyakova): **Home** page and overall styling of the website
* [Sascha Goldstein](https://github.com/SaschaGoldstein):  **About** page and invented the company
* [Floor Jules Segers](https://github.com/FloorJulesSegers): **Services** page and the Readme.md
* [Lennert Verreth](https://github.com/LennertVerreth): **Contact** page with Google maps, working phone number and clickable e-mail



## License
[MIT License](https://github.com/YelenaMerzlyakova/Babylon/blob/master/License.txt)
