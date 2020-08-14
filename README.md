# screen-share
- https://screenshare.netlify.app/
- application for streaming desktop, browser window or browser tabs video to other users
- audio works for Chromium tabs

## motivation
- watch videos together with friends 
- show friends webpages
- use peer to peer


## using
- peer to peer architecture, using [Peer.js](https://peerjs.com/) (WebRTC wrapper)
- front-end created with [IBM Carbon Design](https://www.carbondesignsystem.com/)
- screen capturing by [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API)

## takeaway
- Peer to peer applications => <ins>no need to write or host a server</ins>, WebRTC has potential
- Browsers have powerful API's ([Media Stream API](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API), [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API), ...)
- IBM Carbon Design looks good
- [Netlify](https://www.netlify.com/) is great

## next steps
- Custom player controls
- Better UI, show user what they are recording...
- Stability, sometimes need to press watch button multiple times
- Testing