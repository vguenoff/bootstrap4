<!-- .slide: data-state="title" -->
# Bootstrap 4
Input Groups

> > Speaker Notes:
We've already looked at how to turn form elements into inline elements. There's a variation of this called input groups  that allow you to put form elements in a horizontal layout with an integrated look. Let's check it out.
---
<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-check-square-o"></i> Input Group

<ul>
  <li class="fragment">`input-group`</li>
  <li class="fragment">`input-group-prepend` `input-group-append`</li>
  <li class="fragment">`input-group-text`</li>
  <li class="fragment">`aria-label` `sr-only`</li>
</ul>

> > Speaker Notes:
1. The main class for these elements is called input-group and you can put them on form elements or inside input fields.
1. You can add input groups in two places, either before an input field or after and you used these two classes to take care of that.
1. Inside that, you create an input-group-text class and then add whatever you want inside. It can be text, buttons, checkboxes etc.
1. If you do add checkboxes, they each require their own labels, so you can either use the aria label attribute or the sr-only class on a label


## Conclusion
Input groups are a pretty handy style that let's you make very concise fields for elements like search or add a bit of pizzaz to your existing forms.
