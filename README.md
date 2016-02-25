# Chat-Bookmarklet
This is a bookmarklet to initiate a web chat of jcbrand/converse.js (https://github.com/jcbrand/converse.js). Usually people start chat by choosing a contact or MUC (group chat) in the chat app at first. This bookmarklet starts at book mark bar. Btw, this is a side product of my RoleChat project (https://RoleChat.biz or https://Hotline.Chat).

## Bookmarklet
javascript:(function (window, document, undefined) { converse.rooms.open("sales@role.bizchat.us");})(window, document);

## Test

1. Add this bookmarklet to your bookmark bar in your browser.
2. Visit https://conversejs.org/.
3. Login to the web chat with any XMPP account.
4. Click the bookmarklet to launch a group chat.

## Usage

In the bookmarklet, you may add some logic to decide which contact/MUC should be chat with and what of topic should be pre-defined. So although this is a simple demo, you may extend it according to your seneario.

You may go further, you may inject a web chat to ANY web page according to the context. For example, when you select a colleague name, click the bookmarklet will launch a web chat with your colleague immediately.
