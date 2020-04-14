# home-assistant-custom-iframe
Custom iFrame card to be used with Picture elements card

Add the card js to ui-lovelace.yaml,

```yaml
 - type: js
   url: /local/js/custom-iframe-card.js
```

To use with picture-elements, add the following YAML. You can change the size and position, the iFrame will update dynamically to the size you set:

```yaml
type: 'custom:custom-iframe'
url: www.google.com
style:
  left: 50%
  top: 50%
  width: 50%
  height: 50%
```

**Note, it will hide all shadows and backgrounds by default to make a clean card for Picture Elements.

Used here in my own config to show my nightscout sugar levels:
![preview.png](https://github.com/lukevink/home-assistant-custom-iframe/blob/master/preview.png?raw=true?raw=true)
