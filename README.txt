This is the Grails Resources framework.

It provides a DSL for declaring static resources in plugins and in apps, and a mapper artefact that allows other plugins to provide processing of static resources to e.g. minify / zip them.

All processing is performed at runtime once, against files in the server filesystem.

Built-in mappers included in the plugin:

* CSS rewriter (two mappers required, happens automatically)
* Bundler (combines multiple css or js files into one)

See docs at http://grails.org/plugin/resources
