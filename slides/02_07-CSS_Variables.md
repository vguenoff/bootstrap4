<!-- .slide: data-state="title" -->
# Bootstrap 4
CSS Variables

> > Speaker Notes:
Bootstrap has some really useful classes that help you deal with images, so let's take a look.

---

<!-- .slide: data-state="hasicon" -->

## Variables

- New feature in CSS
- Browser compatibility
- `var()` and `:root`
- Doesn't change existing


> > Speaker Notes:

CSS Variables are a newer feature within CSS that allows you to store a set of property values that you can reuse within your templates. This version of Bootstrap provides pre-written CSS variables that can be useful in developing your projects and customizing your colors.

CSS variables are so new that browser support is an issue, they are not supported in any version of Internet Explorer and only on very new versions of the other browsers. Make sure you check this URL for browser support information so you can make a decision as to wether or not you should be using this feature. https://caniuse.com/#search=variables

To use the variables, you have to use the var() function and then use the name of the variable. You can also use the :root selector to redefine the default values for any of the variables. When you do this, make sure that you put your CSS rules after you load the bootstrap css.

You should note that using these variables doesn't change the colors of existing bootstrap classes since those are hard coded into the CSS, but serves as a way to create new elements based on those colors, breakpoints and default fonts.

---

<!-- .slide: data-state="hasicon" -->

## Variables

- Color/Contextual Variables<br>
<small style="text-align:left">
`--blue` `--indigo` `--purple` `--pink` `--red`<br>
`--orange` `--yellow` `--green` `--teal` `--cyan`<br>
`--white` `--gray` `--gray-dark` `--light` `--dark`<br>
`--primary` `--secondary` `--success`<br>
`--info` `--warning` `--danger`</small>

- Media Queries<br>
<small style="text-align:left">
`--breakpoint-xs` `--breakpoint-sm` `--breakpoint-md`,<br>
`--breakpoint-lg` `--breakpoint-xl`</small>

- Fonts<br>
<small style="text-align:left">
`--font-family-sans-serif` `--font-family-monospace`</small>


> > Speaker Notes:

The variables we get are first a group of color variables that match the variables you see used throughout bootstrap, as well as contextual color variables like primary, secondary, etc.

There are also a set of pre-defined media query variables that correspond to how the bootstrap grid works. Those can be useful because they make writing your own media queries based on the existing sizes available in bootstrap.

Finally, there's a couple of font variables that you can use when you quickly want to use Bootstrap's default fonts.

    :root {
      --danger: #FFBA00;
      --pink: #C4226F;
    }

  class="bg-danger text-white" style="background: var(--danger) !important;

## Conclusion

I like this feature, but it's clearly something that you should only use if you think that you have browser support.
