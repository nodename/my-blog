{:title "1. Hello React"
 :layout :post
 :date "2019-08-02"
 :klipse true
 :tags  ["react"]}

<script src="https://unpkg.com/react@16.0.0-rc.3/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@16.0.0-rc.3/umd/react-dom.production.min.js"></script>

```klipse-js
    const rootElement = document.getElementById('root')
    const element = React.createElement('div', {
        // this is the props object
        className: 'container',
        children: ['Hello React']
    })
    ReactDOM.render(element, rootElement)
```

<div id="root"</div>
