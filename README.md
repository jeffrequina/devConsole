# DevTools Console

### _Debug Easily! Spice up your browser's DevTools console_

# Installation
```jsx
npm i devtool-console
```

![Demo1](https://raw.githubusercontent.com/jeffrequina/devConsole/main/devtool-console-img.png)
![Demo2](https://raw.githubusercontent.com/jeffrequina/devConsole/main/devtool-console-img.png)

# Basic Usage
```jsx
    import console from 'devtool-console'

    console.log('Dev Console Logs goes here')
    console.log({your_object_or_array})
    console.grid(your_object_or_array)
    console.info('Dev Console Logs goes here')
    console.debug(your_object_or_string)
    console.warning('Warning on Component on Mount')
    console.error('Error occurred')
    console.success('Success Log goes here')
    console.banner('Welcome to My Website')

    // print console sample
    console.print.primary('This is Primary')
    console.print.secondary('This is secondary')
    console.print.success('This is success')
    console.print.danger('This is danger')
    console.print.stress('This is stress')
    console.print.dark('This is dark')
    console.print.light('This is light')
    console.print.styled('This is styled',true,'1.5rem',false,true,'yellow','blue')
    console.print.styled('This is another styled',false,'x-large',true,false,'white','steelblue')
```
