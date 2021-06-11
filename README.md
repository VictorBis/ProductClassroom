# ProductClassroom

### Welcome to Product Classroom!
We are a virtual community made by students for students to self-learn product design!

![Product Classroom](img/SN-Thumbnail/Thumbnail.png)

## Design
Design done in [Figma](https://www.figma.com/file/j8x4p6uX4MpyxLZYfbhKoU/WebDev?node-id=116%3A2).

## Organization
All the elemets that are in the website are organized in the following folders:
- [css](#css) - SCSS files used in the website
- **js** - JS files used in the website
- **img** - Images contained in the website
- **doc** - Curriculums PDF's and documentation about how to use the CSS files
- **favicon** - Contains all the icons that are needed to show a favicon in the different browsers

***
## CSS
### Colors
All the colors in the website are defined in the [_colors.scss](https://github.com/VictorBis/ProductClassroom/blob/main/css/_colors.scss) file. By changing the value of one of them, the color will be updated automatically in the whole website.
<details>
    <summary>Defined colors</summary>

```css
$yellow: #f9c449;
$orange: #fc8746;
$red: #fd624d;
$pink: #ef91bf;
$purple: #b461a2;
$darkpurple: #7758a3;
$lightblue: #b0d8f0;
$blue: #5bbfeb;
$darkblue: #497ebf;
$lightgreen: #9ce9d4;
$green: #65d6b6;
$darkgreen: #0bba85;
$black: #000000;
$white: #ffffff;
```
</details>

### Typography
All the sizes and styles of the typography in the website are defined in the [_typography.scss](https://github.com/VictorBis/ProductClassroom/blob/main/css/_typography.scss) file. The styles are defined as classes, and need to be defined in the HTML to be applied.
<details>
<summary>Example</summary>

```html
<p class="medium-19">This is a paragraph with font size 19 and medium weight.</p>
```
</details>

