# webdriveio
webdrive.io test

Git Setup
---------
```
git config user.name $GIT_USER_NAME
git config user.email $GIT_USER_EMAIL

git config credential.helper 'cache --timeout=3600'
git config credential.helper store

git config --global push.default simple

git config --list
```

Run selenium server
-------------------
java -jar -Dwebdriver.gecko.driver=./geckodriver selenium-server-standalone-3.0.1.jar


Run simple test
---------------
node test.js


Run spec test
-------------
./node_modules/.bin/wdio wdio.conf.js

