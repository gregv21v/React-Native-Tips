# React-Native-Tips


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


## Helpful Links


