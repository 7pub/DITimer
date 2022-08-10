<link rel="stylesheet" type="text/css" href="https://7pub.github.io/timeroll/this.web/template/prism-tomorrow.css" />
<link rel="stylesheet" type="text/css" href="https://7pub.github.io/timeroll/this.web/template/demo.css" />

# Actually render your code blocks

This is my markdown file.

```render
DOM_NODE.innerHTML = 'Hey there!'
```

What About babel?
-----------------

If you want to use babel, make sure to add babel-standalone like this file does at the top:

```render-babel
class Demo extends React.Component {
componentDidMount() {
setInterval(() => this.forceUpdate(), 500)
}
render() {
return <h1>This is cool times {Date.now()}</h1>
}
}

ReactDOM.render(
<Demo/>,
DOM_NODE
)
```

Isn't that

- Cool
- Awesome
- Incredibly inflexible?

Yes.

<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<script src="https://unpkg.com/react@15.6.1/dist/react.min.js"></script>
<script src="https://unpkg.com/react-dom@15.6.1/dist/react-dom.min.js"></script>
