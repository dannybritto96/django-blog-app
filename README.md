<h1>Blog Application powered by Django</h1>

Simple blog application. Only the superuser i.e., you can post.
Be sure to migrate before running.

<h3>Clone the project</h3>
<pre> git clone https://github.com/dannybritto96/django-blog-app.git</pre>

<h3>Make migrations</h3>
<pre>
python manage.py migrate
python manage.py makemigrations blog
python manage.py migrate
</pre>

<h3>Create a superuser</h3>
<pre>
python manage.py createsuperuser
</pre>

<h3>Run server</h3>
<pre>
python manage.py runserver
<pre>
Goto <a href="http://127.0.0.1:8000">http://127.0.0.1:8000 </a>to view the application.

Thanks to <a href="https://github.com/yabwe">Yabwe</a> for MediumEditor tool.
For more information on the tool visit <a href="http://yabwe.github.io/medium-editor/">http://yabwe.github.io/medium-editor</a>

<h3>How to post?</h3>
Login as the superuser you've created. Then you can see 'New Post' option in the Navbar.It'll let you create new posts.
