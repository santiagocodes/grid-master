<h1 align='center'>Grid Master</h1>

<p align='center'>
Playing around with animal emoticon cards using the power of GRID!<br>
<a href="https://santiagocodes.github.io/landing-page/"><img src="https://img.shields.io/badge/DEMO-LandingPage-9cf.svg?style=flat"></a>
</p>

<img height="90px" align="left" src="https://santiagocodes.github.io/santiagocodes/images/octocat-santiagocodes.png" alt="santiagocodes octocat" />

## Setup

### Cloning the Project

On Git Bash `git clone https://github.com/santiagocodes/grid-master.git`

## Projects within the Project

### Basic

Under the 'basic' folder you will find an example of a responsive grid at one of it's simplest forms. The main line of code to have a look at on this project would be `grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));`, which organizes the items inside the grid... all occupying the same space (between 200px and 1 fraction of the row (for mobile)) and creating another row whenever there is no more horizontal space for the next item.

### Uneven

Under the 'uneven' folder you will find an example of a responsive grid with some items being bigger than others. Here you can add a class to some items and manipulate the space those items occupy within the grid as follows.

```css
.green {
   grid-column: span 2;
   grid-row: span 2;
}
```

What this means is that the cards with a class of 'green' will take up the space of two items across the x-axis (with `grid-column: span 2;`) and the same across the y-axis (with `grid-row: span 2;`).

<h2 align='center'>Support</h2>

<p align='center'>
Reach out at any of the following places.<br>
    <a href="https://twitter.com/maricstgo"><img src="https://img.shields.io/badge/twitter.com-@maricstgo-blue?style=flat&logo=twitter"></a>&nbsp;
    <a href="https://dev.to/santiagocodes"><img src="https://img.shields.io/badge/dev.to-@santiagocodes-black?style=flat&logo=dev.to"></a>&nbsp;
    <a href="https://santiagocodes.com"><img src="https://img.shields.io/badge/website-santiagocodes.com-blueviolet?style=flat"></a>&nbsp;
</p>
