# How to use slots in Polymer 2.0

The purpose of this experiment is to test how slots behave. As you can see in the `src/polymer-slot-app/polymer-slot-app.html`, there are 3 slots (header, content, footer). 

```html
     <slot name='header'>HEADER</slot>
      <h2>Hello [[prop1]]!</h2>
      <div class='content'>
        <slot>CONTENT</slot>
      </div>
      <slot name='footer'>This is my footer</slot>
      ...
```

In `index.html`: even if the footer is invoked first and the header is invoked last (where it should be the opposite), we can see that the order has no effect when rendered by the Polymer element. The header is at the top while the footer is at the bottom in the generated DOM.

## Installation

Run:  
`$ bower install`

## Preview 

Run:  
`$ polymer serve`
