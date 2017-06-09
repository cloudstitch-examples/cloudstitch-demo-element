# \<cloudstitch-terminal\>

## Install the Polymer-CLI

* First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally. You should be able to do this by running `npm install -g polymer`
* Then make sure you have the components installed (`bower install`)

## Viewing Your Element

```
$ polymer serve
```

Then you can view the test page at:

http://127.0.0.1:8081/components/cloudstitch-terminal/demo/local.html

## Development Plan

### Stage 1 - Styling the Actor Lineup

This stage involves *just basic CSS*. If you look at this [Actor Lineup](https://cloudstitch-examples.github.io/cloudstitch-demo-element/components/cloudstitch-demo-element/) page, you'll see the different "actors" that are involved in our animation. Each actor is just a window.. but the coloring and contents will vary a bit.

If you look at the [Window Actor](https://github.com/cloudstitch-examples/cloudstitch-demo-element/blob/master/window-actor.html) Polymer element, you'll see the different CSS classes that are applied to each actor: `.terminal`, `.folder`, `.spreadsheet`... and so on. See [Zeit.co](http://www.zeit.co) for a great example of what a terminal and web browser might look like

* Update the [Window Actor](https://github.com/cloudstitch-examples/cloudstitch-demo-element/blob/master/window-actor.html) element to contain CSS so that each of these different variants is a nice looking representation of the role it's taking (terminal, folder, etc etc)

* Also update the `#file` and `#mouseCursor` elements to look like a file and mouse cursor


### Stage 2 - Animation Actions

TBD: Ted will provide all the code & test harness to implement different CSS animation sequences. We'll need your help implementing the CSS to make them look nice.