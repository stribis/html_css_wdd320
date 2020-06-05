# HTML CSS - Lesson Material
#### :computer: Web Design & Development 320
#### :school: SAE Institute Zürich
#### :pencil2: Author: Martin Hutchings - Head Instructor

###### THIS IS DOES NOT REPRESENT EVERYTHING WE DID DURING THE LESSON, ONLY THE PRACTICAL EXERCISES!
---

### :one: Week 1: :one:
### :file_folder: [`week_01`](https://github.com/stribis/html_css_wdd320/tree/master/week_01)
#### HTML & CSS Basics

* Building Blocks
  * Using the code editor for an efficient workflow,
  * :file_folder: [`01_building_blocks`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/01_starting_blocks)
* HTML Tags
  * Learning about different HTML Elements
  * :file_folder: [`02_tags`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/02_tags)
* CSS Linking
  * The 3 methods of using CSS in HTML
  * :file_folder: [`03_css_linking`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/03_css_linking)
* Reset Style
  * Removing the standard browser styles
  * :file_folder: [`04_reset_style`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/04_reset_style)
* CSS Selectors
  * Learning and implementing the different CSS selectors available
  * :file_folder: [`05_css_selectors`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/05_css_selectors)

--- 

### :two: Week 2: :two:
### :file_folder: [`week_02`](https://github.com/stribis/html_css_wdd320/tree/master/week_02)
#### HTML & CSS Basics

