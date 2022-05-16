# Django Custom User
## Setup
- **There are several steps that must be completed first:**<br>
     - Create and navigate into a dedicated directory called accounts for our code
     - Install Django
     - Make a new Django project called config
     - Make a new app accounts
     - Start the local web server
     
- **Create a custom user for new projects.**
     - update project/settings.py
     - create a new CustomUser model
     - create new user form CustomUser model
     - update admin

## project/settings.py
AUTH_USER_MODEL = 'accounts.CustomUser' # new

## app/models.py
```
class CustomUser(AbstractUser):
 pass 
 # add additional fields in here
def __str__(self):
    return self.username
```    
## app/forms.py
```
from django import forms 
from django.contrib.auth.forms import UserCreationForm, UserChangeForm 
from .models import CustomUser

class CustomUserCreationForm(UserCreationForm):
class Meta:
    model = CustomUser
    fields = ('username', 'email')
     
class CustomUserChangeForm(UserChangeForm):
class Meta:
    model = CustomUser
    fields = ('username', 'email')
```
[Page Link](https://learndjango.com/tutorials/django-custom-user-model)

