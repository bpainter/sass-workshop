* Files to create
  * Existing project example
  * New project example
  * Gist where folks can add their questions
  * A couple of examples for each feature
  * Susy
  * Mixin vs Extend

* Intro
  * Preprocessors
  * Ruby & Gems
  * Install
    * Command Line
      * gem install sass
      * sudo gem install sass
    * Windows http://rubyinstaller.org/
    * GUI
      * Compass App
      * Scout
      * Codekit
  * Get Started
    * Existing Project
      * mkdir 'sass'
      * mv stylesheets/base.css sass/base.scss
      * manually move and change the file extension
    * New Project
      * cd ~/Sites
      * make a project folder
      * create a 'stylesheets' and 'sass' folder
      * create a .scss file in 'sass'
      * sass --watch sass:stylesheets
  * Compiling
    * Methods of compiling
      * locally
      * on deploy
      * server side
    * Output Options
      * sass --watch sass:stylesheets --style <option>
      * :nested
      * :expanded
      * :compact
      * :compressed
    * GUI/Livereload
    * Compass
  * Debugging
    * Sleuth
    * http://www.mobify.com/dev/sass-sleuth-debugging-sass-in-webkit-browsers/
    * In your config
    * if environment != :production
        sass_options = {:debuginfo => true}
      end
    * sass --watch sass:stylesheets -l
* Beginner
  * Nesting
    * http://codepen.io/bpainter/pen/lhumn
  * Variables
  * @import
  * Reference Selector

* Intermediate
  * Mixins
  * @extend
  * Silent Class

* Advanced
  * Math Operators
  * Logic
  * Functions
  * Color Functions
  * Media Queries
  * Interpolation
  * Each
  * Complex Mixins with Logic

* Compass
  * CSS3 Mixins
  * Sprites

* Misc Examples
  * Font Library
  * Grids