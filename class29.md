## Django Custom User Model
- Custom user model manager where email is the unique identifiers. for authentication instead of usernames
- there are two ways to create custom user model, first ways is AbstractUser and the second way is AbstractBaseUser
- Absrtacuser is a full User model, complete with fields, as an abstract class so that you can inherit from it and add your own profile fields and methods.
- AbstractBaseUser contains the authentication functionality, but no actual fields.

### Custom user model features
- update django_project and settings.py
- create a new CustomUser model
- create new UserCreation and UserChangeForm
- update the admin


## Django X
- is a starter template that comes with log in and out, and for users to sign up. Also being able to style with Bootstrap
