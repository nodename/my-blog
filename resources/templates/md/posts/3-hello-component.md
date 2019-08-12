{:title "3. Hello Component"
 :layout :post
 :date "2019-08-04"
 :klipse true
 :tags  ["react"]}

<script src="https://unpkg.com/react@16.0.0-rc.3/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@16.0.0-rc.3/umd/react-dom.production.min.js"></script>

```klipse-jsx
      const rootElement = document.getElementById('root')

      // This version uses a `msg` prop
      // const Message = (props) => <div>{props.msg}</div>

      // const element = (
      //   <div className="container">
      //     <Message msg="Hello World" />
      //     <Message msg="Goodbye World" />
      //   </div>
      // )

      // This version uses the `children` prop, which allows us to
      // use <Message> similarly to HTML, allowing us to nest components:

      const Message = props => <div>{props.children}</div>

      const element = (
        <div className="container">
          <Message>
            Hello World
            <Message>Goodbye World</Message>
          </Message>
        </div>
      )

      ReactDOM.render(element, rootElement)
```

<div id="root"</div>
