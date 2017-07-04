[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

# ag-Grid Web Component

This project contains the ag-Grid Web Component 

See the [www.ag-grid.com](http://www.ag-grid.com) for an overview and full documentation.

## Demo

[Simple Grid - Live Demo ↗](https://www.ag-grid.com/best-web-component-data-grid/examples/simple-grid/simple-grid-example.html)
[Rich Grid - Live Demo ↗](https://www.ag-grid.com/best-web-component-data-grid/examples/simple-grid/rich-grid-example.html)

<!--
```
<custom-element-demo>
  <template>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/custom-elements/1.0.0/custom-elements.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/ag-grid/11.0.0/ag-grid.min.js"></script>
    
    <link rel="import" href="ag-grid.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<other-element></other-element>
<ag-grid></ag-grid>
```

## Installation 

#### Install with Bower
```sh
$ bower install ag-grid-webcomponent
```

#### Install with Npm
```sh
$ npm install ag-grid-webcomponent
```

## Usage 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>ag-Grid Web Component - Simple Example</title>

    <!-- webcomponents polyfill - must be before any wc related javascript is executed -->
    <script src=../../node_modules/@webcomponents/custom-elements/custom-elements.min.js></script>

    <!-- before the ag-grid web component -->
    <!-- either ag-grid or ag-grid-enterprise, depending on which you're using -->
    <script src="../../node_modules/ag-grid/dist/ag-grid.min.js"></script>

    <!-- the ag-grid-webcomponent-->
    <link rel="import" href="../../node_modules/ag-grid-webcomponent/ag-grid.html">

    <!-- the application code -->
    <script src="simple-grid-example.js"></script>
</head>
<body>
<ag-grid id="myGrid"
         style="height: 140px; width: 350px;"
         class="ag-fresh"></ag-grid>
</body>
</html>
```

## Examples

See the [https://github.com/ceolter/ag-grid-webcomponent-example](https://github.com/ceolter/ag-grid-webcomponent-example) for full 
working examples of what you can do with ag-Grid and Web Components.

Examples included are:

## Simple Grid 
![Simple Grid](https://github.com/ceolter/ag-grid-webcomponent-example/blob/master/docs/simple.png?raw=true "Rich Grid")
## Rich Grid 
![Rich Grid](https://github.com/ceolter/ag-grid-webcomponent-example/blob/master/docs/rich.png?raw=true "Rich Grid")
