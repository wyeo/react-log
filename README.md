![react-log](https://cloud.githubusercontent.com/assets/5600341/22278164/f1e77fc8-e29f-11e6-98a1-c52703c112e5.png)
> React for the Console

## Install
```sh
yarn add react-log
```
or
```sh
npm install react-log --save
```

## Usage
_react-log_ exports a single React Component called _Log_. Each child will not be rendered on the DOM, but it will produce a analog representation on the console.

No proprietary syntax is needed for child HTML elements. _react-log_ handles the parsing and rendering of native React-DOM elements for you.

Let's see it in action!

### Example

```js
import Log from 'react-log';

//...
<Log>
  <h1
    fontFamily='Open Sans, sans-serif'
    fontWeight='normal'
    fontSize='50px'>
    React
    
    <span
      fontFamily='Arial, Helvetica, sans-serif'
      background='#ffd10b'
      fontSize='45px'
      fontWeight='bold'
      borderRadius='5px'
      marginLeft='10px'
      padding='5px'
      borderBottom='2px solid black'>
      log
    </span>
  </h1>
  <a
    display='block'
    lineHeight='40px'
    href='https://github.com/diegomura/react-log'>
    For more info
  </a>
</Log>
```
[See full example](https://github.com/diegomura/react-log/blob/master/examples/index.js)

#### Output
![banner](https://cloud.githubusercontent.com/assets/5600341/22278337/685d60c2-e2a1-11e6-8097-7774f87e07dd.png)

#### Run the example yourself
On the root of the project:

```sh
cd examples/
npm install
npm start
```

The server should be listening now on `http://localhost:8080`

## Browser Support
Tested and working on Chrome 51 and Firefox 45.
Does not work on Safari or IE as far I've seen. Yet.

## License

MIT © [Diego Muracciole](http://github.com/diegomura)
