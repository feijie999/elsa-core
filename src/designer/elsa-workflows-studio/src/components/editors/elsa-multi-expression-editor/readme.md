# elsa-multi-expression-editor



<!-- Auto Generated Below -->


## Properties

| Property            | Attribute        | Description | Type                         | Default               |
| ------------------- | ---------------- | ----------- | ---------------------------- | --------------------- |
| `context`           | `context`        |             | `string`                     | `undefined`           |
| `defaultSyntax`     | `default-syntax` |             | `string`                     | `SyntaxNames.Literal` |
| `editorHeight`      | `editor-height`  |             | `string`                     | `'6em'`               |
| `expressions`       | --               |             | `{ [key: string]: string; }` | `{}`                  |
| `fieldName`         | `field-name`     |             | `string`                     | `undefined`           |
| `isDisabled`        | `is-disabled`    |             | `boolean`                    | `undefined`           |
| `label`             | `label`          |             | `string`                     | `undefined`           |
| `singleLineMode`    | `single-line`    |             | `boolean`                    | `false`               |
| `supportedSyntaxes` | --               |             | `string[]`                   | `[]`                  |
| `syntax`            | `syntax`         |             | `string`                     | `undefined`           |


## Events

| Event               | Description | Type                  |
| ------------------- | ----------- | --------------------- |
| `expressionChanged` |             | `CustomEvent<string>` |
| `syntaxChanged`     |             | `CustomEvent<string>` |


## Dependencies

### Used by

 - [elsa-property-editor](../elsa-property-editor)
 - [elsa-switch-cases-property](../properties/elsa-switch-cases-property)

### Depends on

- [elsa-expression-editor](../elsa-expression-editor)

### Graph
```mermaid
graph TD;
  elsa-multi-expression-editor --> elsa-expression-editor
  elsa-expression-editor --> elsa-monaco
  elsa-expression-editor --> context-consumer
  elsa-property-editor --> elsa-multi-expression-editor
  elsa-switch-cases-property --> elsa-multi-expression-editor
  style elsa-multi-expression-editor fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
