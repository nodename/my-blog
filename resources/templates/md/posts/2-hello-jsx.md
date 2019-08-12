{:title "2. Hello JSX"
 :layout :post
 :date "2019-08-03"
 :klipse true
 :tags  ["react"]}

<script src="https://unpkg.com/react@16.0.0-rc.3/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@16.0.0-rc.3/umd/react-dom.production.min.js"></script>

```klipse-jsx
    const rootElement = document.getElementById('root')
    const props = {
        className: 'container',
        children: 'Hello JSX'
    }
    const element = <div { ...props } />
    ReactDOM.render(element, rootElement)
```

<div id="root"</div>
