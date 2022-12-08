
<p><img src="https://user-images.githubusercontent.com/68425016/198209507-39c6cd5c-ad15-4d9d-8ac4-2a75cfc66e20.png" align="left" width="250" /></p>

<br/>

# webserver

A Simple implementation of a Static webserver from scratch. being a simple implementation it can handle routes and status code. 

# Setup
Setup tutorial on [youtube](https://youtu.be/MQG5TrDgdX8)

## Build the server
```
    make
```

## .config for server configurations
The website which is going to be hosted should conatin .config file. [Example](https://github.com/AtmegaBuzz/webserver/tree/master/website) 

```
    /* server_ip = 192.168.0.4;
    port = 80;
    routes:
        {route1,<html filepath1>}
        {route2,<html filepath2>}
    */
     
    routes: // example 
        {/,index.html};
        {/about,about.html};
        {/contact,contact.html};
```

## Host a static site
```
    ./webserver --host <website folder path>
```
