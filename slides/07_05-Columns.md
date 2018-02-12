<!-- .slide: data-state="title" -->
# Bootstrap 4
Forms in Columns

> > Speaker Notes:
Bootstrap helps you lay out forms using the column grid. There's a few classes you should know about, so let's take a look.
---
<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-check-square-o"></i> Form Columns

<ul>
  <li class="fragment">Use `row` `col`</li>
  <li class="fragment">needs `form-row` `col-auto`</li>
	<li class="fragment">`col-form-label`</li>
</ul>

> > Speaker Notes:
1. To create multi-column forms, you can use the regular column classes like row and col as well as the grid to define where the breakpoints happen for the grid.
2. There are some special classes you can use for forms like the form-row class which gives you a better spacing between columns in forms, since the typical spacing between columns is a little large at 32pixels. You can also use the col-auto class when you want the fields to automatically adjust to the size of the content instead of having to hard code a specific column grid number.
3. If you are going to use the code for multiple columns, make sure that you 

## Demo

```
  <fieldset class="form-group">
    <legend>Owner Info</legend>

    <div class="form-group row">
      <label class="form-control-label col-md-2 text-md-right col-form-label" for="ownername">Owner</label>
      <div class="col-md-10">
        <input class="form-control" type="text" id="ownername" placeholder="Your Name">
      </div>
    </div><!-- form-group -->

    <div class="form-group row">
      <label class="form-control-label text-md-right  col-md-2" for="owneremail">Address</label>
      <div class="col-md-10">   
        <input class="form-control" type="text" id="owneremail" placeholder="Address">
      </div>
    </div><!-- form-group -->

    <div class="form-group row">
      <div class="form-group offset-md-2 col-6">
        <label class="form-control-label sr-only" for="ownercity">City</label>
        <input class="form-control" type="text" id="ownercity" placeholder="City">
      </div><!-- form-group -->

      <div class="form-group col-4">
        <label class="form-control-label sr-only" for="ownerzip">Zip</label>
       <input class="form-control" type="text" id="ownerzip" placeholder="Zip">
      </div><!-- form-group -->
    </div><!-- form-group -->

    <div class="form-group row">
      <div class="offset-md-2 col-md-10">
        <button class="btn btn-primary" type="submit">Submit</button>
      </div>
    </div>

  </fieldset><!-- fieldset -->
</form>
```

## Conclusion
Columns help make the forms easier to read as well as make it easier for you to lay out groups of input fields.
