## Instructions

1. **Load up [Jerkmate Ranked](https://jerkmate.com/jerkmate-ranked)**
2. **Open the Developer Console of your browser, and paste the script below:**
  ```js
const config = {
    interval: 1,
    video: document.querySelector("video[poster='/ui-contents/idleposter.jpg']"),
    buttons: Array.from(document.querySelectorAll("button.buttonBuy"))
};

function main() {
    const elements = [
        config.video,
        ...config.buttons
    ];

    for (const element of elements) {
        element.click();
    }
}

setInterval(main, config.interval);
```

3. **Profit**

    You are now at the top of Jerkmate Ranked. Go fap!


## Credits

- [Snipcola](https://github.com/snipcola), for the readme.md template
