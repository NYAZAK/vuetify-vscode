<p align="center">
  <img height="200px"
  src="https://res.cloudinary.com/confidante/image/upload/v1520961320/logo_ew2tpg.png">
</p>

<h1 align="center">vuetify-vscode</h1>
<p align="center">Vuetify vscode extension</p>

`vuetify-vscode` is the official extension for Vuetifyjs when working in visual studio code. It provides snippets and autocomplete functionality for Vuetifyjs.

## Changelog for Visual Studio Code
<a href="https://github.com/vuetifyjs/vuetify-vscode/blob/master/CHANGELOG.md" target="_blank">Changelog</a>

## Documentation
All available snippets available for Visual Studio Code [click here](https://github.com/vuetifyjs/vuetify-vscode/blob/master/documentation.md)



## Installation
Install through VS Code extensions. Search for `vuetify-vscode`

[Visual Studio Code Market Place: vuetify-vscode ](https://marketplace.visualstudio.com/items?itemName=vuetifyjs.vuetify-vscode)

Can also be installed using

````
ext install vuetifyjs.vuetify-vscode
````
##  Usage
### Snippet
You don't need usage example if you are familiar with concept of snippets or you looked up the documentation. But here is an example:

Let's suppose you want to insert Button componenet. For that you have to write full component.

````HTML
<v-btn>buttonText<v-btn>
````

But in `vuetify-vscode` only writing `vBtn` will give you all options available for Button component.

Everything is in camel case and with 'v' prefix which is for Vuetifyjs.

If you want to see list of all available props of a component. Just write `v{component-name}Props`. For example : `vBtnProps`,`vAvatarProps` etc.

If you want to insert a component with all of its props. Just write `v{component-name}WithProps`. This will insert component with all of its props. For example : `vBtnWithProps`, `vAvatarWithProps` etc.

### Templates
Every component in the Vuetify have additional code to write inside it. For example the `v-btn-toggle` component have `v-btn` inside it. Thats why `vuetify-vscode` provides templates for them.
The syntax of template is pretty easy. `v{component}Template` or `v{component}Template{availableTemplate}`
For example `vBtnToggleTemplate` will give you following code.

```HTML
<v-btn-toggle mandatory multiple v-model="value">
  <v-btn flat>
    <v-icon>icon</v-icon>
  </v-btn>
  <v-btn flat>
    <v-icon>icon</v-icon>
  </v-btn>
  <v-btn flat>
    <v-icon>icon</v-icon>
  </v-btn>
  <v-btn flat>
    <v-icon>icon</v-icon>
  </v-btn>
</v-btn-toggle>
```
## Upcoming features
- on hover documentation for components and props

## Questions
If you have any questions, ideas or you want to discuss with me. Just raise a issue in `vuetify-vscode` [github repository](https://github.com/vuetifyjs/vuetify-vscode/issues).

## License
[MIT](https://github.com/vuetifyjs/vuetify-vscode/blob/master/LICENSE)