# better-discord-css
Block Discord Nitro upsell below the Friends tab!

```
a[href="/store"] {
    display: none !important;
}
```

Add that to your Custom CSS program for Discord, and be free of the annoying Nitro upsell! 

Block the Now Playing section of the Friends tab

```
.scroller__7d20c {
    display: none !important;
}

.nowPlayingColumn__133bf {
    display: none !important;
}
```

Rename the Direct Messages heading of the Friends tab
(Switch "chatz" out for whatever you want)

```
.headerText__99e7c {
    font-size: 0 !important;
}

.headerText__99e7c::before {
    content: "chatz";
    font-size: 16px !important;
    color: inherit !important;
    display: inline-block !important;
}
```

Block the Send Nitro Gift button in the message box

```
[aria-label="Send a gift"] {
    display: none !important;
}
```
Block the Close DM button on DMs (you can still right click and Close DM)

Good for preventing accidental DM closures!

```
.closeButton__972a0 {
    display: none !important;
}
```
