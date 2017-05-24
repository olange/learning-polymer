# Creating a flex layout

## Install the dependencies

```shell
$ bower install Polymer/app-layout --save
$ bower install Polymer/iron-flex-layout --save
```


## Use the flex layout in the component


In `x-app.html` add the `iron-flex-layout-classes`

```html
<link rel="import" href="bower_components/iron-flex-layout/iron-flex-layout-classes.html">
```

Update the `style` tag to include `iron-flex` classes:

```html
<style include="iron-flex">
...
```

Add some DIVs that uses the flex layout

```html
  <template>
    ...

    <div class="layout horizontal ">
      <div class="box">Hello</div>
      <div class="box flex">Hello</div>
      <div class="box">Hello</div>
    </div>
  </template>
```



## View the resulting page

```shell
$ polymer serve --open
info:    Files in this directory are available under the following URLs
      applications: http://127.0.0.1:8081
      reusable components: http://127.0.0.1:8081/components/polymer-layout/
```

# References
- Polymer-project.org [Polymer Elements - Flex Layout Guide](https://elements.polymer-project.org/guides/flex-layout)
