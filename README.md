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
| [web.de](https://web.de/magazine/politik/premierministerin-jacinda-ardern-neuseelands-firstbaby-feiert-premiere-un-vollversammlung-33180342#.homepage.channel2_0_Panorama.Baby%20stiehlt%20allen%20die%20Show.1)  | 42/1.2MB/2.2s  | 14/801.kB/0.9s        | 14/823.6kB/1s  |
| [liberation](https://www.liberation.fr/france/2018/09/25/les-effets-pervers-de-parcoursup-etaient-previsibles_1681018)  | 39/1.4MB/2.2s  | 16/758kB/0.85s       |  16/767kB/0.88s  |
| [Guardian](https://www.theguardian.com/commentisfree/2018/sep/25/keir-starmer-brexit-zinger-labour-conference-remain-option-peoples-vote)  | 128/4.87MB/31s | 43/2.7Mb/14s      | 43/2.7MB/17s  |
| Content Cell  | Content Cell  | Content Cell       | Content Cell  |

