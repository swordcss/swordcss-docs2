# Configuration

## Default Configuration

```json
{
  "useClass": true,
  "useConstant": true,
  "useId": true,
  "useQuery": true,
  "useVariable": true,
  "minify": false
}
```

## Changing Configuration

**WARNING: `setOpts` will only create a new `SwordCSS` instance with the new options, it won't set it's current options**

You can change the configuration of a `SwordCSS` object.

```js
sword.setOpts({ ...newOpts });
```
