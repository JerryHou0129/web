# web

##### after installing nodejs on ubuntu
##### if node command displays       "no such file or directory"
##### it is because that node.js is installed under usr/bin/nodejs in default on ubuntu
##### Therefore you can only do       nodejs helloWorld.js
##### By creating a link using        sudo ln -s /usr/bin/nodejs /usr/bin/node
##### All done
