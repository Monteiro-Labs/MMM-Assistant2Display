# MMM-Assistant2Display

Dev repository module to display in IFRAME
* PHOTOS (not set yet)
* WEB LINKS with auto-scrolling (Done)

FROM MMM-AssistantMk2

Needed : AMk2 v3.1.1-0dev with `responseConfig: { useA2D: true }`

```js
        {
           module: "MMM-Assistant2Display",
           config: {
             ui: "AMk2", // ui of AMk2 (available: Classic/Classic2/Fullscreen or AMk2 for automatic choice from AMk2 config)
             debug:true, // debug mode
             verbose: false, // verbose of A2D Proxy
             displayDelay: 30 * 1000, // delay before closing iframe in ms
             scrollSpeed: 15, // scroll speed High number is low speed recommanded 15 
             scrollStart: 1000, // delay before scrolling in ms (after loaded url)
             proxyPort: 8081 // A2D proxy port
          }
        },
```

* Last Configuration update : 20/02/28
* Note: module position not needed because only with iframe
