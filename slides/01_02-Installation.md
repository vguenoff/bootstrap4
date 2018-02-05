<!-- .slide: data-state="title" -->
# Bootstrap 4
Installation

> > Speaker Notes:
This version of bootstrap has a lot of different installation options. Let's take a quick look at the different options available.

---

## Installation Options

<ul>
	<li class="fragment">CSS and JS</li>
  <li class="fragment">Bootstrap CDN</li>
	<li class="fragment">Source files</li>
	<li class="fragment">Package managers</li>
</ul>

> > Speaker Notes:

You can install Bootstrap in one of four ways. The first is to simply download the pre-compiled Bootstrap CSS and JavaScript files. That works well if you need to install a copy of bootstrap that will work even without an internet connection.

Another way is to use CDNs. A CDN is a content delivery network, which means a place that hosts common libraries like Bootstrap. When someone visits a site that uses  a CDN link, their browser will check it's cache or memory to see if the visitor has been to a similar site that's also using the same link. If that's the case, then the browser will load the cached version of the library. Since it's already stored in memory, that makes the new site load faster since the browser won't have to request the file.

You can also download the source files. This way, you download not just the css and javascript but all of the files that the developers used to create bootstrap, which includes everything including the original sass files and the documentation. You probably only want to do this if you want to contribute to the project or customize bootstrap. We wont be talking about this option in this course.

The last way is to use a package manager. That means using something like NPM, RubyGems, Composer or NuGet. These are advanced installations that make it easier to work with package managers that help you work with more complex projects.

To get instructions and to download a copy of bootstrap manually, you can go to this URL http://getbootstrap.com

Here we are at the bootstrap website. To look at your installation options, click on this download button right here. If you want to install the CSS and JavaScript to install bootstrap yourself, click on this download link to download the CSS and JavaScript files directly to your computer.

This will place a file in my download folder...which for me is my desktop. If I open that up, I get a folder called Bootstrap, and then the version number.

There is a JS folder as well as a CSS folder. The CSS folder has a number of different versions of the Bootstrap framework.

If you take a look at this folder you'll notice that there are three types of files. There are regular css files and the minified versions. Minified versions are smaller versions of the css with all of the spaces and tabs removed so that the file is smaller.

There are also .map files. Those are files that are useful if you're using Bootstrap in development mode so that they can point you to not css, but the original sass code that was used to create the CSS.

You'll notice three versions of the bootstrap css as well. The bootstrap grid...Some people like to use ONLY the grid features of Bootstrap for layout, so you can get just that. There is also a bootstrap-reboot. The reboot files is the special bootstrap code that resets the CSS in browsers so that they work more consistently in different platforms. Then finally, the regular version of bootstrap. That contains the grid, the reset and everything else.

The one that you want to probably use most of the time is this one right here. This is the compressed and minified version of Bootstrap's CSS. You can put that in your project's css folder.

In the JavaScript folder, you'll find several files as well. JavaScript also has map files since most people write in a version of javascript that gets translated so that it works with older browsers. There are also regular and minified versions of the JavaScript. Other than that, there are two types of files. The regular bootstrap and the bootstrap bundle.

Now you have a good understanding of what you get when you download Bootstrap. There's a couple of other things that you'll need, but we'll cover that and put together a basic Bootstrap Template in the next video.
