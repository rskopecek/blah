Spec

Initial thoughts - for better or worse :-)

Code will be hosted on https (cdn) endpoint as it is immutable.  Each concrete implementation of a pattern will reside in a metadata format (json) which will include things like the name, description, params, details, dependancies, tests, source location, and the like. The package should be all inclusive information to use and understand what it is and what it is for.  Namespacing and tagging will be used.  Classes won't exist (thus far).  Functions, data models, etc will be attached to the namespace and tags.  Overriding of functions will be done by more contextual namespacing.  Fast add of patterns/components.  Pluggable styles (typically via CSS) for developer visual preferences.  Natural dependancy injection.

- SSL always enforced
- domain = source authority
- folders = namespace
- name.type (type = pattern) [current version]
- name.type/version


Some patterns:

- Command list/Flow (list of method calls)
- Iterator (probably should be native as iterate-on.command-list)
- Switch/Route (1 switch or 1 if, method call/command list)
- Detect (1 if w/boolean response)
- Data (true type, integrity, mutability, validation etc)
- Calculate/Generate (return result from calculating input [no side effects], incl query)
- Action (specialized method details)
- Map (copy data from 1 object to another)
- Load/Save (transmits/receives from disk, database, http, ftp, etc)
- Notify (send message to person or url)
- Endpoint (cron, api, button click, etc)
- Access (restrictions)
- App (set of endpoints)
