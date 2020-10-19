# IntegralUI Web Lite - TreeList, v20.2

IntegralUI Web Lite - TreeList is a native Web Component that allows you to navigate through tree hierarchy showing only one list at a time. 

![IntegralUI Web Lite - TreeList 20.2 - Native Web Component](https://www.lidorsystems.com/products/web/lite/images/integralui-web-treelist-20.2.png)

<b>Note</b> This component is part of [IntegralUI Web Lite](https://github.com/lidorsystems/integralui-web-lite.git).

Here is a brief overview of what is included:

## Components

[TreeList](https://www.lidorsystems.com/products/web/studio/samples/web-components/#/treelist) - Allows you to navigate through tree hierarchy showing only one list at a time


## Services

<b>Common</b> - Includes a set of common functions usable in most applications

<b>Data</b> - Includes a set of data related functions for different operations like: add/remove, search, etc.


## DEMO

[Online QuickStart App](https://www.lidorsystems.com/products/web/studio/samples/web-components/) - An online demo of each component included


## Installation

Install the repository by running

```bash
npm install https://github.com/lidorsystems/integralui-web-treelist.git
```

or directly from NPM

```bash
npm i integralui-web-treelist
```

Open your application and add a reference to a component you want to use. For example, if you are using the IntegralUI TreeList component:</p>

### Angular

```bash
import 'integralui-web-treelist/components/integralui.treelist.js';
```

### React

```bash
import IntegralUITreeListComponent from 'integralui-web-treelist/wrappers/react.integralui.treelist.js';
```

<b>Note</b>   Currently [ReactJS doesn't have full support for Web Components](https://custom-elements-everywhere.com/#react). Mainly because of the way data is passed to the component via attributes and their own synthetic event system. For this reason, you can use available wrappers located under /wrappers directory, which are ReactJS components that provide all public API from an IntegralUI component.</p>

### Vanilla JavaScript

```bash
<script type="module" src="integralui-web-treelist/components/integralui.treelist.js"></script>
```


## Icons

Because of the web component specification that defines URLs to be always relative to the main document, the path that leads to the icons used by the IntegralUI Web components needs to be set. In addition you may also need to copy/paste the /icons folder in your application folder. Depending on the framework of your choosing this may differ.

### Angular

Follow these steps:
1. Copy/Paste the content of the integralui-web-treelist/icons folder under /assets/integralui/icons subfolder in your React application. 
2. Set the resourcePath property of IntegralUI Web components to point to the location set in your /assets folder. In this case, for TreeList for example:

```bash
<iui-treelist [resourcePath]="'assets/integralui/icons'"></iui-treelist>
```

### React

Follow these steps:
1. Copy/Paste the content of the integralui-web-treelist/icons folder under /public/integralui/icons subfolder in your React application. 
2. Set the resourcePath property of IntegralUI Web components to point to the location set in your /public folder. In this case, for TreeList for example:

```bash
<IntegralUITreeListComponent resourcePath="integralui/icons"></IntegralUITreeListComponent>
```

### Vanilla JavaScript

Set the resourcePath property of IntegralUI Web components to point to /integralui-web-treelist/icons folder. In this case, for TreeList for example:

```bash
<iui-treelist resource-path="../../integralui-web-treelist/icons"></iui-treelist>
```


## QuickStart App

There is a demo application with source code that contains samples for TreeList component. It can help you to get started quickly with learning about the components and write tests immediatelly. 

From [IntegralUI Web Lite - QuickStart](https://www.lidorsystems.com/products/web/lite/#quickstart) you can download a demo app for Angular, React and Vanilla JavaScript. A detailed information about each of these quick-start demos is available in ReadMe file, located in the root folder of the demo app.


## License Information

You are FREE to use this product to develop Internet and Intranet web sites, web applications and other products, with no-charge.

This project has been released under the IntegralUI Web Lite License, and may not be used except in compliance with the License.
A copy of the License should have been installed in the product's root installation directory or it can be found here: [License Agreement](https://www.lidorsystems.com/products/web/lite/integralui-web-lite-license-agreement.pdf).

This SOFTWARE is provided "AS IS", WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License for the specific language governing rights and limitations under the License.