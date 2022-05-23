## Permissions & Postgresql
Permissions are used to grant or deny access for different classes of users to different parts of the API.<br>

REST framework permissions also support object-level permissioning. Object level permissions are used to determine if a user should be allowed to act on a particular object, which will typically be a model instance.<br>

## Setting the permission policy
Add this block of code to set the authentication policy to allow only the owner of the object to modify it.<br>
```
REST_FRAMEWORK = {
    'DEFAULT_PERMISSION_CLASSES': [
        'rest_framework.permissions.IsAuthenticated',
    ]
}
```
## API Reference
**IsAuthenticated**<br>
The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.<br>

This permission is suitable if you want your API to only be accessible to registered users.<br>

**IsAdminUser**<br>
The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.<br>

This permission is suitable if you want your API to only be accessible to a subset of trusted administrators.<br>

**IsAuthenticatedOrReadOnly**<br>
The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.<br>

This permission is suitable if you want to your API to allow read permissions to anonymous users, and only allow write permissions to authenticated users.<br>

**AllowAny**<br>
The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.<br>

[Page Link](https://www.django-rest-framework.org/api-guide/permissions/)

