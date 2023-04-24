# headless-qr-webcomponent

A simple web component for QR code generation. Using Rich Harris's [headless-qr](https://github.com/Rich-Harris/headless-qr)

#### Usage

```html
<head>
  <script defer src="/path/to/wc-headless-qr.js"></script>
</head>
  
<body>
  <headless-qr
    url="https://test.com"
    color="#717171"
    background="#f1f1f1"
    size="250px"
    output="svg"
  ></headless-qr>
</body>
```

#### Props

| name       |    type     | default |
| ---------- | :---------: | ------- |
| url        |   string    |         |
| background |   string    | #FFFFFF |
| color      |   string    | #000000 |
| size       |   string    | 250px   |
| output     | svg or html | svg     |
