# # React Copy to Clipboard Component - Just in One Click!

A lightweight and easy-to-use React component to copy text to the clipboard with just one click.


# Features

-   **Simple Integration**: Easily integrate into any React project.
-   **Minimal Dependencies**: No external CSS or libraries required.
-   **Customizable**: Set custom text length, title display, and inline styles.

## Installation

Install the component via npm:

    npm install react-copy-to-clipboard-component


## Usage

Import and use the `CopyToClipboard` component in your React project:

    import React from 'react';
    import { CopyToClipboard } from 'react-copy-to-clipboard-component';
    const App = () => (
    <div>
	    <h1>Copy to Clipboard Example</h1>
	    <CopyToClipboard textToCopy="Hello World" />
    </div>
    );
    export default App;
    
    
   
   
## Demo

Here's a quick demo of the `CopyToClipboard` component in action:

![copy](https://github.com/user-attachments/assets/c6379c55-caab-4f91-85c1-9b5e1fdbb06c)

## Props

-   **textToCopy** (`string`): The text to be copied to the clipboard.
-   **textLength** (`number`, optional): The maximum length of the displayed text. If not provided, the full text will be displayed.
-   **showTitle** (`boolean`, optional): Whether to show the full text as a title on hover. Default is `false`.
-   **customStyle** (`object`, optional): Custom inline styles for the span element. Default is an empty object.

## Example

    import React from 'react';
    import { CopyToClipboard } from 'react-copy-to-clipboard-component';
    
    const ExampleComponent = () => {
    return (
    <div>
	     <h2>Copy to Clipboard Demo</h2>
		     <CopyToClipboard
		      textToCopy="This is the text to copy!"
		       textLength={10}
		       showTitle={true}
		        />
		      </div>
         );
       };
     export default ExampleComponent;

## Demo 2
Here's a quick demo of the `CopyToClipboard` component in action with the `textLength` and `showTitle` props:
In this demo, you can see how the component truncates the text to the specified length and displays the full text as a title on hover.

![copy2](https://github.com/user-attachments/assets/d161d276-e11c-4df8-bd19-103138e16568)



     




    




## License

Copyright © 2024, [Sonu Mahto](https://github.com/sonu-mern). Released under the [MIT License]



