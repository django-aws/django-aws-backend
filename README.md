# django-aws-backend

This is a simple Django app to be deployed on AWS.

## To start a Django project on windows :

1. to start an empty git repo and activate venv
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/27d4a4c4-960e-4b9b-8bf0-2e67772fcc7a)

2. install django using pip:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/06f18507-c07e-4c5e-87ad-c6ba0996ef11)

3. Start a Django project:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/c8849e3f-4304-4cdd-934f-4f8523db9866)

4. Do Django migrate for all changes to apply and run the server:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/ea3fa71f-4ec5-47ca-a893-dd69a7f40302)

5. Now you've a Django app running:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/36b0420b-aa2b-4196-aa81-d465ba744f2a)

6. Now create and build a Docker image for this App:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/99cbdde3-a4e6-4b49-a056-337bdda9a810)
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/2625bfbf-2d1d-4e86-9497-cb94f5e9bb3b)


8. Now run docker container using this image:
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/3e3e8397-d941-4ea3-b01a-7815571c2d99)
   ![image](https://github.com/django-aws/django-aws-backend/assets/147988907/8468db56-9645-47e1-9bcb-7eeda407bcaa)

9. Next step is to write terraform to have your app working on aws via IaC
   Follow the django-aws-infrastructure repo in the same organization
