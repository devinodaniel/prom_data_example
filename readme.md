# Prometheus Data (Prom Data)

This repository is designed to store config files for the Prometheus Suite.

To add a new configuration, simply copy the `default` folder and rename it. For instance, a Prom Data config for your Network Engineering lab could be called `neteng_lab` so simply use this as the name the top level folder.  The naming convention is totally up to but it's recommended that you use underscores instead of spaces as the folder will be referenced by Prometheus using its absolute path. 

**Folder structure is important.** Renaming or changing the location of the default files may cause Prometheus or any of the other services such as Alert Manager to not properly run.