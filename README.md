```javascript
for (var i = 0; i < names.length; i++) {
  var firstLetter = names[i].charAt(0).toLowerCase();

  if (firstLetter === 'j') {
    // Use byeSpeaker's speak method
    byeSpeaker.speak(names[i]);
  } else {
    // Use helloSpeaker's speak method
    helloSpeaker.speak(names[i]);
  }
}
```
