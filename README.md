<h1 align="center">DiscordFreeStickers</h1>

<p id="screenshot" align="center">
<br>
<a href="#screenshot"><img src="/FreeStickers.png" alt="Free Stickers in action." title="I don't have nitro"></a>
<br>
<h1></h1>
</p>
<br>

<td>
<strong>
  <p>Use nitro stickers and all of your Discord server stickers for free with this plugin!</p>

  <p>Animated stickers will be sent as GIFs, non animated stickers are linked like in the free emojis plugin! If a sticker can already be sent, it will go through just fine!</p>
</strong>
  <p>Note: The animated stickers will appear in chat right away for you, but you have to wait a bit for the upload to complete.</p>

</td>

<br>
<br>

#### Used libraries:
- [rlottie](https://github.com/Samsung/rlottie) and their [WASM build](https://github.com/rlottie/rlottie.github.io)
- [gif.js wasm build](https://github.com/jnordberg/gif.js/tree/wasm)
- [apng-js](https://github.com/davidmz/apng-js)

___

# Changes made in fork

Fixed plugin not working anymore after Discord update that re-obfuscated a ton of modules.

Replaced file uploader code in function `swapEnqueueWithUploadAfterRender` with fixed uploader code.

Also put in [ArjhanToteck's PR](https://github.com/An00nymushun/DiscordFreeStickers/pull/32) which fixes an issue where stickers are sent as links even when a sticker is sendable.
