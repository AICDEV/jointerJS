Simple jquery plugin to connection elements
===============

# What can this program do ?

Sometimes you need a simple plugin that can connection two html elements without canvas. Here is it.
In the example folder, is a simple example how you can create and delete connections and work with jointerJSs


## create instance from jointerJs

Please make sure that you have jQuery included in your project.

```javascript
  var jointer = new $().jointer();
```

You can also instantiate jointerJS with some arguments. The first param is the color from the connection line, the second is the color from the connection circle and
the third tells jointer to use margins from target element to connect it right. Just try it out.

```javascript
  var jointer = new $().jointer('black','red', true);
```

## connect elements

If you want to connection two elements, just do it as follow. Please make sure, that your elements have an id attribute!.
The first element is your element where the connection comes from, the second is the target element from your connection.

```javascript

     jointer.connectElements('#from1', '#target1');

```


##remove connection from element

If you want to delete a connection from an element. You can just do it like follow.

```javascript

      jointer.clearConnection('#from1');

```

## remove all connections

If you want to delete all connections. You can just do it like follow.

```javascript

        jointer.clearAllConnection();

```

If you find any bugs or have some nice ideas for improvements, just let my know ;)

And thanks to Jon Surrell for this awesome guid function
https://stackoverflow.com/users/1432801/jon-surrell


Happy connecting and coding =)
