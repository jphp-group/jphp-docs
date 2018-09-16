## Resources and protocol res://

The protocol ``res://`` is a system protocol inside JPHP, it helps to access any files from resource sources. 

If you are developing a project using jppm, the resource folder is ``<project path>/src``. 

After compilation, all files inside the src fall into the executable file and they can still be read using the ``res://`` protocol, although they are already inside your application.
