[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Protoss78/paper-button-group)

# paper-button-group

This web component is a direct clone from the <a href="https://github.com/PolymerElements/paper-radio-group">PolymerElements/paper-radio-group</a> 
element. Minor code parts where changed to work with paper-buttons instead of
paper-radio-buttons.

`paper-button-group` allows user to select only one button from a set.
Checking one button that belongs to a group unchecks any
previously checked button within the same group. Use
`selected` to get or set the selected button.

Example:

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-button-group.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <style>
        paper-button[toggles] {
            transition: background-color 0.3s;
        }

        paper-button[toggles][active] {
            color: white;
            background-color: var(--paper-green-500);
            --paper-button-flat-focus-color: var(--paper-green-50);
        }

        paper-button:hover {
            background: #eee;
        }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-button-group attr-for-selected="name" selected="c">
    <paper-button name="o" toggles>Oxygen</paper-button>
    <paper-button name="c" toggles>Carbon</paper-button>
    <paper-button name="h" toggles>Hydrogen</paper-button>
    <paper-button name="n" toggles>Nitrogen</paper-button>
    <paper-button name="ca" toggles>Calcium</paper-button>
</paper-button-group>
```
