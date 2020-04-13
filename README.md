# Proxy and Cache Server for Google Maps Web Services

## To start dev server
1. Open Google Cloud Shell
2. Clone repo
```git clone https://github.com/mfarix/google-maps-api-proxy.git```
3. Replace the `YOUR_API_KEY` in [proxy.go](proxy.go) file with an actual Google Maps API key
4. Run ```goapp serve```

## To test
1. Click on Preview on port 8080 (opens a new tab)
2. Append `&location=-33.8594663,151.1927602&radius=500` to the URL in new tab
3. New URL will look as follows `https://8080-dot-xxxxxxxx-dot-devshell.appspot.com/?authuser=0&location=-33.8594663,151.1927602&radius=500`

## Reference
- [Google Maps API Key Best Practices](https://developers.google.com/maps/api-key-best-practices)
- [Google Codelabs](https://codelabs.developers.google.com/codelabs/google-maps-web-services-proxy/index.html)
