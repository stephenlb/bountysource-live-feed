# Bountysource Live Feed

Live Realtime Feed of all Bountysource Activities.

 1. Create a live stream **writer** using `PubNub` server SDK by Publishing all Activities in a **JSON** object format.
 2. Create a live stream **reader** using `PubNub` client SDK by Subscribing to the channel where activities can be received.  This is in a simple SDK Receiver wrapper format.
 3. Create a UI that shows different and make it availbale on the `gh-pages` GitHub branch as `index.html` entry point.

## PubNub Resources

 1. JavaScript Node.JS SDK - `npm install pubnub -g`
 2. JavaScript WEB SDK - [https://github.com/pubnub/javascript](https://github.com/pubnub/javascript)
