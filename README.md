# laravel-backend-dev-task

<h1>Task:</h1>

<li>Create simple blog application according to described business logic.</li>
<li>Create your repo (preferablly on Github) for laravel-backend-dev-task solution and share it us.</li>
<li>Deploy your application to <a href="https://www.heroku.com">Heroku</a> and share its public link in project README</li>

<h2>Requirements:</h2>
<li>Use Laravel 9</li>
<li>Use OOP</li>
<li>Follow best practices SOLID, Clean code etc.</li>
<li>Data storage solution is up to you.</li>

<h3>Optionally you can also use:</h3>
<li><a href="https://github.com/laravel/breeze">Laravel Breeze</a></li>
<li><a href="https://github.com/laravel/ui">Laravel UI</a></li>

<h2>Business logic:</h2>

<li>Blog consists of posts in reverse chronological order</li>
<li>Draft posts are only visible to its author</li>
<li>Post can be created by registered user, edited and deleted - only by post author</li>
<li>Post can be commented and liked by registered user</li>
<li>Comment can be deleted only by comment author</li>
<li>Comment can be liked by registered user</li>
<li>Post/comment can not be liked by same user twice</li>
<li>Post authors are email notified of comments and likes</li>
<li>Comment authors are email notified of likes</li>

<h3>Blog entities:</h3>

<h4>Post:</h4>
<li>id</li>
<li>date</li>
<li>title</li>
<li>content</li>
<li>slug</li>
<li>status (draft, published)</li>
<li>comments count</li>
<li>likes count</li>

<h4>Comment:</h4>
<li>id</li>
<li>content</li>
<li>likes count</li>

<h4>Like:</h4>
<li>id</li>

<h3>Functionality:</h3>
<li>Display a listing of the posts with minimal info included (date, title, status, number of comments and likes)</li>
<li>Display a single post with detailed info included (date, title, content, status, attached comments, number of likes for post and for each attached comment)</li>
<li>Create post</li>
<li>Update post</li>
<li>Delete post</li>
<li>Add comment to the post</li>
<li>Like post</li>
<li>Like comment</li>
<li>Provide REST API endpoint for retrieving 5 latest posts</li>

<br>
<br>
<br>
<h5>*Feel free to ask us for any clarifications if needed</h5>