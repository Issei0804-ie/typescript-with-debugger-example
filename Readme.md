## typescript-with-debugger-example

A aim of the repository is building typescript environment using debugger.

Description is [here](https://scrapbox.io/issei-ie-public/%E3%83%87%E3%83%90%E3%83%83%E3%82%AC%E3%82%92%E7%94%A8%E3%81%84%E3%81%9FTypeScript%E3%81%AE%E3%83%87%E3%83%90%E3%83%83%E3%82%B0%E6%96%B9%E6%B3%95)(sorry, japanese only..)

## How to set up it

### My environment 
- pnpm(v8.6.12)
- node(v18.17.1)

I recomend to use pnpm, but it may can build a environment.

### Install dependencies and build

```
git clone https://github.com/Issei0804-ie/typescript-with-debugger-example.git
cd typescript-with-debugger-example
pnpm i
pnpm tsc
```

### Debug

```
node --inspect-brk helloworld.js
```

And you access `chrome://inspect` on chrome.
