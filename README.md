# DjangoAdmin
Some Records here for Django Admin Site customization

How to import Model from another App
https://stackoverflow.com/questions/31406662/django-unable-to-import-model-from-another-app
Switch
from News.models import News_Article
to
from Bolton_GC.News.models import News_Article


I. Model Field Setting 

https://docs.djangoproject.com/en/2.1/ref/models/fields/ 

1.Especially for DateField
DateField.auto_now vs DateField.auto_now_add
Automatically set the field to now everytime saved vs first created. 

2.for Primary Unique Key
id = models.AutoField(primary_key=True) is automaically created the primary key




Regular expression

https://docs.djangoproject.com/en/2.1/ref/models/querysets/#regex

Look up with Q filter
https://docs.djangoproject.com/en/2.1/topics/db/queries/#complex-lookups-with-q
https://stackoverflow.com/questions/687295/how-do-i-do-a-not-equal-in-django-queryset-filtering

How to upload a file
https://stackoverflow.com/questions/2443752/django-display-image-in-admin-interface


3. Multiple Image Display

https://stackoverflow.com/questions/16985258/how-to-show-multiple-images-in-django-admin-panel

4. Action for Downloading (Not testing...)

https://www.endpoint.com/blog/2012/02/22/dowloading-csv-file-with-from-django

5. Permissiong for Add, Delete, Save

https://docs.djangoproject.com/en/2.1/ref/contrib/admin/#django.contrib.admin.ModelAdmin.has_add_permission

6. Help Text

https://docs.djangoproject.com/en/2.1/ref/models/fields/#help-text

