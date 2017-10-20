# Awesome meta tags  
Awesome collection of meta tags  

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()

#### Standart start  
```html
<!DOCTYPE html>
```
#### Use "lang" to language and "dir" (if right to left)  
```html
<html lang="en" dir="rtl">
```
#### Microdata start - "itemscope" and "itemptime" in head   
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
#### Disable skype call widget  
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

<meta name="renderer" content="webkit" />

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
#### Orientation  
```html
<meta name="screen-orientation" content="portrait" />
<meta name="x5-orientation" content="portrait" />
<meta name="full-scerrn" content="yes" />
<meta name="x5-fullscreen" content="ture" />
<meta name="x5-page-mode" content="app" />
<meta name="browsermode" content="application">
```
#### If you want reload page every %number% second, use  
```html
<meta http-equiv="refresh" content="30">
```
#### If you want disable night mode  
```html
<meta name="nightmode" content="enable/disable">
```
#### Icon, favicon etc tags  (Fluid-icon - Mac OS icon)
```html
<link rel="icon" type="image/x-icon" href="https://example.com/favicon.ico" />
<link rel="icon" type="image/png" href="https://example.com/favicon.png" />

<link rel="fluid-icon" type="image/png" href="https://example.com/fluid-icon.png" />

<link href="favicon-16.png" rel="icon" type="image/png" sizes="16x16">
<link href="favicon-32.png" rel="icon" type="image/png" sizes="32x32">
<link href="favicon-48.png" rel="icon" type="image/png" sizes="48x48">
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
<meta name="format-detection" name="email=no" />      
```
#### Android tags  
```html
<meta name="viewport" content="target-densitydpi=device-dpi">
<meta name="theme-color" content="red">
<meta name="mobile-web-app-capable" content="yes">
<link href="icon-192x192.png" rel="icon" sizes="192x192">
<link href="icon-128x128.png" rel="icon" sizes="128x128">
```
#### IE Mobile tags (holy-molly)
```html
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="176" />
<meta name="HandheldFriendly" content="True" />
<meta http-equiv="imagetoolbar" content="false">
<meta http-equiv="cleartype" content="on"/>
<meta http-equiv="msthemecompatible" content="no"/>
```
#### MS Windows app tags  
```html
<meta http-equiv="Page-Enter" content="RevealTrans(Duration=2.0,Transition=2)" />
<meta http-equiv="Page-Exit" content="RevealTrans(Duration=3.0,Transition=12)" />
<meta name="mssmarttagspreventparsing" content="true">
<meta name="msapplication-starturl" content="http://example.com/"/>
<meta name="msapplication-window" content="width=800;height=600"/>
<meta name="msapplication-navbutton-color" content="#000000">
<meta name="application-name" content="Words name"/>
<meta name="msapplication-tooltip" content="Word and word"/>
<meta name="msapplication-task" content="name=About;action-uri=/about/;icon-uri=/images/about.ico" />
<meta name="msapplication-tap-highlight" content="no">
```
#### Og tags (Facebook)  
```html
<meta name="og:title" content="The Rock"/>
<meta name="og:type" content="movie"/>
<meta name="og:url" content="http://www.imdb.com/title/tt0117500/"/>
<meta name="og:image" content="http://ia.media-imdb.com/rock.jpg"/>
<meta name="og:site_name" content="IMDb"/>
<meta name="og:description" content="A group of U.S. Marines, under command of..."/>

<meta name="fb:page_id" content="43929265776" />

<meta name="og:email" content="me@example.com"/>
<meta name="og:phone_number" content="650-123-4567"/>
<meta name="og:fax_number" content="+1-415-123-4567"/>

<meta name="og:latitude" content="37.416343"/>
<meta name="og:longitude" content="-122.153013"/>
<meta name="og:street-address" content="1601 S California Ave"/>
<meta name="og:locality" content="Palo Alto"/>
<meta name="og:region" content="CA"/>
<meta name="og:postal-code" content="94304"/>
<meta name="og:country-name" content="USA"/>

<meta property="og:type" content="game.achievement"/>
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT"/>

<meta property="og:video" content="http://example.com/awesome.swf" />
<meta property="og:video:height" content="640" />
<meta property="og:video:width" content="385" />
<meta property="og:video:type" content="application/x-shockwave-flash" />
<meta property="og:video" content="http://example.com/html5.mp4" />
<meta property="og:video:type" content="video/mp4" />
<meta property="og:video" content="http://example.com/fallback.vid" />
<meta property="og:video:type" content="text/html" />

<meta property="og:audio" content="http://example.com/amazing.mp3" />
<meta property="og:audio:title" content="Amazing Song" />
<meta property="og:audio:artist" content="Amazing Band" />
<meta property="og:audio:album" content="Amazing Album" />
<meta property="og:audio:type" content="application/mp3" />
```
#### Twitter tags  
```html
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@site_account">
<meta name="twitter:creator" content="@individual_account">
<meta name="twitter:url" content="https://example.com/page.html">
<meta name="twitter:title" content="Content Title">
<meta name="twitter:description" content="Content description less than 200 characters">
<meta name="twitter:image" content="https://example.com/image.jpg">
```
#### Google+ tags  
```html
<meta itemprop="name" content=""/>
<meta itemprop="description" content=""/>
<meta itemprop="image" content=""/>
```
#### Swift tags  
```html
<meta class="swiftype" name="title" data-type="string" content="page title" />
<meta class="swiftype" name="body" data-type="text" content="this is the body content" />
<meta class="swiftype" name="url" data-type="enum" content="http://www.swiftype.com" />
<meta class="swiftype" name="price" data-type="float" content="3.99" />
<meta class="swiftype" name="quantity" data-type="integer" content="12" />
<meta class="swiftype" name="published_at" data-type="date" content="2013-10-31" />
<meta class="swiftype" name="store_location" data-type="location" content="20,-10" />
<meta class="swiftype" name="tags" data-type="string" content="tag1" />
<meta class="swiftype" name="tags" data-type="string" content="tag2" />
```
#### DC tags  
```html
<meta name="DC.Title" content="Page title">
<meta name="DC.Creator" content="Creator name">
<meta name="DC.Subject" content="Page subject">
<meta name="DC.Description" content="Page description">
<meta name="DC.Publisher" content="Name publisher">
<meta name="DC.Contributor" content="Name contributor">
<meta name="DC.Date" content="Date post page">
<meta name="DC.Type" content="Type site">
<meta name="DC.Format" content="Format site">
<meta name="DC.Identifier" content="http://example.com/this/page/">
<meta name="DC.Source" content="Data source">
<meta name="DC.Language" content="en">
<meta name="DC.Coverage" content="Geo">
<meta name="DC.Rights" content="Copiright">
```
#### Supposedly prevents your site from being set in an iframe  
```html
<meta http-equiv="window-target" content="_top">
```
#### Pinned Sites 
```html
<meta name="application-name" content="Application Name">
<meta name="msapplication-tooltip" content="Tooltip Text">
<meta name="msapplication-starturl" content="/">
```
#### Pinned Tab  
```html
<link href="path/to/icon.svg" rel="mask-icon" size="any" color="red">
```
#### Imagemode - show image even in text only mode  
```html
<meta name="imagemode" content="force">
```
#### UC Mobile Browser  
```html
<meta name="full-screen" content="yes">
<meta name="browsermode" content="application">
<meta name="viewport" content="uc-fitscreen=yes"/>
```
#### Manifest.json  
```html
<link href="/manifest.json" rel="manifest">
```
#### HTML5 Shim  
```html
<!--[if lt IE 9]> 
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script> 
<![endif]-->
```
#### CSRF  
```html
<meta name="csrf-param" content="authenticity_token"/>
<meta name="csrf-token" content="/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc="/>
```
#### Other tags  
```html
<meta name="google-analytics" content="1-AHFKALJ"/>
<meta name="disqus" content="abcdefg"/>
<meta name="uservoice" content="asdfasdf"/>
<meta name="mixpanel" content="asdfasdf"/>
<meta name="microid" content="mailto+http:sha1:e6058ed7fca4a1921cq91d7f1f3b8736cd3cc1g7" />
<meta name="tweetmeme-title" content="Title" />
<meta name="blogcatalog" />
```
#### JSON-LD data  
```html
<script type="application/ld+json"> 
{
  "@context": "http://www.schema.org",
  "@type": "WebSite",
  "name": "Title",
  "url": "http://exapmle.com"
}
</script>
```

___
### Contribution  
Your contributions and suggestions are heartily welcome
