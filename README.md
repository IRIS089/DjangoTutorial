# DjangoTutorial
I will be working through the real python django course. You can view the course here: https://realpython.com/courses/django-portfolio-project/

Part 1 - Django Overview
1. About this section
2. About Web Frameworks and Django
3. What you'll build and learn
4. Apps in the Django project
5. Files in a Django project
6. Flow in a Django project
7. Recap and Outlook

3. What you'll build and learn
- How to build a Django project from start to finish
- We'll do lot's of Django deep-dives, asking: how does this actually work?
- Get friendly with Django error messages
- Hands-on debugging approaches during Django development
- Understand Django projects and file structure
- Understand how requests flow through Django apps
- Models, views, and templates
- Primer on Relation Databases and using the Django ORM
- Interact with your DB from the Django Shell and the Django Admin Interface
- Using the Django Templating language and Template Inheritance
- URL resolving and correctly using path converters and namespaces
- Using Bootstrap for style and mobile responsiveness

4. Apps in the Django Project
- when you create your first django project you'll get a folder with the name of your project and a manage.py file
- you'll create additional apps in this project folder for your whole website
- the project will have a urls.py file where django will look to know which app to go to 

5. Files in a Django project
- settings.py - mostly used to route to other apps
- urls.py - this allows django to know what to do when it receives a url
- views.py - this is where we will write most of our logic
- models.py - this is where we will store the structure of our objects that we store in the database
- templates - used to contain our html files for displaying to the user

6. Flow in a Django project
- when you enter a url, first django will look in the urls.py in the project folder to know which app to go to, once it does this it will go to that apps urls.py file to figure out where to go next, the urls.py will direct us to views.py which will direct us to a specific template in our templates folder


Part 3 - Build a Django Application

1. About this section
2. Django by error messages
3. Create a Django App
4. Build your routes
5. Create a view
6. Create a template
7. Add bootstrap to your app
8. Recap and Outlook
