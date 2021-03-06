# Take off the blindfold

[![Join the chat at https://gitter.im/jaredly/rxvision](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jaredly/rxvision?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

It's easier to understand what's happening if you can look at it.

`rxvision` is a tool to visualize and debug your RxJS reactive streams.

[![screenshot](http://jaredly.github.io/images/pasted-16.png)](https://jaredly.github.io/rxvision)

# The Demo [(see it live)](https://jaredly.github.io/rxvision)

You'll need `browserify`.

```
npm install
make
```

Then you need to run a static server (so ajax will work in the demo). I use
`http-server` (`npm install -g http-server`):

```
http-server -p 4321
```

then open http://localhost:4321/examples/gh-follow/index.html in a browser.

# Usage (so far)
I make no promises, this is very WIP.

- Add `sneak.js` to your page, after `rx.all.js` but before your code.
- run your page, do some things to trigger streams
- run `RxVision.dump()` from the console. Replace `data.json` with the output.
- run `make` again.

That ought to work, but no promises yet. Fire up an issue if it doesn't.



