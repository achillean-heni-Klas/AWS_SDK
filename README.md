
# **rhythmix.js**

![Node](https://img.shields.io/badge/node-%3E%3D18-green)
![NPM](https://img.shields.io/npm/v/rhythmix)
![License](https://img.shields.io/badge/license-ISC-orange)

lightweight music sequencing library for generative audio in JavaScript.

---

### example

```js
import { Sequence } from "rhythmix"

const seq = new Sequence([60,62,64,67], 120)
seq.on("tick", note => synth.play(note))
seq.start()
```

### features

* minimal MIDI abstraction
* WebAudio + Node.js support
* WebSocket synchronization
* JSON import/export

MIT • [rhythmix.dev](https://rhythmix.dev)

# PR Update: 2025-10-31 20:31:13
