# First steps with Polymer



## Install dependencies


```shell
$ bower init
$ bower install Polymer/polymer#2.0.0 --save
$ bower install PolymerElements/app-layout --save
$ bower install PolymerElements/iron-icons --save
$ bower install PolymerElements/paper-icon-button --save 
```

## Some notes

Check the `x-app.html` source code to see how to use the following components:

- `<app-header-layout>` & `<app-header>`
- `<app-drawer-layout>` & `<app-drawer>`
- `<app-toolbar>`

As you can see the \<app-header-layout> has the `fullbleed` attribut which tells the layout to take the entire page size.

The `<app-drawer>` has two behaviors depending on if it is a child of `<app-drawer-layout>` or not. To activate the `<app-drawer-layout>` uncomments the tag in `x-app.html`. 

The `drawer-toggle` attribut binded to the `<paper-icon-button>` only works if the `<app-drawer>` is inside the `<app-drawer-layout>`.

Note the `reveals` attribut on the `<app-header>` component which is an effect attached to the header when the user scroll up:

>app-header is container element for app-toolbars at the top of the screen that can have scroll effects. By default, an `<app-header>` moves away from the viewport when scrolling down and if using `reveals`, the header slides back when scrolling back up.

The `waterfall` effect that 

>Toggles the shadow property in app-header to create a sense of depth (as recommended in the MD spec) between the header and the underneath content. And is provided from the following component: 

```html
<link rel="import" href="bower_components/app-layout/app-scroll-effects/app-scroll-effects.html">
```


## View the resulting page

```shell
$ polymer serve --open
info:    Files in this directory are available under the following URLs
      applications: http://127.0.0.1:8081
      reusable components: http://127.0.0.1:8081/components/polymer-layout/
```

# References
-  Polymer-project.org: Polymer [\<app-layout>](https://github.com/PolymerElements/app-layout)
