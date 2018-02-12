<!-- .slide: data-state="title" -->
# Bootstrap 4
Special Form Styles

> > Speaker Notes:
There's a few classes that let you control the size of form elements.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-check-square-o"></i> Form Styles

<ul>
  <li class="fragment">`form-control(-sm)(-lg)`</li>
  <li class="fragment">`readonly` `form-control-plaintext`</li>
  <li class="fragment">`form-inline` `form-check-inline`</li>
  <li class="fragment">`col-form-label(-sm)(-lg)`</li>
</ul>

> > Speaker Notes:
1. The form controls can be two additional sizes, to make them smaller, add the form-control-sm class, bigger -lg in addition to their regular form-control classes.
1. In the same way, labels have their own sizing classes
1. There are a couple of ways of displaying an input field, but not allowing users to modify them. You can add a readonly attribute to an input field. This isn't a bootstrap feature, but an HTML feature, it's just that bootstrap has a nice display for it. The other is to use form-control-plaintext, which shows the input field as regular text.
1. Although it's a bit less useful, you can use the form-control-file class for those types of form controls.
1. If you need to make a label and a field appear side by side, then use the form-inline class on the form group. There is an optional version for checkboxes called form-check-inline


## Conclusion
There's just a few styles that you can use to enhance your forms with sizes and special styles for inline elements.
