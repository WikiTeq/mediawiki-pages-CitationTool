# CitationTool package

`Package` is the installable set of MediaWiki pages. The CitationTool package provides a collection of pages from Wikipedia involved into citation management workflow.

# Requirements

## Extensions

* [Cite](https://www.mediawiki.org/wiki/Special:MyLanguage/Extension:Cite)
* [PageExchange](https://www.mediawiki.org/wiki/Extension:Page_Exchange)
* [ParserFunctions](https://www.mediawiki.org/wiki/Special:MyLanguage/Extension:ParserFunctions)
* [Scribunto](https://www.semantic-mediawiki.org/wiki/Special:MyLanguage/Extension:Scribunto)
* [TemplateData](https://www.mediawiki.org/wiki/Special:MyLanguage/Extension:TemplateData) 
* [TemplateStyles](https://www.mediawiki.org/wiki/Special:MyLanguage/Extension:TemplateStyles)
* [VisualEditor](https://www.mediawiki.org/wiki/Special:MyLanguage/Extension:VisualEditor)

[Read more](https://www.mediawiki.org/wiki/VisualEditor/Citation_tool)

## Configuration settings

* `$wgRestrictDisplayTitle = false;`
* `$wgPFEnableStringFunctions = true;`

# Setup

* add the following to the bottom of your `LocalSettings.php`: `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-CitationTool/master/page-exchange.json';`
* navigate to `Special:Packages` and install the package
* run `php maintenance/runJobs.php`
