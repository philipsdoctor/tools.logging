# Logging

Forked from https://github.com/clojure/tools.logging/

Addresses the following problem:  When using a custom logger, SLF4J can/will relace it with a no-op logger at run time.  This requires a multi-step configuration which must be performed programatically.  This exposes a method to reinit the logger to perform a multi-step config based on either a supplied path argument, or an environment variable.

## License

Copyright © 2009 Alex Taggart

Licensed under the EPL. (See the file epl.html.)
