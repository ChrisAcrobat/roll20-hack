# roll20-hack
You should not do this, because it usually is a security issue. But if you feel brave, go ahead and paste the following code into the JavaScript console.
```JavaScript
['https://chrisacrobat.github.io/roll20-hack/hack.js'].map(u=>{s=document.createElement('script');s.setAttribute('src',u);document.head.appendChild(s)})
```
