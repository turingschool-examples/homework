## Week 1

##### Ongoing
  * Reverse-engineer one of your favorite websites to practice your HTML/CSS skills.
  * [CSS Zen Garden](http://www.csszengarden.com/)
  * Experiment with [Bootstrap](http://getbootstrap.com/). 

##### Day 1
  * Finish styling TaskManager using Bootstrap `layout.erb`, `index.erb`, `show.erb`, `new.erb`, and `dashboard.erb`
  * Research: What is CRUD (in the programming sense of the word)? What CRUD functionality do we have in TaskManager already and what are we missing? What routes/views/methods would we need to add in order to have full CRUD functionality?

##### Day 2
  * CRUD either Skill Inventory or Robot World. Instructions are at the bottom of [this file](https://github.com/turingschool/lesson_plans/blob/master/ruby_02-web_applications_with_ruby/crud_sinatra.markdown).

##### Day 3
  * Continue working on Skill Inventory or Robot World. Add model and feature tests using Capybara that hit the routes in your controller. Timebox this to <= 2 hours.
  * Work through the [Fundamental SQL](http://tutorials.jumpstartlab.com/topics/sql/fundamental_sql.html) tutorial in preparation for tomorrow. This should take approximately 40 minutes. Come with questions for Mike. 

##### Day 4
  * Transform Skill Inventory or Robot World to use Sequel & Sqlite3. You'll continue working on this over the weekend. Submit the link to your repo [here](https://github.com/turingschool/ruby-submissions/blob/master/1510/task_manager_transformation.yml) no later than Sunday at 8pm.
  * [Watch Sharif Ramadan's intro to 1NF, 2NF and 3NF databases. They're only about 4 minutes each.](https://www.youtube.com/watch?v=K7vzLrGCV50&list=PLQ9AAKW8HuJ5m0rmHKL88ZyjOIKejvrj0) intro to datbase normalization video. 
  * Suggested reading about database normailization:
    *  [DevShed - An Introduction to Database Normalization](http://www.devshed.com/c/a/mysql/an-introduction-to-database-normalization/)
    *  [Mike Hillyer's Blog Post - intro to database normalization](http://mikehillyer.com/articles/an-introduction-to-database-normalization/)
  

##### Day 5 & Weekend
  * Continue transforming Skill Inventory or Robot World to use Sequel & Sqlite3.
  * Suggested: Read the [Learn SQL the Hard Way](http://sql.learncodethehardway.org/book/) book. 

## Week 2

##### Day 1
  * [ActiveRecord Practice and Set Up TrafficSpy](https://github.com/turingschool/challenges/blob/master/active_record_and_database_design.markdown)

##### Day 2
  * Continue working on Traffic Spy

##### Day 3
  * Continue working on Traffic Spy

##### Day 4 & Weekend
  * Continue working on Traffic Spy

## Week 3

##### Day 1
  * Complete the [routes and controllers](https://github.com/turingschool/challenges/blob/master/routes_controllers_rails.markdown) homework. 

##### Day 2
  * [Form and Route Helpers](https://github.com/turingschool/challenges/blob/master/form_route_helpers_rails.markdown)

##### Day 3
  * Continue working on [Blogger](http://tutorials.jumpstartlab.com/projects/blogger.html)

##### Day 4
  * [Contact Manager](http://tutorials.jumpstartlab.com/projects/contact_manager.html)
  * Submit your Contact Manager repo and sha of the commit for the checkpoint that's due to [this repo](https://github.com/turingschool/ruby-submissions/blob/master/1508/contact_manager.yml). 
  * Alternatively, you may be doing [MixMaster](https://github.com/turingschool/lesson_plans/blob/master/ruby_02-web_applications_with_ruby/mix_master.markdown) instead. 

##### Day 5 & Weekend
  * [Contact Manager](http://tutorials.jumpstartlab.com/projects/contact_manager.html)

## Week 4

##### Day 1
  * Store the id of the last song added to MyJams in the session with a key of `:most_recent_song_id`.
  * Add a method to your `ApplicationController` called `most_recent_song` that loads the most recent song using `:most_recent_song_id` stored in the session. (Hint: use `Song.find...`)
  * Make that new method available to your views by making it a [helper method](http://apidock.com/rails/AbstractController/Helpers/ClassMethods/helper_method).
  * Add this snippet to `application.html.erb`:
  
 ```erb
 <p>
   <strong>Newest song:</strong> <%= most_recent_song.title %>
 </p>
 ```
  * Similar to your existing `flash[:errors]` that you set in the SongsController, implement a `flash[:notice]` in MyJams when you successfully create a song.
  * Remove any existing `flash`es in your views and replace them with a dynamic content generator. Take a look at 20:33 in the [Sessions, Cookies, and Flashes](https://vimeo.com/130058574) video for a refresher on how to do this.
  * Watch [this video on authentication](https://vimeo.com/134451454) in preparation for tomorrow's class. Prepare questions for class tomorrow and be ready for a code-along in the morning. 

##### Day 2
  * Authentication in MyJams

##### Day 3
  * Authorization in MyJams

##### Day 4
  * [Rails Mini-Project](https://github.com/turingschool/challenges/blob/master/rails-mini-project.markdown)

##### Day 5 & Weekend
  * [Rails Mini-Project](https://github.com/turingschool/challenges/blob/master/rails-mini-project.markdown)

## Week 5

##### Day 1
  * Start implementing the cart and order lifecycle in [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html)

##### Day 2
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html): refactor your views 

##### Day 3
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html):  make your controllers skinny

##### Day 4
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html): make sure that your app works on Heroku

##### Day 5 & Weekend
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html)

## Week 6

##### Day 1
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html)

##### Day 2
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html): implement category and order filtering with jQuery

##### Day 3
  * [Dinner Dash](http://tutorials.jumpstartlab.com/projects/dinner_dash.html)

##### Day 4
  * Demo night!

##### Day 5 & Weekend
  * Enjoy your intermission week! 