* Units
  * Revised the different units
    * `px` ( the smallest possible point in a screen )
    * `vw / vh` ( Relative to the viewport )
    * `em` ( Relative to font size of the parent)
    * `rem` ( Font size of the root element )
  * :file_folder: [`01_units`](https://github.com/stribis/html_css_wdd320/tree/master/week_02/01_units)
* `block` vs `inline` vs `inline-block`
  * Learning about difference between the `display` properties
  * :file_folder: [`02_blockVSinline`](https://github.com/stribis/html_css_wdd320/tree/master/week_02/02_blockVSinline)
* Float & Clear
  * Basic layouts with float and clear
    * We continued working with the example from last week
  * :file_folder: [`01_building_blocks`](https://github.com/stribis/html_css_wdd320/tree/master/week_01/01_starting_blocks)
* Positioning
  * Reviewed the position property and 4 different values
    * `position: static`
    * `position: relative`
    * `position: absolute`
    * `position: fixed`
  * :file_folder: [`03_positioning`](https://github.com/stribis/html_css_wdd320/tree/master/week_02/03_positioning)
* Flex Basics
  * Played around with a container and the different flex properties
    * `display: flex`
    * `justify-content`
    * `align-items`
    * `flex-direction`
    * and more ...
  * :file_folder: [`04_flex_basics`](https://github.com/stribis/html_css_wdd320/tree/master/week_02/04_flex_basics)
* Basic Flex Layout
  * Created a simple layout using Flex
    * Very similar to week_01/01_starting_blocks but with flex
  * :file_folder: [`05_flex_layout_basic`](https://github.com/stribis/html_css_wdd320/tree/master/week_02/05_flex_layout_basic)

--- 

### :three: Week 3: :three:
### :file_folder: [`week_03`](https://github.com/stribis/html_css_wdd320/tree/master/week_03)
#### HTML & CSS Basics

* PopQuiz
  * We tested our knowledge of Flex as a layout tool
    * Created a simple website using flex for layout
    * We tried to not define `width` our `height` if not necessary
      * Instead use `padding` to use the size of the content and add to it
  * :file_folder: [`01_pop_quiz`](https://github.com/stribis/html_css_wdd320/tree/master/week_03/01_pop_quiz)
* Centering: `transform : translate()` and `margin: 0 auto`
  * Learned more techniques for centering elements 
  * :file_folder: [`02_transform_translate`](https://github.com/stribis/html_css_wdd320/tree/master/week_03/02_transform_translate)
* Gradients
  * We reviewed the syntax for `background-image: linear-gradient()`
    * `simple.html` is the first part
    * `index.html` and `style.css` are for the exercise where we had to create flags
      * **Try to create recreate the last 3 flags without looking at the code**
  * :file_folder: [`03_gradients`](https://github.com/stribis/html_css_wdd320/tree/master/week_03/03_gradients)
* Positioning
  * Reviewed the position property and 4 different values
    * `position: static`
    * `position: relative`
    * `position: absolute`
    * `position: fixed`
  * :file_folder: [`03_positioning`](https://github.com/stribis/html_css_wdd320/tree/master/week_03/03_positioning)
* Fonts & Font icons
  * Checked out webfonts (like google fonts) with `@import` & `<link>` 
  * Learned how to like font files from your project directory
    * First `@font-face` to define the font name and path
    * Then `font-family` to use the font !
    * Linked a font-icon from https://fontawesome.com/
      * Remember to have the correct `<link>` path
      * Remember to have the correct `class` in your element!
  * :file_folder: [`04_fonts`](https://github.com/stribis/html_css_wdd320/tree/master/week_03/04_fonts)

  ---
### :four: Week 4: :four:
### :file_folder: [`week_04`](https://github.com/stribis/html_css_wdd320/tree/master/week_04)
#### HTML & CSS Basics

* Box Shadow Homework
  * Using box shadow to create special effects
    * Remember the syntax `box-shadow: color xPosition yPosition blur spread`
      * More info here : https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow
  * :file_folder: [`01_box_shadow`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/01_box_shadow)
* Stack of images
  * Using box shadow to create special effects
    * Remember the syntax `box-shadow: color xPosition yPosition blur spread`
      * More info here : https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow
  * :file_folder: [`02_bilderstapel`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/02_bilderstapel)
* CSS Sprites
  * Using background-image to implement sprites
    * A sprite file is basically an image with multiple images inside it
    * Using background position we can move the image around to define which part of the image is shown
      * More info here : https://www.w3schools.com/css/css_image_sprites.asp
  * :file_folder: [`03_css_sprites`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/03_css_sprites)
* Form Basics
  * The HTML involved in creating forms
    * Remember to always have a `label` for your `input`s, link them together using `for=""` and `id=""`
      * More info here : https://www.w3schools.com/tags/tag_label.asp
  * :file_folder: [`04_forms_basics`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/04_forms_basics)
* Form with CSS
  * The CSS involved in creating forms
    * :file_folder: [`05_forms_styled`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/05_forms_styled)
* Layout Exercise (ONLY HTML)
  * We went through identifying and setting the correct HTML elements needed for a specific layout
  * Here is the layout we were trying to recreate: https://cdn.discordapp.com/attachments/689086496208191671/714862960853516288/D__sae_320_02_html_css_examples_hazbin_flex.html.png
    * Additionally you need the following infomation
      * You need the images (In the images folder)
      * The fonts are :
      ```css
      @import url('https://fonts.googleapis.com/css?family=Quicksand&display=swap');
      @import url('https://fonts.googleapis.com/css?family=Indie+Flower&display=swap');
      ```
      * The colors you will need are:
      ```
        --pri-color: #000;
        --sec-color: #ff4069;
        --ter-color: #ffd171;
        --ter-dark-color: #fda742;
        --qua-color: #fff;
      ```
      * We will discuss the finished example next time
  * :file_folder: [`06_hazbin_layout_nur_html`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/06_hazbin_layout_nur_html)
* Layout Exercise (Complete)
  * Use this if you want to compare your work with mine. 
    * Remember there are multiple solutions to one problem!
  * :file_folder: [`07_hazbin_layout_complete`](https://github.com/stribis/html_css_wdd320/tree/master/week_04/07_hazbin_layout_complete)


  ---
### :five: Week 5: :five:
### :file_folder: [`week_05`](https://github.com/stribis/html_css_wdd320/tree/master/week_05)
#### HTML & CSS Basics

* Dummie Exam - Solution
  * :file_folder: [`01_probe_test`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/01_probe_test)
* Test Your Knowledge Exercise with solutions
  * :file_folder: [`02_testYourKnowledge`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/02_testYourKnowledge)
* HTML Tables
  * Elements for HTML Tables:
    1. Simple styled table
    2. Table with col/row span
    3. Table puzzle with odd / even
      * More info here : https://www.w3schools.com/html/html_tables.asp
  * :file_folder: [`03_tables`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/03_tables)
* Iframes
  * How do iframes work and how to implement them
    * More info here : https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe
  * :file_folder: [`04_iframe`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/04_iframe)
* Dropdown Navigation with CSS hover
  * The CSS and HTML involved in creating a dropdown navigation
    * :file_folder: [`05_dropdown_nav`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/05_dropdown_nav)
* Layout Exercise: Freelancer (ONLY HTML)
  * We went through identifying and setting the correct HTML elements needed for a specific layout
  * Here is the layout we were trying to recreate: https://startbootstrap.com/previews/freelancer/
    * We will discuss the finished example next time
  * :file_folder: [`06_layout_freelancer_html_only`](https://github.com/stribis/html_css_wdd320/tree/master/week_05/06_layout_freelancer_html_only)
