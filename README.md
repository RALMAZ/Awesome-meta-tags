# Awesome-meta-tags
Awesome collection of meta tags

Lets go
  
#### Standart start  
```html
<!DOCTYPE html>
```
#### Use "lang" to language and "dir" (if right to left)  
```html
<html lang="en" dir="rtl">
```
#### "itemscope" and "itemptime" in head is start Microdata  
```html
<head itemscope itemtype="http://schema.org/Website">
```
#### Standart charset, IE and viewport tag  
```html
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
```
#### Title and microdata  
```html
<title itemprop='name'>Page Title less than 65 characters</title>
```
#### My lovely. Block skype call widget  
```html
<meta name="SKYPE_TOOLBAR" content="SKYPE_TOOLBAR_PARSER_COMPATIBLE" />
```
#### Configuring prefetching (look at https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-DNS-Prefetch-Control) 
```html
<meta http-equiv="x-dns-prefetch-control" content="on">
<link rel="dns-prefetch" href="http://example.com">
```
#### Default core tags in html  
```html
<meta name="description" content="Description of the page less than 150 characters">
<meta name="keywords" content="Word1,word2,word3,word4">

<meta name="subject" content="Your website's subject">
<meta name="copyright"content="Company name">
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">

<meta name="Classification" content="Business">
<meta name="designer" content="">
<meta name="reply-to" content="email@exapmle.com">
<meta name="owner" content="">

<meta name="url" content="http://exapmle.com">
<meta name="identifier-URL" content="http://exapmle.com">

<meta name="directory" content="submission">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">

<meta name="rating" content="General">

<meta name="revised" content="Sunday, July 18th, 2029, 5:15 pm" />
<meta name="revisit-after" content="7 days">

<meta name="author" content="John Doe">
<meta name="generator" content="Name" />
```
#### Link meta-tags  
```html
<link rel="canonical" href="http://example.com/2017/09/a-new-article-to-red.html">
<link rel="shortlink" href="http://example.com/7448" />
<link rel="alternate" href="https://es.example.com/" hreflang="es">

<link rel="me" type="text/html" href="http://example.com/me"/>

<link rel='index' title='Name site' href='http://example.com/' />

<link rel='start' title='News 1' href='http://example.com/news1' />
<link rel='prev' title='News 24' href='http://example.com/news23' />
<link rel='next' title='News 25' href='http://example.com/news25' />

<link rel="search" href="/search.xml" type="application/opensearchdescription+xml" title="Viatropos" />
<link rel="self" type="application/atom+xml" href="http://example.com/?page=3"/>

<link rel="first" href="http://example.com?page=1"/>
<link rel="next" href="http://example.com/?page=4"/>
<link rel="previous" href="http://example.com/?page=2"/>
<link rel="last" href="http://example.com/?page=147"/>

<link rel="EditURI" type="application/rsd+xml" title="RSD" href="http://example.com/?rsd" />
<link rel="pingback" href="http://example.com/ping" />
```
#### Simple index tags  
```html
<meta name="robots" content="index, follow">
<meta name="Googlebot" content="Noindex, Nofollow" />
<meta name="Googlebot" content="Noimageindex" />
<meta name="yandex" content="all"/>
```
#### Cache tags 
```html
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
```
#### If you want reload page every %number% second, use  
```html
<meta http-equiv="refresh" content="30">
```
#### Icon, favicon etc tags  (Fluid-icon - Mac OS icon)
```html
<link rel="icon" type="image/x-icon" href="https://example.com/favicon.ico" />
<link rel="icon" type="image/png" href="https://example.com/favicon.png" />
<link rel="fluid-icon" type="image/png" href="https://example.com/fluid-icon.png" />
```
#### Apple tags  
```html
<link rel="apple-touch-icon" href="/custom-icon.png">

<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="apple-mobile-web-app-title" content="page title">
<meta name="apple-mobile-web-app-orientations" content="portrait-any">
<meta content="yes" name="apple-touch-fullscreen" />

<link rel="shortcut icon" sizes="196x196" href="chromeapp-touch-icon-196x196-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="152x152" href="apple-ipad-retina-ios7-touch-icon-152x152-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="apple-ipad-retina-ios6-touch-icon-144x144-precomposed.png">
<link rel="apple-touch-icon" sizes="120x120" href="apple-iphone4+-ipod-touch-retina-ios7-touch-icon-120x120-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="apple-iphone4+-ipod-touch-retina-ios6-touch-icon-114x114-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="76x76" href="apple-ipad1-ipad2-ipad-mini-non-retina-ios7-touch-icon-76x76-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="apple-ipad1-ipad2-ipad-mini-non-retina-ios6-touch-icon-77x72-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="60x60" href="universal-touch-icon-60x60-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="57x57" href="fallback-touch-icon-57x57-precomposed.png">
<link rel="apple-touch-icon-precomposed" href="fallback-touch-icon-57x57-precomposed.png">
<link rel="shortcut icon" href="fallback-touch-icon-57x57-precomposed.png">

<link rel="apple-touch-startup-image" href="apple-touch-startup-image-1536x2008.png" 
media="(device-width: 768px) and (device-height: 1024px) and (orientation: portrait) and (-webkit-device-pixel-ratio: 2)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-1496x2048.png"
media="(device-width: 768px) and (device-height: 1024px) and (orientation: landscape) and (-webkit-device-pixel-ratio: 2)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-768x1004.png"
media="(device-width: 768px) and (device-height: 1024px) and (orientation: portrait) and (-webkit-device-pixel-ratio: 1)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-748x1024.png"
media="(device-width: 768px) and (device-height: 1024px) and (orientation: landscape) and (-webkit-device-pixel-ratio: 1)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-640x1096.png"
media="(device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-640x920.png"
media="(device-width: 320px) and (device-height: 480px) and (-webkit-device-pixel-ratio: 2)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-320x460.png"
media="(device-width: 320px) and (device-height: 480px) and (-webkit-device-pixel-ratio: 1)">
<link rel="apple-touch-startup-image" href="apple-touch-startup-image-fallback.png">

<meta name="apple-itunes-app" content="app-id=myAppStoreID, app-argument=myURL, affiliate-data=myAffiliateData">

<meta name="format-detection" content="telephone=no">
<meta name="format-detection" content="address=no">      
```
#### IE Mobile (holy-moly)  
```html
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="176" />
<meta name="HandheldFriendly" content="True" />
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
#### Standart start  
```html
<!DOCTYPE html>
```
