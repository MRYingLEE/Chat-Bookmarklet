# Chat-Bookmarklet
This is an experimental bookmarklet to initiate a web chat of jcbrand/converse.js (https://github.com/jcbrand/converse.js) at book mark bar. In the bookmarklet, you may add some logic to decide which contact/MUC should be chat with and what topic should be pre-defined. Btw, this is a side product of my Hotline.Chat project.

## Bookmarklet
Just add the bookmarklet below to your bookmarks bar.

```javascript
javascript:(function (window, document, undefined) { converse.rooms.open("sales@role.bizchat.us");})(window, document);
```

## Test

1. Add this bookmarklet to your bookmark bar in your browser.
2. Visit https://conversejs.org/.
3. Login to the web chat with any XMPP account.
4. Click the bookmarklet to launch a group chat.

## To Do

1. You may try another popular XMPP web chat Jappix Mini (https://github.com/jappix/jappix).
2. In the bookmarklet, you may add some logic to decide which contact/MUC should be chat with and what of topic should be pre-defined. So although this is a simple demo, you may extend it according to your seneario.
3. You may go further, you may inject a web chat to ANY web page according to the context. For example, when you select a colleague name, click the bookmarklet will launch a web chat with your colleague immediately. A good example is sillero/togetherjs-bookmarklet(https://github.com/sillero/togetherjs-bookmarklet).
