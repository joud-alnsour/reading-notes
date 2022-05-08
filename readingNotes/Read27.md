# Djano Models
## Fields
- CharField: Characters
- TextField: large arbitrary strings
- IntegerField: ints
- DateField: Datetime
- EmailField: unknown
- FileField: Files / Images
- AutoField: Automatic increments/ for primary key
- ForeignKey: id field from a relational model
- ManyToManyField: Specifies relationships

## Models
- class based
- common methods: __str__ and get_absolute_url
- Use models to perform CRUD (similar to mongoose)
- Model.objects.all() Find all
- instance.save()
- Model.objects.filter(title__contains='something') filter search (dunder separates fields)<br>

[Page Link](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)


# Django Admin
- Register models with admin.py
>admin.site.register(Model)
- Create superuser
- register models with admin/list display

[Page Link](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
