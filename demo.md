<link rel="stylesheet" type="text/css" href="https://7pub.github.io/timeroll/this.web/template/prismjs%401.6.0/prism-tomorrow.css" />
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

<script src="https://7pub.github.io/timeroll/this.web/template/babel-standalone@6.26.0/babel.min.js"></script>
<script src="https://7pub.github.io/timeroll/this.web/template/react@15.6.1/react.min.js"></script>
<script src="https://7pub.github.io/timeroll/this.web/template/react-dom@15.6.1/react-dom.min.js"></script>
