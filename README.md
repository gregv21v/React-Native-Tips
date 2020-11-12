# React-Native-And-Expo-Tips

## Tools

[Blisk](https://blisk.io/) is a good brower to use for development, particularly if you are developing for IOS on a windows machine with Expo. Having to build your app on a remote build server that has a line on it can take a lot of time. Using Blisk with Expo can allow you to fine the UI before you build it remotely. Blisk is a browser for developers, built on Chromium.


## Helpful Links


## Common Errors Messages

Sometimes when you compile your react code it will give you an error like this:

```
TypeError: Failed to construct 'Image': Please use the 'new' operator, this DOM object constructor cannot be called as a function.
```

This likely means that you forget to include an import. In the above case, the import you forgot would be the Image component.

----

Another common you might see is this:

```
TypeError: Cannot read property 'state' of undefined
```

If you are trying to access the state variable inside a function of your component then you likely haven't bound that function to the class. You do that as follows:

```
this.functionName = this.functionName.bind(this)
```



