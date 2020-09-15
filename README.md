
# Introduction
#### What is **PageScroll** ?
PageScroll is a lightweight library for fullpage scrolling. With PageScroll you can create beautiful landing pages with its own charm✨.

#### Demo

[![PageScroll-1.gif](https://s1.gifyu.com/images/PageScroll-1.gif)](https://gifyu.com/image/4mZV)

# Usage

To start your work with PageScroll you will need a couple of files: 
* CSS file `pagescroll.css`
* JavaScript file `pagescroll.js`

#### Install

Copy `pagescroll.css` and `pagescroll.js` from github repository.
You will need to import them in your project as well.

```html
<!-- Importing CSS file -->
<link rel="stylesheet" href="pagescroll.css">

<!-- Importing JS file -->
<script type="text/javascript" src="pagescroll.js"></script>
```

#### HTML structure requirements
In terms of use PageScroll you will heed to have this structure of your HTML file.

```html
<div id="pagescroll">
    <div class="section"></div>
    <div class="section"></div>
    <div class="section"></div>
    <div class="section"></div>
    <div class="section"></div>
</div>
```

`pagescroll` is your root element while `section`s are the pages that will appear as you scroll.

The class `section` of slide is strongly required.

#### Initialization

You can init PageScroll just after you import it to your project.
```html
<script type="text/javascript" src="pagescroll.js"></script>
<script>
    new PageScroll('#pagescroll', {
        // Options goes here
    })
</script>  
```

#### Customise

Options that available in this version:

|Option|Description|
|--- |--- |
|animDuration| Controls the duration of changing the scene. _Default `300ms`_|
|easing| Controls the easing of animation. _Default `linear`_|

**Examples**

```javascript
new PageScroll('#pagescroll', {
    animDuration: 2000, // 2 seconds
    easing: 'cubic-bezier(.17,.67,.83,.67)' //animation easing
})
```

# License

PageScroll is completely free. You can use it in any way you want.

# My social media

[Instagram](https://www.instagram.com/maksym.shv/)
[Telegram](https://telegram.me/beastmode23)