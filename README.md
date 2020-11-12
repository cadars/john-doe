Demo: https://john-doe.neocities.org/

A website in a single HTML file. It simply uses the `#anchor` suffix and the `:target` CSS selector to show and hide pages/content. This setup is databaseless, javascriptless, and buildshit-free, so you can edit your website with a text editor and upload it somewhere like a normal person.

To create a new page, add a `<section>` with a unique `id`
```html
<section id="contact">
   Contact me!
</section>
```
Then you could add a link to it inside `<nav>`
```html
<a href="#contact">Contact</a>
```
