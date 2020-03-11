# webdiceroller
### How to download:
##### First Time
```
git clone https://github.com/botdemy/webdiceroller.git
```
##### Weekly Refresh
```
cd webdiceroller
git fetch origin
git reset --hard origin/master
```
### How to upload/commit: (admin only)
```
git add -A
git commit -m "weekly update"
git push
```
### How to setup a static site on pythonanywhere
1. In main menu, select Web
2. Add a new web app
3. Select Manual configuration. Select Python 3.7. Next. 
4. Update /var/www/[yoursite].wsgi file
5. Test your site: yourusername.pythonanywhere.com
