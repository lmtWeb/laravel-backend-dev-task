# laravel-fullstack-dev-task

<h1>Task:</h1>

<li>Create simple blog application according to described business logic.</li>
<li>Create your repo (preferablly on Github) for laravel-fullstack-dev-task solution and share it us.</li>

<h2>Requirements:</h2>
<li>Use Laravel 9</li>
<li>Use OOP</li>
<li>Follow best practices SOLID, Clean code etc.</li>
<li>Data storage solution is up to you.</li>

<h3>Optionally for authentication scaffolding you can use:</h3>
<li><a href="https://github.com/laravel/breeze">Laravel Breeze</a></li>
<li><a href="https://github.com/laravel/ui">Laravel UI</a></li>

<h3>Optionally for email sending you can use:</h3>
<li><a href="https://mailtrap.io">Mailtrap</a> or any other email sandbox service</li>

<h2>Business logic:</h2>

<li>Blog consists of posts in reverse chronological order</li>
<li>Draft posts are only visible to its author</li>
<li>Post can be created by registered user, edited and deleted - only by post author</li>
<li>Post can be liked/unliked by registered user</li>
<li>Post can not be liked by same user twice</li>
<li>Post authors are email notified of likes (plain text email - "Your post was liked {postUrl}")</li>

<h3>Blog entities:</h3>

<h4>Post:</h4>
<li>id</li>
<li>date</li>
<li>title</li>
<li>content</li>
<li>slug</li>
<li>status (draft, published)</li>
<li>likes count</li>

<h4>Like:</h4>
<li>id</li>

<h3>Functionality:</h3>
<li>Authenticate users</li>
<li>Display a listing of the posts with minimal info included (date, title, status, number of likes)</li>
<li>Display a single post with detailed info included (date, title, content, status, number of likes)</li>
<li>Create post</li>
<li>Update post</li>
<li>Delete post</li>
<li>Like/unlike post</li>
<li>Provide REST API endpoint for retrieving 5 latest posts</li>

<br>
<br>
<br>
<h5>*Feel free to ask us for any clarifications if needed</h5>
