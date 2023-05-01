# WebSlides = Customized Breadcrumbs 


* * *
### What's in the download?


```
webslides/
├── index.html
├── css/
│   ├── base.css
│   └── colors.css
│   └── svg-icons.css (optional)
├── js/
│   ├── webslides.js
│   └── svg-icons.js (optional)
└── images/
```

## How to run?
- Clone the Repo and run the index.html in your browser

## Features

- Navigation (horizontal and vertical sliding): remote presenters, touchpad, keyboard shortcuts, and swipe.
- Updating Beadcrumbs on scroll

## Markup

- Code is clean and scalable. It uses intuitive markup with popular naming conventions. There's no need to overuse classes or nesting.
- Each parent `<section>` in the `#webslides` element is an individual slide.

```html
<article id="webslides">
    <section>
        <h1>Slide 1</h1>
    </section>
    <section class="bg-black aligncenter">
    <!-- .wrap = container 1200px -->
        <div class="wrap">
            <h1>Slide 2</h1>
        </div>
    </section>
</article>
```

### Vertical Sliding

```html
<article id="webslides" class="vertical">
```

for more details please check https://webslides.tv/



 
