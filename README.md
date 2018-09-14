# Corporate Assets Office Add-in

This project demonstrates distributing your organizations corporate assets (logos, icons, etc.) to your end users from right inside Word.

![Image of Add-in](http://i64.tinypic.com/2h51b3c.png)

___

### Dependencies

```json
"dependencies": {
  "office-ui-fabric-js": "^1.3.0"
}
```

### Configuration

Add links to your assets in the `Images` array at the bottom of `index.html`

```javascript
const Images = [
    'https://seeklogo.com/images/A/apple-logo-52C416BDDD-seeklogo.com.png',
    'https://seeklogo.com/images/A/Apple-logo-4DC2B05F7D-seeklogo.com.png',
    'https://seeklogo.com/images/A/apple-ipad-logo-C44B3CB6BA-seeklogo.com.png',
    'https://seeklogo.com/images/A/apple-pay-logo-51FB613CF0-seeklogo.com.png',
    'https://seeklogo.com/images/A/Apple-logo-08556AB833-seeklogo.com.png',
];
```

### Testing

Testing this application requires you to sideload this add-in. Click the links below to learn how to sideload for your specific platform.

[For Windows](https://docs.microsoft.com/en-us/office/dev/add-ins/testing/create-a-network-shared-folder-catalog-for-task-pane-and-content-add-ins)

[For Mac](https://docs.microsoft.com/en-us/office/dev/add-ins/testing/sideload-an-office-add-in-on-ipad-and-mac)

[For Office Online](https://docs.microsoft.com/en-us/office/dev/add-ins/testing/sideload-office-add-ins-for-testing)