### Fridays 

##### 1- Working directory
```
1. [/](https://ondemand-rmacc.rc.colorado.edu/pun/sys/dashboard/files/fs//)
2. [scratch /](https://ondemand-rmacc.rc.colorado.edu/pun/sys/dashboard/files/fs//scratch)
3. [alpine /](https://ondemand-rmacc.rc.colorado.edu/pun/sys/dashboard/files/fs//scratch/alpine)
4. [sbagheri@colostate.edu /](https://ondemand-rmacc.rc.colorado.edu/pun/sys/dashboard/files/fs//scratch/alpine/sbagheri@colostate.edu)
5. decomp_tutorial /
```

Set up Node for Fridays 
```
sinteractive --reservation=aneq505 --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

- For other days 
```
ainteractive --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

- always Purge 