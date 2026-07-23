# venera-configs

Configuration file repository for [Venera](https://github.com/venera-app/venera).

## Subscribe

Add the following URL to your Venera app's comic source repository settings:

```
https://cdn.jsdelivr.net/gh/opaiopaio/venera-configs@main/index.json
```

## Create a new configuration

1. Download `_template_.js`, `_venera_.js`, put them in the same directory
2. Rename `_template_.js` to `your_config_name.js`
3. Edit `your_config_name.js` to your needs. 
   - The `_template_.js` file contains comments to help you with that. 
   - The `_venera_.js` is used for code completion in your IDE.
4. Add your source to `index.json`
5. Push to your repository, jsDelivr CDN will update automatically