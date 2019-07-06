# otd-commands

Are you still suffering from installing software, and worry about polluting your base system, this should be done.

The over the docker commands can help you run command as ***local installed command*** and forget about the installation and configuration.

They are designed to be one-off command base on the docker technology, I hope this can change the way people they use software, no more installation, configuration, just run the command, the docker will do the rest. If docker hub provide this kind of shortcut command, people no more need to docker pull xxx and docker run xxx, just docker install git, and then git version, blah blah...

    $ tree otd-commands
    otd-commands
    ├── dk-ls-tags-v1     (list all tags by image name from docker hub, through Docker Registry HTTP API V1.)
    ├── dk-ls-tags-v2     (list part of tags by image name from docker hub,  through Docker Registry HTTP API V2.)
    ├── gcc               (GCC is a compiler system produced by the GNU Project supporting various programming languages.)
    ├── gen-dockerfile    (generate Dockerfile from local image)
    ├── gen-dockerfile-r  (generate Dockerfile recursively from local image)
    ├── git               (Git is a distributed version-control system for tracking changes in source code during software development.)
    ├── http              (HTTPie is a command line HTTP client with an intuitive UI, JSON support, syntax highlighting, wget-like downloads, plugins, and more.)
    ├── install           (Install this set of commands by export current directory to env PATH.)
    ├── java              (Run java classes)
    ├── mkcd              (create a dir and cd's into it)
    ├── mongo             (MongoDB is a cross-platform document-oriented database program.)
    ├── myip              (check my public ip address)
    ├── myip2             (check my public ip address)
    ├── mysql-cli         (mysql client tools)
    ├── python            (run python scripts)
    ├── redis             (start redis server)
    ├── redis-cli         (redis client)
    ├── set-aliases       (set a set of aliases for shell)
    ├── strace            (strace is a diagnostic, debugging and instructional userspace utility for Linux. )
    └── svn               (subversion is a software versioning and revision control system.)

## Prerequisites

Make sure you have installed Docker.

## Installing
```
git clone https://github.com/leo18945/otd-commands

cd otd-commands && source ./install
```

## Running OTD command
```
http ifconfig.co/json

myip

...
```

## Reference
Please cat command and go to their website.
