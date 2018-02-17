<h1>Blog Application powered by Django<h1>

Simple blog application. Only the superuser i.e., you can post.
Be sure to migrate before running.
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

Thanks to https://github.com/yabwe for MediumEditor tool.
For more information on the tool visit http://yabwe.github.io/medium-editor/
