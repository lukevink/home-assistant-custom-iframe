# home-assistant-custom-iframe
Custom iFrame card to be used with Picture elements card

Add the card js to ui-lovelace.yaml,

```yaml
 - type: js
   url: /local/js/custom-iframe-card.js
```

To use with picture-elements, add the following YAML. You can change the size and position, the iFrame will update dynamically to the size you set:

```yaml
type: 'custom:custom-iframe-card'
url: www.google.com
style:
  left: 50%
  top: 50%
  width: 50%
  height: 50%
```
