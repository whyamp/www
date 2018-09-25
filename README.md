# Why hate AMP?

## Motivation

This document is to show despite disadvantages there is major advantage of AMP that number of network requests and tracking, data resources are minimal with AMP due to current ad practices.

Please read some good thoughts by Alex Kras at

https://www.alexkras.com/google-amp-is-winning/

## API Reference

https://developers.google.com/amp/cache/reference/acceleratedmobilepageurl/rest/v1/ampUrls/batchGet

## Conditions

```
user-agent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
Firefox-62.0.2
Linux 
uBlock Origin v1.17.0
Privacy Badger 2018.9.20
```


## Example

```
https://www.wired.com/story/google-chrome-login-privacy/
{
  "ampUrls": [
    {
      "originalUrl": "https://www.wired.com/story/google-chrome-login-privacy/",
      "ampUrl": "https://www.wired.com/story/google-chrome-login-privacy/amp",
      "cdnAmpUrl": "https://www-wired-com.cdn.ampproject.org/c/s/www.wired.com/story/google-chrome-login-privacy/amp"
    }
  ]
}
```

## Data


| Website       | Complete page    | AMP from website  | Google-AMP | 
| ------------- | ------------- | -------------      | ------------- | 
| URL           |               requests/size/time                        |
| [Wired](https://www.wired.com/story/google-chrome-login-privacy/) | 60/4.05 MB/12.5s | 22/1 MB/ 1.8s       |  20/1.MB/2s  |
| Content Cell  | Content Cell  | Content Cell       | Content Cell  |
| Content Cell  | Content Cell  | Content Cell       | Content Cell  |
| Content Cell  | Content Cell  | Content Cell       | Content Cell  |
| Content Cell  | Content Cell  | Content Cell       | Content Cell  |

