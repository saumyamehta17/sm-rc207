Railscast sm-rc207
====================

IF want to display code to user, and if want to have pretty awsome syntax..So three popular utilities in rails world.
```
You can use
1. coderay
2. harsh
3. Ultraviolet
4. pygments
Note: speedwise coderay is good one.
and if using caching then all are good.
```
git clone
```
git clone ''
```
steps to follow
```
postgresql server and ruby 2.0 and rails 4 is needed
bundle
rake db:create
rake db:migrate
```
Showing code snippt
```
use raw method
see show.html.erb
```
gemfile
```
coderay -  used to give style to code snippt
RedCloth - used to covert formatting style of simple document into html. see https://github.com/jgarber/redcloth
```
use custom coderay helper for display content
```
see articles/index.html.erb and Application_helper.rb
```
Now create  coderay.css
```
coderay stylesheet > coderay.css
or download it from
https://github.com/ryanb/railscasts-episodes/blob/master/episode-207/blog/public/stylesheets/coderay.css
```
also add coderay into header of application.html.erb
```
#todo
```
Rails server
```
rails s
```
