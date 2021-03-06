# Django GuestBook App

## Folder Structure
``` 
myproject  
│	  README.md
│     db.slite3
│     manage.py  
└───────────guestbook
│           │   __init__.py
│           │    admin.py
│           │    apps.py
│           │    forms.py
│           │    models.py
│           │    test.py
│           │    urls.py
│           │    views.py
│           └────migrations
│	        │	     │   0001_initial.py
│           │        │   _init_.py
│           │           
│           └────static
│           │        └────guestbook
│           │        │        bootstrap-theme.min.css
│           │        │        bootstrap.min.css
│           │        │        sign.css
│           │        │        theme.css
│           └──── templates
│           │         └────guestbook
│           │         │        index.html 
│           │         │       sign.html
│           │
└────────────hello
│           │   __init__.py
│           │    admin.py
│           │    apps.py
│           │    forms.py
│           │    models.py
│           │    test.py
│           │    urls.py
│           │    views.py
│           └────migrations
│	        │	     _init_.py    
│           │  	
└───────────myproject
│           │   __init__.py
│           │    settings.py
│           │    urls.py
│           │    wsgi.py
│           └────migrations
│	        │	 _init_.py    
│           │  	
│	        │		
└───────────screenshots
│                a_comment.png
│                admin.png
│                comments.png
│                guestbook_comments.png
│                sign_page.png  
│		
   ```

## Screenshots
* *http://127.0.0.1:8000/admin/guestbook/comment/{id}/change/*
![a_comment.png](https://github.com/james-chege/mydjango-first-app/blob/master/screenshots/a_comment.png)

* *http://127.0.0.1:8000/admin/*
![admin.png](https://github.com/james-chege/mydjango-first-app/blob/master/screenshots/admin.png)

* *http://127.0.0.1:8000/admin/guestbook/comment/*
![comments.png](https://github.com/james-chege/mydjango-first-app/blob/master/screenshots/comments.png)

* *http://127.0.0.1:8000/guestbook/*
![guestbook_comments.png](https://github.com/james-chege/mydjango-first-app/blob/master/screenshots/guestbook_comments.png)

* *http://127.0.0.1:8000/guestbook/sign/*
![sign_page.png](https://github.com/james-chege/mydjango-first-app/blob/master/screenshots/sign_page.png)