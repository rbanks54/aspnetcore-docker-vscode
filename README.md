# About this sample

A working example of starting an debugging a .net core app in a docker container from VSCode

#### Basics
To use it, do the following

* run `docker-compose up -d`
* run `watch.cmd`
* In VSCode, set a breakpoint and then attach the debugger using either of the 'Attach to web' options.
* browse to http://localhost:5001 and see your breakpoint get hit

If you're on linux/mac, just run the docker-compose command inside `watch.cmd` manually

#### Taking it further

* make a change to the code as save it
* recompile the application locally. Your console output should show the web site restarting. 
* reattach the debugger (the process id will probably have changed). You should be able to just press F5

When you're done, just hit ctrl-c to end your watch command in the container and take the environment down using 'docker-compose down'.

#### Notes
This sample was forked from [alexjamesbrown/aspnetcore-docker-vscode](https://github.com/alexjamesbrown/aspnetcore-docker-vscode), and arose from this twitter thread https://twitter.com/alexjamesbrown/status/1069751862381944833

More information and details can be found in my post at https://www.richard-banks.org/2018/07/debugging-core-in-docker.html