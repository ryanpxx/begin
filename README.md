## What is this?

This is the Bootstrap3 based theme for [Hugo](https://gohugo.io/).  

This theme "begin" was forked from [here](https://github.com/dim0627/hugo_theme_beg) 
and subsequently modified for my needs.

## Changelog

The following provides an overview of my changes:

1. Footer is now a simple partial that takes the following parameters:
 
``` 
 [params]
     footerImprintLabel = "Impressum"
     footerPrivacyLabel = "Datenschutzerklärung"
     footerLicenseLabel = "Lizenz"
```

2. Modified the sidebar and listing templates such that pages can be optionally excluded from the listing. Adding the following parameter to a page's frontmatter will exclude it:

``` 
ExcludeFromPostListing: "true"
``` 

3. Removed significant amounts of formatting from the listing pages for a cleaner, simpler article listing.

