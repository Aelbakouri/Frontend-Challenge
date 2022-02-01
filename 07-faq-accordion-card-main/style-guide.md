# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

#### Text

- Very dark desaturated blue: hsl(238, 29%, 16%)
- Soft red: hsl(14, 88%, 65%)

#### Gradient

Background gradient:

- Soft violet: hsl(273, 75%, 66%)
- Soft blue: hsl(240, 73%, 65%)

### Neutral

#### Text

- Very dark grayish blue: hsl(237, 12%, 33%)
- Dark grayish blue: hsl(240, 6%, 50%)

#### Dividers

- Light grayish blue: hsl(240, 5%, 91%)

## Typography

### Body Copy

- Font size: 12px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700

.container {
width: 1200px;
height: 500px;
/_ margin-top: 300px; _/
background-color: #fff;
display: flex;

}
.faq-content {
display: flex;
/_ justify-content: center; _/
/_ align-items: center; _/
}
.section {
display: flex;
/_ flex: 1; _/
width: 40%;
flex-direction: row;
justify-content: center;
align-items: center;
/_ margin-left: 50%; _/
background-image: url('../images/bg-pattern-desktop.svg');
}
.section .img1 {
margin-left: -100px;

}
.section .img {
margin-top: 90px;
margin-left: -100px;
padding-left: 0px;
z-index: 10;

}

.section1 {
/_ display: flex; _/
/_ flex: 1; _/
/_ display: flex; _/
/_ flex-direction: column; _/
width: 60%px;
/_ flex-direction: column; _/
}
.child{
flex-direction: row;
}
