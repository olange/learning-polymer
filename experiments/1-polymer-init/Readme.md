# First steps with Polymer
## Create an initial page

Prerequisites:
- Bower installed 
- Polymer CLI installed


```shell
$ bower init
$ bower install Polymer/polymer#2.0.0 --save
```

Create `index.html` that imports webcomponents-lite.js. The library contains polyfills for browser that are not supporting webcomponents. In  

```html
  ...
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
  ...
  <body unresolved>
  </body>
```


## Create and import a component

Between the `<head>..</head>` tags, insert: 

```html
<link rel="import" href="x-app.html">
```
And use the component in the page between the `<body></body>` tags:

```html
  <body unresolved>
    ...
    <x-app></x-app>
    ...
```


Create `x-app.html` with the following structure:

```html
<link rel="import" href="bower_components/polymer/polymer.html">
<link rel="import" href="bower_components/app-layout/demo/sample-content.html">

<dom-module id="x-app">

  <template>

    <style>
    </style>
     
     <h1>Hello world</h1>

  </template>

  <script>
    Polymer({
      is: 'x-app',
      ready: function(){
        console.log("Ready!");
        this.foo();
      },
      foo: function() {
        console.log("You called a foo!");
      }
    });

  </script>

</dom-module>
```

## View the resulting page

```shell
$ polymer serve --open
info:    Files in this directory are available under the following URLs
      applications: http://127.0.0.1:8081
      reusable components: http://127.0.0.1:8081/components/polymer-layout/
```

