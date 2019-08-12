{:title "cljs-0. Hello World without React"
 :layout :post
 :date "2019-08-05"
 :klipse true
 :tags  ["react"]}

```klipse-cljs
    (let [root (.getElementById js/document "root")]
      (set! (. root -textContent) "Hello, world!"))
```

<div id="root"</div>
