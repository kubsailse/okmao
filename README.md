


```js
addEventListener(
    "fetch",event => {
    let url=new URL(event.request.url);
    url.hostname="xxx.cloud.okteto.net;
    let request=new Request(url,event.request);
    event. respondWith(
      fetch(request)
    )
  }
)
```

