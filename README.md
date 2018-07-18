# Test task for [timebook]](http://timebook.jobingood.com/)

This is CI repository for a simple web-application, based on laravel PHP web-framework. Application located [here](https://github.com/lictw/simple-app).

## Using with test-kitchen framework
```
kitchen converge ubuntu
```
**Make sure that ruby, related gems (test-kitchen, kitchen-vagrant, kitchen-ansible), vagrant and VirtualBox are installed!**

## Using with raw ansible:
1. Change target host in inventory file
2. Execute *deploy.yml* playbook via ansible-playbook
3. Enjoy! (this isn't tested, but i convinced that it works)
