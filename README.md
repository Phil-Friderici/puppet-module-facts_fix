# puppet-module-facts_fix

# Module description

Fixes an annoying and confusing display bug that is shown on every run:

`Error: /File[/var/lib/puppet/facts.d]: Could not evaluate: Could not retrieve information from environment production source(s) puppet://puppet-dev3.epk.ericsson.se/pluginfacts`

Just make this pseudo module available to get rid of the error message.

For more information see:
- https://tickets.puppetlabs.com/browse/PUP-3655
- http://www.itkeyword.com/doc/8109446504918750x791/facts-d-pluginfacts-could-not-be-retrieved-during-puppet-run
