# Neumorphism_Buttons
一Neumorphism Buttons design for OpenHarmony.

## Download & Install

Install using npm

```npm i hmos-neumorphism ```
Details about OpenHarmony NPM environment configuration, see at [here](https://gitee.com/openharmony-tpc/docs/blob/master/OpenHarmony_npm_usage.md)

## Usage Instructions
# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    color: black;
}
```

# Button

<img src="sample_images/button.png" width="" height="">

Import:
```html
<element name='neubutton' src='hmos-neumorphism/button/button.hml'></element>
```

Usage:
```html
<neubutton icon="common/icons/heart.png" width="250px" height="60px" border="50px" onclick="buttonClick">
  <text>Button</text>
</neubutton>
```

# Buttons

<img src="sample_images/buttons.png" width="" height="">

Import:
```html
<element name='neubuttons' src='hmos-neumorphism/buttons/buttons.hml'></element>
```

Usage:
```html
<neubuttons  width="250px" height="60px" border="50px">
  <button slot="first">Left</button>
  <button slot="second">Right</button>
</neubuttons>
```

## Compatibility
Supports OpenHarmony API version 6 

## Directory Structure
````
|---- Neumorphism  
|     |---- entry  # sample app usage
|     |---- Neumorphism  # Neumorphism library
|           |---- buttons  # Buttons Component
|                 |---- buttons.css  # Buttons style component
|                 |---- buttons.hml  # Buttons hml file
|                 |---- buttons.js  # Buttons JS
|     |---- README.MD  # installation and usage                   
````
## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://gitee.com/openharmony-sig/Buttons/issues) to us. Of course, we also welcome you to send us [PR](https://gitee.com/openharmony-sig/Buttons/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/Buttons/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
