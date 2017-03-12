# know-it-nl.github.io

## You need
- http://livereload.com/
- A browser
- A keyboard

## Sass?
Sass (http://sass-lang.com/) is an awesome way to help you write CSS with superpowers. It's main features are described on http://sass-lang.com/guide.

We're using the original Sass syntax because we don't like writing {} and ; all day long.

## Sass compiling through LiveReload
Livereload is an awesome tool that watches your files and reloads your browser when your HTML / CSS / JS has changed. This saves a lot of manual reloading.

Install livereload

Check the [compile SASS, LESS, ...] checkmark
![LiveReload screenshot](https://know-it-nl.github.io/images/README/livereload1.png)

Click [Options...] for the compile section
![LiveReload screenshot](https://know-it-nl.github.io/images/README/livereload2.png)

Copy the settings in both tabs
![LiveReload screenshot](https://know-it-nl.github.io/images/README/livereload3.png)

## CSS SETUP
`/base/` has all the structure for the CSS, like layout, typography,
`/components/` has all the components, these are small parts of the interface you want to reuse within modules
`/modules/` has all the modules, bigger blocks of your page such as the navigation, member page, etc.

`.l-` prefix for layout classes
`.c-` prefix for components
`.m-` prefix for modules

This combination makes it "safe" to use classes for modifiers or elements within a component / module.

## REM Units?
https://www.sitepoint.com/understanding-and-using-rem-units-in-css/
