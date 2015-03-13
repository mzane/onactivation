This little jQuery-plugin defines the position, that developers don't need to know whether an element was clicked or used with the keyboard - he just needs to know, that an element was activated (by the user). So onActivation binds basically a click- and a keyup-event to a defined element, and the developer makes sure by using this plugin, that even keyboard users are ready to go. Additionally the plugin also prevents double clicks where double clicks shouldn't be valid.

Use it like this:

`$("input[type='submit']").onActivation(function() {`
> `// do something ...`
`});`