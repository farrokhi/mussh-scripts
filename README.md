# mussh-scripts

A bunch of scripts to be used on conjunction with `mussh(1)` to automate tasks on remote servers. Most of the scripts are specific to FreeBSD. And most of them might be totally irrelevant (or look weird) for your workflow. This was supposed to be a private repository, but I decided to make it public so maybe others find them useful too.

## Why?

Why not ansible/puppet/chef/blah?

Configuration management tools are supposed to make life easier for Ops. For me they never did. I found ansible untidy and ugly, and every other configuration management tool too bulky or too complicated for my workflow. I believe most CM tools are just making life even more complicated for most experienced ops folks, but they hesitate to admit. 
Let's be honest. What is really wrong with your good old shell script workflow? What is wrong with [mussh](https://sourceforge.net/projects/mussh/) (except that it is hosted on SourceForge)?
Every sane sysadmin is able to write great shell scripts that are powerful and flexible? So why you give it up to some cryptic configuration file or a fat CM software (perhaps from a fat vendor)?
For the moment, I prefer to stick with shell scripts and `mussh(1)` until some sane CM tool comes along.

