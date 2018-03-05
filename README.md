# Blaze-UI

----
## What is Blaze-UI

>Blaze-UI is a light-weight structural framework with plenty of helpers and components to quickly structure your next application. My goal was to create something that not only would I want to use, but would be easy to remember, learn and build on top of. Other frameworks take a lot of back-and-forth between the documentation and developing; I'm confident that with Blaze-UI that won't be the case. Do things yourself; I encourage using this as a structure, so build upon it. No two sites should look the same when using this.
>
> Before we begin; this is not meant to be a replacement for frameworks like Bootstrap, Semantic, Foundation, etc. I wanted to create this for structure, but that seemed to plain. So, I've included some useful helpers and components to get your project off the ground quickly and easily.


----
## Usage
1. Blaze-UI is great for any project.
2. This framework is incredibly easy to use.
3. Excellent CSS and JS Components & Helpers.

----
## Change-log
* March-3-2018 (Initial Commit)

----
## What's Used
* [SASS](#)
* [JavaScript](#)

----


# Documentation
## Navigation

   **Regular Navbar:**

      <nav id="nav">
        <a href="" class="brand">Brand</a>
        <ul class="left">
          <a href=""><li>ItemOne</li></a>
          <a href=""><li>ItemTwo</li></a>
          <a href=""><li>ItemThree</li></a>
        </ul>
        <ul class="right">
          <a href=""><li>ItemFour</li></a>
          <a href=""><li>ItemFive</li></a>
        </ul>
      </nav>

**Left Navbar:**

      <nav id="left-nav">
        <a href="#" class="brand">Brand</a>
        <ul>
          <a href=""><li>ItemOne</li></a>
          <a href=""><li>ItemTwo</li></a>
          <a href=""><li>ItemThree</li></a>
        </ul>
      </nav>

**Navbar w/ Logo:**

    <nav id="nav">
	   	<a href="" class="brand-img">
	   		<img src="logo.jpg">
	   	</a>
	   	<ul class="right">
	       <a href=""><li>ItemOne</li></a>
	       <a href=""><li>ItemTwo</li></a>
	       <a href=""><li>ItemThree</li></a>
       </ul>
     </nav>



----------


## Buttons

    <a href="" class="btn"></a> -- Standard Button
    <a href="" class="btn success"></a> -- Button w/ Success Color
    <a href="" class="btn failure-inverse"></a> -- Button w/ Failure-Inverse Color
    <a href="" class="btn-lg warning"></a> -- Large Button w/ Warning Color



----------


## Section-hr

    <hr class="section-hr">



----------


## Cover-Loader

    <div id="cover"><div class="loader"></div> Loading...</div>



----------


## Cards

    <div class="card">
      <h3>Title</h3>
      <span>Created: March 3rd, 2018</span>
      <p>Content Description</p>
    </div>
**Card w/ Image:**

    <div class="card-img">
      <div class="img">
        <img src="img.jpg" alt="">
        <span>Title</span>
      </div>
      <div class="body">
        <h6>User</h6>
        <span>Created: March 5th, 2018</span>
        <p>Content Description</p>
      </div>
    </div>
**Card w/ Toggle:**

    <div class="card togglable">
      <h3>Lorem ipsum dolor.</h3>
      <span>Created: March 2nd, 2018</span>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora nihil obcaecati eaque possimus ad? Corrupti!</p>
      <div class="toggle warning plus"></div>
    </div>
**Card Grid:**

    <div class="card-grid">
        <div class="card-img">
          <div class="img">
            <img src="img.jpg" alt="">
            <span>Lorem ipsum dolor sit.</span>
          </div>
          <div class="body">
            <h6>Lorem ipsum dolor sit.</h6>
            <span>Created: March 5th, 2018</span>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis dicta sapiente at doloremque facilis ipsa nemo distinctio incidunt.</p>
          </div>
        </div>

        <div class="card-img">
          <div class="img">
            <img src="img.jpg" alt="">
            <span>Lorem ipsum dolor sit.</span>
          </div>
          <div class="body">
            <h6>Lorem ipsum.</h6>
            <span>Created: March 5th, 2018</span>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis dicta sapiente at doloremque facilis ipsa nemo distinctio incidunt.</p>
          </div>
        </div>
    </div>


----------
## Hero

    <section id="hero">
      <p class="hero-text visible-text text-center">
        Hero Text
      </p>
    </section>

    <section id="hero">
      <p class="hero-text visible-text contained">
        Hero Text
      </p>
    </section>

**Medium Hero:**

    <section id="hero" class="medium">
      <p class="hero-text visible-text text-center">
        Hero Text
      </p>
    </section>
**Small Hero:**

    <section id="hero" class="small">
      <p class="hero-text visible-text text-center">
        Hero Text
      </p>
    </section>



----------
## Colors

 - success | success-inverse
 - failure | failure-inverse
 - info | info-inverse
 - warning | warning-inverse


----------
## Grid
>Highly Recommended That You Do NOT Use This. Create Your Own with CSS Grid. (This is using flex-box)

    <div class="flex-grid">
      <div class="col">
        <h5>I'm Column One!</h5>
      </div>
      <div class="col">
        <h5>I'm Column Two!</h5>
      </div>
      <div class="col">
        <h5>I'm Column Three!</h5>
      </div>
     <div class="col">
       <h5>I'm Column Four!</h5>
     </div>
    </div>

    <div class="flex-grid-thirds"> -- Uses: justify-content: space-between; & .col = 32%;
	     <div class="col">
	       <h5>I'm Column One!</h5>
	     </div>
	     <div class="col">
	       <h5>I'm Column Two!</h5>
	     </div>
	     <div class="col">
	       <h5>I'm Column Three!</h5>
	     </div>
     </div>

----------

## Helpers


    <div class="container"></div> -- 70% Width | 0 Auto Margin

    <!-- Display Properties -->
    <div class="inline"></div> -- Element inline
    <div class="inline-child"></div> -- All Child Elements Are inline
    <div class="inline-block"></div> -- Element inline-block
    <div class="block"></div> -- Element block
    <!-- End Display Properties -->

    <!-- Margins 15px, 25px, 50px -->
    <div class="m-50"></div> -- All Margin 50px
    <div class="mt-25"></div> -- Margin Top 25px
    <div class="mb-15"></div> -- Margin Bottom 15px
    etc..
	<!-- End Margins -->

    <p class="lead"></p> -- Prominent Text
	<a class="classic"></a> -- Underline text
	<div class="no-effects"></div> -- Removes Effects given by Blaze-UI
	<div class="no-border-effect"></div> -- Removes Border Radius
	<div class="no-box-effect"></div> -- Removes Box Shadow
	<div class="fixed"></div> -- Element Position Fixed
	<div class="float-right"></div> -- Element Floated Right
	<div class="float-left"></div> -- Element Floated Left
	<ul class="bulleted"></ul> -- Bulleted Unordered List
	<p class="visible-text"></p> -- Opac Black Background to Make Text Visible on Any Background  
	<div class="text-center"></div> -- Text aligned-center
    <div class="description"></div> -- Description area for text.
    <div class="contained"></div> -- Width of Element fits Width of Content
