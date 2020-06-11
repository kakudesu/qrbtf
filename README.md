# QRBTF

QRBTF is a simple online tool to beautify your QR code.

* 8 Art QR Code Styles
* Parametric Design
* No Backend Required
* Support for SVG Downloads

URL: [qrbtf.com](https://qrbtf.com)

中文介绍: [如何制作一个漂亮的二维码](https://mp.weixin.qq.com/s/_Oy9I9FqPXhfwN9IUhf6_g)

<img align="center" src="https://blog.ciaochaos.com/projects/qrcode/qrs2.jpg" width="500">

## QRBTF Website

### Installation

``` bash
git clone https://github.com/ciaochaos/qrbtf.git
cd qrbtf
npm install
npm start
```

### Usage

1. Open [qrbtf.com](https://qrbtf.com).
2. Enter a URL or text.
3. Select a style.
4. Adjust parameters.
5. Download `JPG` or `SVG`.

## React Component (react-qrbtf)

See [github.com/cpunisher/react-qrbtf](https://github.com/cpunisher/react-qrbtf) for more information.

``` bash
npm install react-qrbtf --save
```

### Include the Component

```js
import React from 'react'
import { QRNormal } from 'react-qrbtf'

class Component extends React.Component {
    
    render() {
        return <QRNormal value="https://qrbtf.com" />
    }
}
```

## Examples

<img align="center" src="https://blog.ciaochaos.com/projects/qrcode/qrc2.jpg" width="300">

## Donation

#### Paypal

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.me/ciaochaos)

#### Alipay

<img align="center" src="https://blog.ciaochaos.com/projects/qrcode/alipay2.jpeg" width="300">
