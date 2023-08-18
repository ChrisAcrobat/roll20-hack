# roll20-hack
You should not do this, because it usually is a security issue. But if you feel brave, go ahead and paste this line into the JavaScript console:
```JavaScript
[document.createElement('script')].map(s=>{s.setAttribute('src','https://chrisacrobat.github.io/roll20-hack/hack.js');document.head.appendChild(s)})
```
