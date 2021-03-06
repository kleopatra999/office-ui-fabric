# Text Field
Allows for the input of text. Can be a single line or multiple lines. Typically used to accept user input within a form.

## Variants

### Default
<!---
{{> TextField props=TextFieldExampleModel}}
--->

### Multiline
<!---
{{> TextField props=TextFieldMultilineExampleModel}}
--->

### Placeholder text
<!---
{{> TextFieldPlaceholderExample props=TextFieldPlaceholderExampleModel}}
--->

### Underlined (@TODO: deprecated?)
<!---
{{> TextField props=TextFieldUnderlinedExampleModel}}
--->

### Underlined
<!---
{{> TextField props=TextFieldTextFieldUnderlinedExampleModel}}
--->

## Using this component
1. Confirm that you have references to Fabric's CSS on your page:
    ```
    <head>
        <link rel="stylesheet" href="fabric.min.css">
        <link rel="stylesheet" href="fabric.components.min.css">
    </head>
    ```
2. Copy the HTML from one of the samples above into your page.
3. Update the `.ms-Label` to contain your label text.

## Dependencies
This component has a dependency on the Label component.
