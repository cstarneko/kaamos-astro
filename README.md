# Kaamos Astro
Highly Search Engine Optimized Starter Blog for Astro

<img src="https://www.kalervoraitanen.com/kaamos/assets/kaamos-ascii.png" alt="Kaamos Astro ASCII logo" />

## [Demo site](https://www.kalervoraitanen.com/kaamos)

Kaamos Astro is designed to give a strong semantic and lightweight foundation to a blog. It is highly Search Engine optimized especially for blogs with Schema.org Microdata. It is meant to be used as a starter blog which you can use to develop your own blog.

Kaamos is minimalistic as possible and has only the essential features of a blog and no unnecessary CSS. However it comes with some CSS files for example a demo theme and some practical styles. You can easily remove these if you want just the bare bones starter blog.

Kaamos is licensed under <a href="http://sam.zoy.org/wtfpl/" title="Link to WTFPL license">WTFPL</a> so you can do what ever you want with it! However you are forbidden to hold me liable for anything, or claim that what you do with this is made by me.

## Some features

- Open Graph Tags (Twitter, Facebook)
- User Declared Canonical URLs
- XML Sitemap
- Robots.txt
- Markdown based blog posts with featured images

## Getting Started

To get started you should have Astro, Node and npm installed. Instructions can be found on <a href="https://docs.astro.build/en/installation/"> Astro's website</a>. After that follow these steps:
```
# Install Dependencies

npm i

# Run Site locally

npm start

# Build Site

npm run build
```

Navigate to `src/data/site.js` and edit to match your site's information.

Start writing new blog posts in Markdown at `src/pages/blog/`

## Activating a demo

Kaamos Astro comes with demo themes to showcase what can be done with just CSS and a touch of Vanilla Javascript. All the demos are also WTFPL licensed so you can use them anyway you want. However you are forbidden to hold me liable for anything if you choose to use them.

Demos so far:
- [Demo #1](https://www.kalervoraitanen.com/kaamos)
- [Demo #2](https://www.kalervoraitanen.com/demo2)
- [Demo #3](https://www.kalervoraitanen.com/demo3)
- [Demo #4](https://www.kalervoraitanen.com/demo4)


Activating a demo is very simple. Below are the instructions how to do it:

1. Open `src/components/blog/BaseHead.astro`.
2. Find the line `<link rel="stylesheet" id='kaamos-demo1-css' href="/style/demo1.css" media='all'/>` and change the 'demo1' to 'demo2' for example.
3. Find the line `<script src='/script/demo1.js?ver=1.0' id='kaamos-demo1-js'></script>` and change the 'demo1' to 'demo2' for example.
4. That's it, you're all set! Start your site locally and see the demo in your browser.

## Credits

Kaamos Astro is also based on:
- astro-minimal-starter by Jaydan Urwin
- https://github.com/necolas/normalize.css

And thanks to Tony-Sull of Astro Support Squad for some coding help!