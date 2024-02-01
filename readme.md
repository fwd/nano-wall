![line](https://github.com/fwd/n2/raw/master/.github/line.png)

<h1 align="center">NanoWall.js</h1>

<h3 align="center">Crypto HTML Paywall</h3>

### Live Demo

<a target="_blank" href="https://blog.nano.to">https://wall.nano.to</a>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Install

```html
<script src="https://pay.nano.to/latest.js"></script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Paywall

Monetize any DOM element on your website.

> **This library is not for keeping secrets. It is to make it easier for users to support you. Anyone can bypass this kind of  paywall with some tinkering.**

```html
<script>
    NanoPay.wall({ 
        element: '.premium', // required, all with class .premium
        address: 'YOUR_ADDRESS', // required
        amount: 0.001, // required
        free: false, // // optional, allow free access
        success: (block) => {
            // Element(s) are automatically shown.
            console.log(block)
        }
    })
</script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

## Sponsor (DigitalOcean)

<a align="center" target="_blank" href="https://m.do.co/c/f139acf4ddcb"><img style="object-fit: contain;
    max-width: 100%;" src="https://github.com/fwd/fwd/raw/master/ads/digitalocean_new.png" width="970" /></a>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### License

**MIT**

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Stargazers

[![Stargazers over time](https://starchart.cc/fwd/nano-pay.svg)](https://github.com/fwd/nano-pay)
