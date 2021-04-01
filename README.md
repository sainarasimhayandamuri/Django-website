## Django-website

1. We create a portfolio website using html and css
2. We convert this into a django template
3. We will create a templates folder and index.html file inside that folder
4. we will also create a static folder and we will update with style.css file in it.
5. Now we have to include path in settings.py file
```
 'DIRS': [os.path.join(BASE_DIR,'templates')],
```
6. Now we should also include static file path
```
STATICFILES_DIRS = [os.path.join(BASE_DIR),'static']
```
7. Atlast include update the path in url.py and return request in views.py file
