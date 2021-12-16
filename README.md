# Hugo Blog

Build locally with `hugo server --buildDrafts --noChmod`

Build for production with `hugo --theme hugo-universal-theme`


```sh
# Development
hugo server --buildDrafts --noChmod --theme hugo-universal-theme

# Full reload on development
hugo server --buildDrafts --noChmod --disableFastRender --theme hugo-universal-theme

# Debugging theme
hugo server --buildDrafts --noChmod --theme ga-hugo-theme
```


Interessante build flags:
  -D, --buildDrafts            include content marked as draft
  -E, --buildExpired           include expired content
  -F, --buildFuture            include content with publishdate in the future
 --disableFastRender      For full rebuilds on change    
 --cleanDestinationDir    remove files from destination not found in static directories
 --noChmod                don't sync permission mode of files
 --noTimes                don't sync modification time of files
 --templateMetrics        display metrics about template executions
 --templateMetricsHints   calculate some improvement hints when combined with 
 -t, --theme strings          themes to use (located in /themes/THEMENAME/)

 --log                        enable Logging
 --logFile string             log File path (if set, logging enabled automatically)
 -v, --verbose                    verbose output
 --verboseLog                 verbose logging