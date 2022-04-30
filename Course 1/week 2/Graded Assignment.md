Steps to follow: 
1. Go to "Files" section of your pythonanywhere account. 
2. Go to the directory where you have your django_project.
3. Now go to "django_projects/mysite/polls/views.py". The full path will look like \
"/home/*your-username*/django_projects/mysite/polls/views.py" 
4. Edit your "views.py" file to:
```
from django.http import HttpResponse

def index(request):
    return HttpResponse("Hello, world. *your-code specified in assignment* is the polls index.")
    
```

5. Go to "/home/*your-username*/django_projects/mysite/mysite/settings.py" and edit the ALLOWED_HOSTS to look as follows: \
ALLOWED_HOSTS = ['*']

6. That's it!!! Now go to your web page, reload the project URL and go to "http://*your-username*.pythonanywhere.com/polls".\
You'll see the response you edited in your "views.py". \
Submit this URL to get grades.
 
