# Babylon: four page exercise
Our coaches assigned us to create a four-page website about a company we invented. The pages needed to be divided amongst the members of the group (4), each needed to design a page. Once finished the pages needed to be joined together on one page and published in one repository.

The project is on Github because it's easier to collaborate with eachother and the other groups can evaluate the website and check off all te requirements for the project.

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
![Babylon header](https://user-images.githubusercontent.com/49682756/57920961-8d28bf80-789c-11e9-811e-193c1342cc66.png)



## Frameworks
[Bootstrap](https://getbootstrap.com)

## Built with
[Visual Studio Code](https://code.visualstudio.com/)

## Getting started
In this project we used HTML, CSS and Javascript.


- We created our **own logo** with [Photoshop](https://www.photoshop.com/) and added the logo as a favicon.

![BabylonLogo](https://user-images.githubusercontent.com/49682756/57852815-7b83e100-77e4-11e9-9ccf-eea69d3c3745.jpg)

We started with inventing a company and created four pages that needed to be on the website. 
* [Home](#home)
* [About](#about)
* [Services](#services)
* [Team](#team)
* [Contact](#contact)

and 2 additional ones:

* [Urban Farming](#urbanfarming)
* [Mission](#mission)

These contain information about our page and our mission.

### Home 

Landing page


- **Parallax image header**:

Parallax image header and body is responsive throughout every device.

```
<div class="parallax site-blocks-cover overlay aos-init aos-animate" data-aos="fade" data-stellar-background-ratio="0.5">
      <div class="container containerheader">
        <div class="row align-items-center justify-content-center text-center">
```

### About 

Contains the logo of the company.

### Urban Farming


- **Photostack with Javascript**:
```
    <link rel="stylesheet" type="text/css" href="photostack/jquery.Photostack.css" />

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
### Javascript

We used Js to create an interactive photo gallery, active contact form and active navbar that collapses when not used. 

## Project link

[Babylon: Urban farming](https://yelenamerzlyakova.github.io/Babylon/)


## Tests
- **[Google Lighthouse](https://developers.google.com/web/tools/lighthouse/#devtools)**:
![Screenshot lighthouse test](https://user-images.githubusercontent.com/49682756/57934386-e81fde00-78bf-11e9-8002-d2381c9374af.png)



- **[Monkey test](https://monkeytest.it/)**:
![Screenshot monkey test](https://user-images.githubusercontent.com/49682756/57934439-084f9d00-78c0-11e9-8731-4820767cefe4.png)




- **[W3C validator](https://validator.w3.org/)**:
![Screenshot w3c validator](https://user-images.githubusercontent.com/49682756/57934541-392fd200-78c0-11e9-8c39-48580f5d3530.png)




## Credits
* [Yelena Merzlyakova](https://github.com/YelenaMerzlyakova)
* [Sascha Goldstein](https://github.com/SaschaGoldstein)
* [Floor Jules Segers](https://github.com/FloorJulesSegers)
* [Lennert Verreth](https://github.com/LennertVerreth)



## License
[MIT License](https://github.com/YelenaMerzlyakova/Babylon/blob/master/License.txt)
