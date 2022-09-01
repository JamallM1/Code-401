# class 34

## Django Settings 
- Sensitive data cannot be stored in VCS
- Sharing settings between team members you have to take on this as an average task while dealing with the settings 
- Django settings are a Python code, instead of having key value pairs settings have different and sometimes tricky logic 
## Settings_local.py
- for this method to work you need to extend all environmental settings in the settings_local.py file and it'll also be ignored by VCS
## PROS
- Secrets not in VCS.
## CONS
- You can lose some of your django environment settings 
