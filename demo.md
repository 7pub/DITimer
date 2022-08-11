<link rel="stylesheet" type="text/css" href="this.web/template/prismjs@1.6.0/prism-tomorrow.css"/>
<style>
body {
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
background: hsl(0, 0%, 90%);
}
pre {
color: hsl(0, 0%, 90%);
background: hsl(0, 0%, 10%);
padding: 10px;
border-top-right-radius: 6px;
border-top-left-radius: 6px;
margin-bottom: 0;
}
.render-js {
background: white;
border: 2px solid hsl(0, 0%, 10%);
padding: 10px;
border-bottom-right-radius: 6px;
border-bottom-left-radius: 6px;
}
</style>


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

<script src="this.web/template/babel-standalone%406.26.0/babel.min.js#L1"></script>
<script src="this.web/template/react@15.6.1/react.min.js"></script>
<script src="this.web/template/react@15.6.1/react-dom.min.js"></script>
