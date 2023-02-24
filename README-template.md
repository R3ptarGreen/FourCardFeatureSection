# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Deskto](./images/Screenshot%202023-02-24%20at%2013-35-07%20Four%20card%20feature%20section.png)
![Mobile](./images/Captura%20de%20pantalla%202023-02-24%20-%2012.06.33.png)

### Links

- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learnd a litle bit more about @media query and make the page responsive

```css
@media screen and (max-width:1130px) {
    .container{
        width: 60rem;
        height: 50rem;
    }
    .supervisor{
        margin-right: 0.1rem;
    }
    .calculator{
        margin-left: 0.1rem;
    }
    .supervisor, .team_builder, .calculator, .karma{
        width: 20rem;
        height: 13rem;
    }
    .img_card{
        padding-top: 1rem;
    }
}
@media screen and (max-width:950px) {
    .container{
        width: 50rem;
        height: 50rem;
    }
    .supervisor{
        margin-right: 0.1rem;
    }
    .calculator{
        margin-left: 0.1rem;
    }
    .supervisor, .team_builder, .calculator, .karma{
        width: 16.5rem;
        height: 13.5rem;
    }
    .img_card{
        padding-top: 0.5rem;
    }
}
@media screen and (max-width: 800px) {
    .container{
        width: 40rem;
        height: 50rem;
    }
    .supervisor{
        margin-right: 0.1rem;
    }
    .calculator{
        margin-left: 0.1rem;
    }
    .supervisor, .team_builder, .calculator, .karma{
        width: 15rem;
        height: 15rem;
    }
    .img_card{
        padding-top: 1rem;
    }
}
@media screen and (max-width: 750px) {
    .container{
        margin-top: 4vh;
        width: 21rem;
        height: 85rem;
        grid-template-rows: 20% 20% 20% 20% 20%;
        place-items: start;
        place-content: start;
        grid-template-areas: "header"
                              "sup"
                              "team"
                              "karma"
                              "calc";
    }
    .header{
        width: 21rem;
        height: 18rem;
        grid-area: header;
        position: absolute;
        top: 8rem;
        text-align: center;
    
    }
    .header h1{
        font-size: 1.7em;
    }
    .header span{
        width: 21rem;
        font-size: 1.7em;
    }
    .header p{
        width: 21rem;
        padding-top: 1rem;
    }
    .supervisor, .team_builder, .calculator, .karma{
        width: 21rem;
        height: 15rem;
        place-items: center;
        padding: 2rem;
        border-radius: 0.5rem;
        background-color: white;
        box-shadow: 0px 10px 21px -1px rgba(137, 143, 186, 0.75);
    }
        
    .supervisor{
        margin-top: 0;
        margin-right: 0;
        grid-area: sup;
        border-top: 0.25rem solid hsl(180, 62%, 55%);
    }
    .team_builder{
        margin-top: 0;
        grid-area: team;
        border-top: 0.25rem solid hsl(0, 78%, 62%) ;
    }
    .calculator{
        margin-top: 0;
        margin-left: 0;
        grid-area: calc;
        border-top: 0.25rem solid hsl(212, 86%, 64%);
    }
    .karma{
        margin-top: 0;
        grid-area: karma;
        border-top: 0.25rem solid hsl(34, 97%, 64%);
    }

    .img_card{
        padding-top: 1rem;
    }
}
```

### Continued development

I would like continued development on my responsive design and start using flexbox like a complement to grid display

### Useful resources

- [Pixel converter](https://codebeautify.org/rem-to-px-converter) - This page is awesome to convert size in rem/em/%, and stop using px

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor
