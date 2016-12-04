This is my selection of relevant Chromium and Firefox intents (from blink-dev and mozilla.dev.platform, respectively); updated weekly (:new: marks latest additions).

***

Jump to section: [Chromium](#chromium) | [Firefox](#firefox)

***

### Chromium

December 2016
- :new: [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gWp3xcyEDJM/JKOu68Y2BQAJ) MediaStreamTrack Content Hints
- :new: [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HZ_ZHEE9oDo/jXunplrqBAAJ) Presentation API 1-UA mode
- :new: [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sa5Tvr4QyWI/Pk_ohqbpBAAJ) Phone number API (a.k.a. Sign up API)

November 2016
- :new: [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5AgbvQwEEdM/bLQcXkF7BAAJ) ReadableStream `pipeTo` and `pipeThrough` methods
- :new: [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kyll3WFKTig/gMNvZ66eBAAJ) PerformancePaintTiming interface (incl. time to first paint)
- :new: [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/npKDoKVOUAs/ogtlIFmLBAAJ) changes to CSP’s model for workers
- :new: [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GAhY5gl8bIs/8eVDOUA8BAAJ) OpenType variable fonts
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vM3RM1OQNFU/ao3wqCM6AgAJ) `<iframe allowpaymentrequest>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OTbGJtwRmXg/RCYzioMlAgAJ) PointerEvent `getCoalescedEvents` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/d2mbqJ0ADXk/MLrTZq1xAwAJ) CSS `text-decoration-*` properties
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Qm_q-LzwnHs/bTh_T0T1AgAJ) CSS `::placeholder` pseudo-element
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kJLzOeS-l4w/Dco5FIcpAwAJ) Remote Playback API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6jK81erL87E/i6t4G9AaAwAJ) CSS `caret-color` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hBx1ffTS9CQ/TMTigaDIAgAJ) CSS Grid Layout
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/qCJhuuZH5p0/le6l1t37AQAJ) Web Authentication API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IoIxRpn6l9g/ux1C1Cj7AQAJ) Payment Request API `canMakeActivePayment` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sTJ0OL9QJx8/DAXDOrIqAQAJ) “Fire `visibilitychange` event on document unloading”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/AT7aqhPcNdw/10jQ2B0HAQAJ) Navigation Timing Level 2
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Hs5-wPpCPZc/7BVwLbfMAAAJ) Resource Timing `nextHopProtocol` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1UkZE-vOROc/gEj7psewAAAJ) CSP's `worker-src` directive
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2ojnMk_T9_c/h7QfIhTeCAAJ) Payment App API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PI3FG54L1ZU/B4jNSzhyCAAJ) navigation preload for service workers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VJmxBRYGVIE/CogbbYWXCAAJ) scroll anchoring

October 2016
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LukPJ86fcs8/RX_dsbUiCAAJ) `<link referrerpolicy>` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/X_vBQp60kp8/v43CLS89CAAJ) CSS `position: sticky` value
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wfIVkXvQ7kQ/VfuOr_FhBwAJ) FIDO U2F API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1kroHAnh3BU/uYZb6uZRBwAJ) Fractional MouseEvent coordinates 
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/6o1W8mVUDsA/JOKZ-aRfBwAJ) KeyboardEvent `isComposing` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/f1zzIHtRomQ/foZ6f5dKBwAJ) WritableStream (part of Streams API)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vNNQ50QRNuY/u6n62FlqBgAJ) CSS `shape` media feature
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VAEv-MUFGC8/n7gz63UfBgAJ) WebGL 2.0 
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/___gftRPAvg/TsANSIDHBQAJ) TLS 1.3 1-RTT (field trial)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/toKFfP_oOac/jde6w6xuBQAJ) ImageBitmap rendering context for `<canvas>`
- [Remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JqUlPA-HFfU/l77tAggtBQAJ) CSP `'referrer'` directive
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nAUxrvJeNLQ/-e1zF6YkBAAJ) CSS `display: contents` value
- [Intervene](https://groups.google.com/a/chromium.org/d/msg/blink-dev/BW3qrkisqIs/v5Au-HVTAwAJ) “Treat touch Scroll-blocking event listeners as passive”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jkHEX_9eOjE/hmlv6sJMBAAJ) `PresentationConnection.url` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Ono3RWkejAA/2skvuBhSCQAJ) Web Bluetooth
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7NzKZKdSyc/HISQnGJXCQAJ) “Render Unicode control characters”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hvN9YVvIb5c/5DrcunKSCAAJ) CSS `system-ui` generic font family
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/y6U-3IGIduM/VxCRbkntBgAJ) Notification API `image` property (“a large image as part of the content of a notification”)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nAM3o4NSMsI/3gRKsOuYBgAJ) durable (persistent) storage
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/j7Oo9JSPY8c/DMNbU2qdBgAJ) customized built-in elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/y4a1OWfMzN0/XFBIp_GIBgAJ) HTTP `Referrer-Policy` header

September 2016
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ip4dmVNr15Y/jyE0Gc8jBQAJ) CSP violation event `disposition` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/3tViQmRF2l8/0hRE9EBUBQAJ) Long Task API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Uzit4zDQ1ps/pD_3k2rqBAAJ) CSS `overscroll-action` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/EVN4Y8NVtNM/VanLZ_1hBAAJ) `pinch-zoom` value for CSS `touch-action` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bck8mCc-HOQ/HUeob0z8AwAJ) Content Security Policy: Embedded Enforcement
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iAIKruoq5QM/Ht0eD081AwAJ) MediaStream Image Capture
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9WIVyDz1T34/5Nmj46UXAwAJ) `MediaStream` constructor
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hdBMDg5Nmok/ZAd7NTgfAwAJ) CSS `text-decoration-skip` property (and default to `ink` value)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UY1EfjaGF_E/OU7W_s3PAgAJ) Pointer Events
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SUF73nqP1P4/2fK1GjVFAgAJ) ECMAScript async functions
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IxyBdzkSU98/LJ12LwjKAAAJ) constructible document with `new Document()`
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zGAzqfi0e00/atXaz8UCAQAJ) WebVR
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/s-w44wOMzqs/tEd_YNjkAAAJ) MediaDevices `devicechange` event
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LsnvY7FFrY0/iVl1FcAFAgAJ) CSS `hyphens` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/GxTBfZjzqFw/dw63GhkrAgAJ) “Process continuous events just before `requestAnimationFrame` occurs”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/JkdoxpINjxQ/CUWOBwc0AgAJ) Shape Detection API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fBfWECEGZa8/Jr_3UDsCAQAJ) AudioWorklets for Web Audio API

August 2016
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_IReUkNKF6o/S1GCeqxMAAAJ) Accelerometer, Gyroscope and Magnetometer Sensor APIs
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/b6UBgAZt1kQ/nZTYfu0AAgAJ) CSS Properties and Values API
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zuqQaLp3js8/5V9wpRWhBgAJ) Web Share API on Android
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/R8OehqGJzt0/x95pHclCBgAJ) `auxclick` event type
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/UpS11lcUkYg/NBFTJMQPBgAJ) IndexedDB object store and index renaming (during version change transactions)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FQxPB5GEQjo/oUJb_54BBgAJ) Notifications API `image` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/lLX_NIuTpkM/-iP0Kq23BQAJ) WebUSB (updated)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P2UKXfsFWWE/Nii0d7snBQAJ) custom elements v1
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uMC1NQP4kpY/Rh8LYedWBAAJ) `once` option for `addEventListener` method
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Yk8u329AmIs/eXTS5WeaAwAJ) media tracks (limited to  1 audio/video track)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zXlpFPXhyvE/PPbUFRAvAgAJ) `dataset` API on SVG elements
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sIzHpZVhmBE/fF0Qf15qAQAJ) foreign fetch and `serviceworker` link relation
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Tf5TwA45W8Q/eycERiHpAAAJ) unprefixed CSS `-webkit-image-set` function
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/A_sM-fu6u50/ao9mnO8SAQAJ) “long task” notifications in Performance Observer
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/A12B1S4eGxY/TECSVggtAAAJ) visual viewport
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/I3FhKqtui_k/YY4AvQq6AAAJ) Budget API

July 2016
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fH5bzd0_lRI/58_8fyxIBwAJ) ParentNode/ChildNode `prepend`/`append`/`before`/`after`/`replaceWith` methods
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/bcD93CiIJHE/2a9_ibfbDQAJ) `pan-up`/`pan-down`/`pan-left`/`pan-right` values for CSS `touch-action` property (follow up)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Z2fllXoSjcU/P-kHtCVJBQAJ) “Allow web pages to request fullscreen while an orientation change event handler is running”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MjeLmhOZKXw/zvlyAsvNBAAJ) `Node.getRootNode` method (was `Node.rootNode`)
- [Implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/N0HybdIpKBs) Content Size Policy
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/IHrxKj4zGjg/LTzEZ2iuAgAJ) Gamepad API extensions (`touched` and `pose` properties)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kJ3FGlUaWHU/BTg1AXx7AQAJ) `BroadcastChannel` API
- [Implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/jyCdW1dHyYA) CSP `require-sri-for` directive
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ysEXU21Dn1Y/2UZUHve_BQAJ) Push API `PushSubscription.options` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/nsmmXIAOil4/Hc1th-x-BQAJ) `"auxclick"` event type (non-primary button click)
- [Implement and ship]() “Block `navigator.vibrate` in cross-origin iframes”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/VhYxkRlfQng/EXRHD7A5BQAJ) `pan-up`/`pan-down`/`pan-left`/`pan-right` values for CSS `touch-action` property

June 2016
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/p1DYoxHlkKg/qxS32AaCAgAJ) PaymentRequest API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/hWT6i_qXcjo/7uN5KoiJAgAJ) `"install"` event for Web App Manifest
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_Lhz8THHk2Q/f8j8E49rAgAJ) timer throttling for hidden, cross-origin frames
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/rBYR3Xd6Skw/oddIWad6AgAJ) Feature Policy
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/-vHFK4g93jA/JW9wAJyKAQAJ) CSS `the text-size-adjust` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zrZRD2ls5tw/ibbjD3cQAQAJ) Shadow DOM v1
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SKLhE1LhjOg/-oIudYzfAAAJ) Media Capture from `<audio>`/`<video>` (“WebRTC streaming of prerecorded content”)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1BOhy5av8MQ/OPPt76oZCQAJ) Web Share API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Umj9iVRJM70/6CG49IswBwAJ) `Referrer-Policy` HTTP header
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WEMnlVIbe70/i2MJcEtNBgAJ) “Do not perform default action on un-trusted events”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/vuYEHSeqonM/JpeLkiJABgAJ) “Web Audio requires user gesture on Android”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Q1cnzNI2GpI/AL_eyUNABgAJ) “Autoplay muted videos on Android” (`<video autoplay muted>`)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/1bdP80f0GVs/U7qIckr-BQAJ) Resource Timing `transferSize`/`encodedBodySize`/`decodedBodySize` properties
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HGh92uMX_kE/zt2TLWgNAgAJ) “Block cross-origin scripts inserted via document.write” (for users on slow connections)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ezyGy6JE7hs/lz5TuPcbGwAJ) Media Capture Depth Stream Extensions (media stream from depth camera)

May 2016
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/L-BRotfWD8U/YiYj6aGCAgAJ) HTTP Alternative Services
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QC5iefctcag/kkoBNliBAgAJ) “External stylesheets in `<body>` do not block paint”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g09B730nI80/tWiUWVWFAQAJ) CSS `nav-up`, `nav-down`, `nav-left`, `nav-right` properties
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/XUNMtri0tI4/qIsHgTWNAQAJ) “Apply `u` flag to `<input pattern>` attribute”
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KoasIWagGsk/ayj7mTF5AAAJ) `allow-presentation` token for `<iframe sandbox>` attribute
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iHXS9S66bAw/BM1mV5BQAAAJ) Resize Observer API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0S-jPuCy8ws/QMUrHFQdBwAJ) “Specifying a `ReadableStream` response body in the `Response` constructor”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/SMlcunoqHl0/-1XtMsPPBgAJ) permission delegation for `<iframe>`s
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0mBO8Q5FhTo/2OagzgagBgAJ) (read-only) `action`/`vibrate` attributes on `Notification` instances
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/OzHI2c2vkEo/9Bz-j4PhBAAJ) “Do not perform default action on untrusted events”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/jlSoAmWa1i4/7xowBIOSBAAJ) ECMAScript async functions (`async` and `await`)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/alcPcPKzzkg/QDDrbz2hAwAJ) IndexedDB Observers
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Y6Q69fwcexo/xq5YCjiRAwAJ) 8 and 4-digit hex color notation (`#RRGGBBAA` and `#RGBA`)
- [Deprecate and remove](https://groups.google.com/a/chromium.org/d/msg/blink-dev/O9_XnDQh3Yk/SI9yuUpjAwAJ) `requestAutocomplete` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/osZzOCF-ONM/RU3h7wiMAwAJ) CSS `font-variant-numeric` property
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5Sihi1iAXYc/SISKuRppAwA) durable storage (`navigator.storage.persist` and `.persisted` methods)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/zLL_d4DLAno/paH269ijAwAJ) Performance Observer API


April 2016
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Wo7fimlUUjc/sN34ExpqAQAJ) Web Push protocol and subscription restrictions
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NHkG8FXFEWU/KLPutppmAQAJ) `Clear-Site-Data` HTTP header
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/TkfdVqYAYiE/xLGN2b1-AAAJ) Generic Sensor and Ambient Light Sensor APIs
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/r4zE8RKB6l4/wg7xJM5HAAAJ) Token Binding
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/MgponsgdJcg/1rFgBswaAAAJ) CSS Containment (`contain` property)
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/QDHX73bCAZc/XKqR4xaKBwAJ) CSS `hyphens` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/5GDO3nt_oDI/n6D838dYBwAJ) `ImageBitmap.close` method
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/g3qEQkTv5dU/V4Ppp1xuBgAJ) `unsafe-dynamic` CSP source expression
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/NDHMUjbHywI/WOJfYG1NBQAJ) `IDBKeyRange.includes` method
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/P6eY26vB91c/Ri4ohXOPBQAJ) Storage Quota Estimation API (`navigator.storage.estimate()`)
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/W6rKEsdQHXE/neTBKQomCAAJ) ECMAScript 2016 exponentiation operator
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/PoHJp1mu4fE/fWlRRIN0BQAJ) `ImageBitmapOptions`
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/WYTiG9h8Xbs/fxbpfZEBBQAJ) Mediastream Image Capture (e.g. taking pictures from a webcam)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/HZ_SDWrDTHo/QV6rBTjIBAAJ) `-webkit-appearance: none` for `<meter>` and `<progress>` elements
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Et8xbBUxrHs/HwdzVp36AgAJ) `HTMLMediaElement.srcObject` for MediaStreams
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/2VWDU83_VzQ/Dw9l33nyAgAJ) CSS `user-select: none` (unprefixed)
- [Experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/i6wQ7PNuMyc/eGfTKYsiAwAJ) WebUSB
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Jhwj8QAYaFY/breWmVLNAgAJ) filters in 2D canvas (`CanvasRenderingContext2D.filter` property)
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0b5Jgk47uMU/ldEJNx94CAAJ) `Node.isConnected` property

March 2016
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7GYNDnQHRCs/BXHM0jn8BgAJ) Fetch API `Request.referrerPolicy` property
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KhRce4bmnb0/h--WcEzKBgAJ) DOM `KeyboardEvent.key` property
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7ZWqizEIK1E/D3rDr_HEAwAJ) multiple audio and video tracks
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/csCtW3M3-wg/H5gEqBVNAwAJ) `SameSite` attribute for cookies
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/9s8Zamqbv34/JngoiqKeAwAJ) inline replies in web notifications
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LqQXLx93mEo/C50y8EiLAQAJ) Visual Viewport API
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/pqUfi_z57OY/8STCiGOCAQAJ) notification badges
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/29oXhN4RJlQ/N5IrEHGCAQAJ) multiple image definitions for notifications
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/D20_5X-2nCk/E7Gd0G8pAQAJ) `HTMLMediaElement.srcObject` for MediaStreams
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FWu2lHOCbNg/eI-cQCqGBQAJ) iterable array-like interfaces
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/FcxvG5Jq4w0/wLWtyndoBAAJ) Intersection Observer
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/cPcOuNxebX0/IEgKQMxvBAAJ) “Disallow `document.open` and `document.write` during unload”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/sBHPRkLbF-E/yWJ4dJ6CBAAJ) “Fire `"visibilitychange"` event on document unloading”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uba6pMr-jec/tXdg6YYPBAAJ) `<script type="module">`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LpXX7Svx8IY/Hu54zinaAwAJ) DOM `.rootNode` property
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/ntyWX1GW4gQ/xaNY_s0yAgAJ) “Correct handling of percentages in children of flex items”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/kX6a99C1FGw/MQSorHYwAQAJ) CORS restrictions on internet-to-intranet connections

February 2016
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Sf1C6blXmUo/bFNlBk1MDwAJ) Remote Playback API
- [Implement and experiment](https://groups.google.com/a/chromium.org/d/msg/blink-dev/0xXsJYdkaWg/2NwHKmZBEAAJ) AppInstalled API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gDokxXYyeSo/uCS1Gq8oDwAJ) `referrerpolicy` attribute
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/yEdXn35VwVw/H9BSdwYhDgAJ) Experimental Framework
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/wdSV0zUuvJQ/Jd7p_mAIDgAJ) `MediaDevices` `'devicechange'` event
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/YIH8CoYVGSg/Di7TsljXDQAJ) “Do not use web page-provided strings for `'beforeunload'` dialogs”
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/Wc71ungGdn4/3Ix2IjnkDQAJ) CSS `@apply` rule
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/8hsz3bOFBpY/kUHDGmTPDQAJ) `EventListenerOptions.passive`
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/gbSs15ZSWtA/JFU3H7fTDQAJ) Payment Request API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/7ouLjWzcjb0/E7YWD1KrDQAJ) Credential Management API
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/mOWCmoEFfS8/VHYbbaohDQAJ) Media capture from `<canvas>` (`captureStream` method )
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/LIqrS6y7AiU/tkcDvyMdDQAJ) CSS `font-variant-caps` property
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/_-RlGYnb5W8/bfFbSGDKCwAJ) CSS Snap Size
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/RrnitB0OElc/rirueVekCwAJ) Basic `InputEvent` interface
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/77188XZG5Lg/OXNW-f51CwAJ) CSS `:dir()` pseudo-class
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/U55OzGb0bQo/bFMINnduCwAJ) Web Animations Level 1, interop with Firefox
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/fv84jWFFovQ/DhjrNXpHCwAJ) `ImageBitmap` options
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ejLQ0y8IVPM/e8X5j6hSCwAJ) Non-document root scrollers
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/HwDRVyP505Q/tgEJY5kYCwAJ) `"serviceworker"` link relationship
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/IM0HxOP7HOA/y8tu6iq1CgAJ) Optional icon URL for notification actions
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/sXT-rWAd0kk/P11TJQKuCQAJ) “Merge `DOMSettableTokenList` into `DOMTokenList`”
- [Experiment](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/coyvHj1u2Z8/aqjyAUuICQAJ) Web Bluetooth API
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/k5n129-lM1A/02Qqlq0SCQAJ) Notification renotify flag
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ghf2Wq4qQ_w/kzVB_nIvCQAJ) Push subscription restrictions and the Web Push protocol
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/E6kHXWv4sJA/7fKGaApzCAAJ) CSS `break-after`, `break-before`, `break-inside` (generic breaking control)
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/bvs8ledF4tU/qC__g3yICAAJ) “`HTMLMediaElement.play()` retuns a promise”

January 2016
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/fePanzKy6ec/fscI5AOoBgAJ) `"notificationclose"` event
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/_nu6HlbNQfo/XzaLNb1bBgAJ) `"preload"` link relationship
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/A4PZz_mXOTg/D9sNjsGWBQAJ) CSS Paint API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/JufzX024oy0/WEOGbN43AwAJ) Brotli (`Accept-encoding: br` on HTTPS connection)
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/8P5RWP_nRTk/7QNvJVrmAgAJ) Unprefixed CSS Multi-column Layout 
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/jRzvehX9U1U/RReEdlqpAgAJ) `ImageBitmap` and `createImageBitmap` method
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ZuseXCSZY2U/p1gLNcCMAgAJ) Media Capture from `HTMLMediaElement`
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/WUUEUWha5cI/lnw0T_5XAgAJ) CSS `column-fill` property
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/XlBHOIOCjUk/1ZidsQfzAQAJ) `FetchEvent.clientId` and `Clients.get(id)` for Service Worker
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/CuOrg2TrnDw/gTgLL59PAQAJ) `EventListenerOptions.passive`
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/64DG7iR5Qjs/HHX2unspAQAJ) “Modify `{add,remove}EventListener` to accept `EventListenerOptions`”
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/QnBcTm29mJU/3fMvH0XuAAAJ) Canvas Hit Regions

December 2015
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/N9a8eAT6Jug/c5LwnvEiBQAJ) CSS `inverted-colors` media feature
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/Vga32co0YMQ/4i6qXvfeAwAJ) Push messaging payloads (`PushEvent.data` property)
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/iJ_enKAj9gE/swGKdCAlAwAJ) CSS Custom Properties Level 1
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/vAWK0ldpyrc/3I_RKXblAgAJ) `i` modifier for attribute selectors
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ckHvzFXn5zQ/ZkzPC--gAgAJ) OffscreenCanvas
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/g_igIzSue40/hpQoZ2oRAgAJ) Cookie prefixes and Strict Secure Cookies
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/kl8ct3ub3a8/-WfzBTkCAgAJ) Worklets
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/FnZBCN4t46w/qn3CtGa5BwAJ) Canvas `toBlob` method
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/AmChp_uVpXU/SNEykhRLBwAJ) Promise rejection tracking events

November 2015
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/sWoR3JJpowc/WCd9GofQBQAJ) `HTMLMediaElement.disableRemotePlayback`
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/76HB0BIxk_o/RTel6y2IBQAJ) Media Stream Recording API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/t9apD7cQb6I/NlTgcjt_BQAJ) Background Sync (one-shot)
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/9W80Kw-z3ss/7CLbeeqGBQAJ) CSS Containment
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/3rsQQJvhY8k/P2cAFq3hAwAJ) `addEventListener`/`removeEventListener` non-optional arguments
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/xEoWkGEd_g4/Pkn_o92EAwAJ) DOMTokenList-based feature detection for `<link>` and `<iframe>`
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/grHZDbldP04/JdsoQ169AQAJ) `URLSearchParams`
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/gDR7v8QBooU/pnA-5jSNAQAJ) suborigins
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/hqW3RGDV8WI/bGe64uK-AQAJ) `"noopener"` link relation

October 2015
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/8iSlPpwokbY/LWMJ8IffDQAJ) notification action buttons
- [Implement and ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/el1cAmGOrvY/0tnBa3bvDAAJ) `"navigate"` mode in `fetch` requests
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/ELz4SxMwa0U/CWsWMGjfCwAJ) Audio Output Devices API
- [Implement](https://groups.google.com/a/chromium.org/d/msg/blink-dev/KpCcUTv1UQ8/aAoXs3UTCwAJ) CSS Typed OM
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/nyo08pwJcfQ/meb49q1yCQAJ) “modify `addEventListener` to accept `EventListenerOptions`”
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/21YdGHt2ogM/pkNLbZftCAAJ) `WindowClient.navigate` method for service workers

September 2015
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/G-hC66MRTso/uVrmHV0NAwAJ) Local Font Access API
- [Ship](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/Md2SYtNazVU/QbN4NGgTAwAJ) durable storage
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/VscIPcVtKrc/VfJHxeGUAgAJ) iterable `NodeList`
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/TZ79t_huYcg/X00beRJmAgAJ) CSS `position: sticky`
- [Implement and ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/uajNnbH8UPU/YBmO4w-yAAAJ) “Allow `data:` and `blob:` schemes in Fetch API”
- [Implement](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/7s4-eQTAxqs/SoahsGpMAQAJ) CSS `font-display`
- [Ship](https://groups.google.com/a/chromium.org/d/msg/blink-dev/iBX_2xfX6jc/Uc0D6jr3AgAJ) `stale-while-revalidate` Cache-control extension

### Firefox

December 2016
- :new: [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/Q-dSrp4PYe4/hS7r9Y3OCwAJ) Presentation API (on Android)

November 2016
- :new: [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/1K_Uq_fx1l4/Yc93M2P2CgAJ) Web2Native Bridge
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/B9bIszPlVX4/3OVBjLBTCQAJ) CSS `background-repeat-x`/`background-repeat-y` and `mask-repeat-x`/`mask-repeat-y` properties
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/n-2o58jcTK8/sFisJf6pCAAJ) Payment Request API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6shk3TZX5vo/avSCrtLCBgAJ) CSS Grid Layout
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/F0rCRF8z87E/CPh7dIJ9BQAJ) Web Authentication API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/PYPzrwNh6kA/_ErvsqkEAwAJ) `requestIdleCallback` function 

October 2016
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Yy4WAqnGxGo/8bUPmXyJBgAJ) `transitionrun`, `transitionstart`, and `transitioncancel` events
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/sfeqeMkyxCI/J04LFWcnBgAJ) TLS 1.3 (draft 16)
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/PhG4Upk4Mo4/ie0Mr2xsBAAJ) CSS `shape-outside` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/mziFttqlkDM/t-CHVMJCBAAJ) Selection API events (`selectionstart`, `selectionchange`)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6CGjsm1XpD4/GDbW6mCDAQAJ) CSS `touch-action` property (only Level 1 values)

September 2016
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/FO-x9WCJfxM/yfH9YpnDBQAJ) CSS `initial-letter` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/UnBVw8R4Kl0/tOIqsr0qBAAJ) global `isSecureContext` property in workers
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/-stfRvwwEHU/J5P1mzlHAwAJ) Storage API `estimate` method
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/dYn5Fel_p-M/3sPPJvLqCQAJ) Canvas 2d context `getTransform`/`setTransform` methods

August 2016
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/ozygu09pg_o/ux577V_zBAAJ) Canvas 2D context `imageSmoothingEnabled` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/PR_AP6i-xIo/YQ_qTJqyBAAJ) `transitionstart` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/S1_0_G6lqAs/7C4P3xb4AwAJ) HTML `minlength` attribute and `tooShort` validity state
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Ja4GCMopHVg/0D2Zu4VNAQAJ) `dataset` API on SVG elements

July 2016
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/YnTqCbrusb0/ENLHDcUhBAAJ) `forEach` method on NodeList and DOMTokenList
- [Ship]() Blink’s Entries API (`webkitGetAsEntry` method) incl. file input `webkitdirectory` attribute
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/UwD8xIPNK0c/CBlM4FxiAwAJ) (unprefixed) CSS `:any-link` pseudo-class
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/mC06HKQ45hs/np7OxIYYCgAJ) MediaDevices `devicechange` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/acFKZpcVw8o/8s9L4lPyCQAJ) MediaStreamTrack `getConstraints` and `getSettings` methods
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/CNmJeMkUv88/oLmZacPECAAJ) CSS Properties and Values API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/U_drxJ1LCQE/YL6TGfELCAAJ) `once` option for `addEventListener` method
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/32Z6O50rM5k/Fbx9lRaQBwAJ) `__Secure-`/`__Host-` cookie prefixes
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/SYEzvXJKw9M/eGhL0RAKBwAJ) CSS `touch-action` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/NGms9X06tW8/ZK5jthS3BQAJ) “Force flattening of `transform-style: preserve-3d` when opacity is applied”

June 2016
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/azNSLhfv978/Rb2evmprBQAJ) Service Worker `WindowClient.navigate` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/6lMOvomdZFU/Q1AScq2SAgAJ) CSS `mask-image` property

May 2016
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/KaFZG0WoJnw/DqI5UA0OPAAJ) filters in 2D canvas
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/jbMO8mkFZwE/ATXLMHECPAAJ) unprefixed CSS `text-align-last` property
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/VzYoDjzn1CE/-YmQS3LpOwAJ) HTMLMediaElement `seekToNextFrame` method (non-standard)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/S4Aicrg9uiA/XRAsBB75OgAJ) `PerformanceObserver` API
- [Unship](https://groups.google.com/d/msg/mozilla.dev.platform/tgXlkRhF6wo/aVVSmT6mOQAJ) HTML microdata API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/ohoKhFTv80w/P8x5ToZ0AAAJ) `space`/`round` values for CSS `background-repeat` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/F0_UbXAfB_4/TvkG6SwbAAAJ) unprefixed CSS `:dir` pseudo-class
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/00Tq2s58GwA/OSO6V33dAAAJ) 8 and 4-digit hex color notation (#RRGGBBAA and #RGBA)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/cOpESN6_osE/W9zB7m3eAAAJ) “sandbox propagates to auxiliary browsing contexts” flag (`allow-popups-to-escape-sandbox` keyword)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/02aLOHxPqKA/6Y673m7eAAAJ) “sandboxed modals” flag (`allow-modals` keyword)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/xgdSNY6-Dn0/ORLCyeu0AAAJ) passive event listeners (`passive` option)
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/YFRTGKaY5-g/vgam5EksAAAJ) `DOMTokenList.prototype.supports` property

April 2016
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/5FwFLRW5bBE/lYHzKIb0AwAJ) Speech Synthesis API
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/2gjY07E0D5E/6MxWoygDAwAJ) `"noopener"` link relation
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/wouDQLBbm9A/D9K5e2PIAQAJ) “Restrict `geolocation.watchPosition` to secure contexts”
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/1cTAxTf916c/-9fwpSORAQAJ) basic shapes (`polygon` et al) for CSS `clip-path` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/q6AQnTEeX6o/dqS48DbtAwAJ) `requestIdleCallback` function 
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/2INRr96R3IU/do-AigNwAwAJ) `Element.animate` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/SeuzXf0mdRs/Z1x-wh-hAwAJ) ParentNode `prepend`, `append`, `before`, `after`, `replaceWith` methods
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/v11adKDvK04/W05rm0f0AgAJ) `document.scrollingElement` property
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/OrUOw3ag258/Te3rqqRLAgAJ) “Treat cookies set over non-secure HTTP as session cookies”
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/FCQSOydoE-8/YeAp3VZIAgAJ) HTML `<details>` and `<summary>` elements
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/d_zmnSd_yts/guM1BxZHAgAJ) CSS `-webkit-text-stroke` property

March 2016
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/eEm0CPr8lGI/x0AZZxzgCAAJ) CSS `-webkit-background-clip: text`
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/RKTuYDrsnvo/ysG8aeLhCAAJ) CSS `text-combine-upright: all`
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/1ExwWZOmV74/BerMieDzBgAJ) `navigator.hardwareConcurrency`
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/uqDMOCfDhMQ/KcGlZnWaBQAJ) Credential Management API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/RN7bLChacKM/EdqbE7i2AwAJ) CSS `color-adjust` property
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/Bp02mJMc7V4/O1iYSRsjAwAJ) Push API in Firefox for Android

February 2016
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/hmFYDmGlzRU/vQNnYWOnAQAJ) `IDBKeyRange.includes()`
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/UWqtgnztHts/ENmvJiSQAQAJ) `fetch()` referrer and Referrer Policy API

January 2016
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Hcudhkexz8A/YvafGQcnAgAJ) `document.elementsFromPoint` method

December 2015
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/969k-Iryiyo/LsqkHKZ0BAAJ) Support for a subset of `-webkit-` prefixed CSS properties and features
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/cTAnBeZFtUE/kx0I4UC-AQAJ) One-off Background Sync API
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/TXFImc_r9Jo/iW_5u0ICCwAJ) `referrerpolicy` attribute
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/IVGEJnQW3Uo/Eu5tvyLmCgAJ) FIDO U2F API

November 2015
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/2gn7ywXZ6e4/5R6JdndvBwAJ) Service Workers with FetchEvent
- [Implement](https://groups.google.com/d/msg/mozilla.dev.platform/b0UMDIasfq8/tW49QLgCBwAJ) HTML `<details>` and `<summary>` elements
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/Udt3psYNFuY/7qDFZK8sBwAJ) `Performance.translateTime` method
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/QFJO6aqQwIs/Miln8pb4BgAJ) CSS `unicode-range` descriptor
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/uWyfl_szAcw/y-2EsjRhBgAJ) CSS Emphasis Marks (`text-emphasis` property)
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/P6_ADO2sOxE/48RwgUE4BAAJ) CSS Mask Image properties
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/bRDUCA4tb84/_c1Ch4T2AQAJ) Web Speech API - Synthesis

October 2015
- [Ship](https://groups.google.com/d/msg/mozilla.dev.platform/BeVaHGEgZNA/vIVnbrLgBwAJ) WebVR 
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/N3i7Yc2UpR0/huNQI2fVBQAJ) `window.orientation` and `'orientationchange'` event
- [Implement and ship](https://groups.google.com/d/msg/mozilla.dev.platform/pH98pOjGgX4/u1D_zBiVBAAJ) `::backdrop pseudo-element` for Fullscreen API
