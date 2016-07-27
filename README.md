# keeping track of notes without spamming disqus  

bomb ass tutorial: http://gregblogs.com/how-the-do-i-build-a-django-django-rest-framework-angular-1-1-x-and-webpack-project/#step1  

* step 1
* step 2  

  * we create configlord/dev.env but then in step 3, mysite/dev.env is referenced instead, unsure which it should be
  * we didn't touch frontend files and instead created them later (cool but just inconsistent)

* step 3

  * not entirely clear if we are editing / overwriting the regular mysite/settings.py or creating new settings in configlord/settings/base.py. The imports make it look like the former but if that's the case I don't get the point of separate configlord. likely me being a noob
  
* step 4

  * again probably noobness but not sure what to do with settings.py if we are using this base.py, and are we copying over all the installed apps or taking these excepts literally? :( 
  
* step 5

  * in the class def need (model.Models):
  
* step 6

 * this is what happens: 
 ```  
 python manage.py runserver --DJANGO_SETTINGS_MODULE=mysite.settings.dev
usage: manage.py runserver [-h] [--version] [-v {0,1,2,3}]
                           [--settings SETTINGS] [--pythonpath PYTHONPATH]
                           [--traceback] [--no-color] [--ipv6] [--nothreading]
                           [--noreload] [--nostatic] [--insecure]
                           [addrport]
manage.py runserver: error: unrecognized arguments: --DJANGO_SETTINGS_MODULE=mysite.settings.dev
```  

* step 7
* step 8
* step 9
* step 10
* step 11
* step 12  
typo:  

> Learn *by* NOT to do var that = this; over at my friend's blog!
