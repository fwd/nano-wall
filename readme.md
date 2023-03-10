![line](https://github.com/fwd/n2/raw/master/.github/line.png)

<h1 align="center">NanoWall.js</h1>

<h3 align="center">Non-custodial, backend-agnostic DOM monetization library.</h3>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

![line](https://github.com/fwd/nano-wall/raw/master/img/wall.png)

![line](https://github.com/fwd/n2/raw/master/.github/line.png)
![line](https://github.com/fwd/nano-wall/raw/master/img/splash2.png)
![line](https://github.com/fwd/n2/raw/master/.github/line.png)
![line](https://github.com/fwd/nano-wall/raw/master/img/splash3.png)

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Live Demo

<a target="_blank" href="https://blog.nano.to">https://wall.nano.to</a>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Install

**Local:**
```html
<script src="/latest.js"></script>
```

**CDN:**
```html
<script src="https://wall.nano.to/latest.js"></script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Paywall

Monetize any DOM element on your website.

> **This library is not for keeping secrets. It is to make it easier for users to support you. Anyone can bypass this kind of  paywall with some tinkering.**

```html
<script>
    nano.paywall({ 
        element: '.premium', // required, all with class .premium
        address: 'YOUR_ADDRESS', // required
        amount: 0.001, // required
        debug: false, // optional
        free: false, // // optional, allow free access
        background: '#000000de', // optional css hex
        text: 'Read Lorem for', // optional
        title: '', // optional
        color: '', // optional
        // endpoint: 'https://nanolooker.com/api/rpc', // optional
        success: (block) => {
            // Element(s) are automatically shown.
            console.log(block)
        }
    })
</script>
```

### Single Charge

Accept one-time Nano payments.

```html
<script>
    // open up popup
    nano.charge({ 
        address: 'YOUR_ADDRESS', // required
        amount: 0.001, // required
        random: true, // recommended
        success: (block) => {
            console.log(block)
        }
    })
</script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### License

**Limited Commercial:**

- ??? Personal & Open Source
- ??? Commercial use where NanoWall.js is **NOT** the end-product.
- ??? Commercial use where NanoWall.js **IS** the end-product.

Contact [@nano2dev](mailto:support@nano.to) for licensing questions.

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Stargazers

[![Stargazers over time](https://starchart.cc/fwd/nano-pay.svg)](https://github.com/fwd/nano-pay)
