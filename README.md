This gem protects you against most opportunistic attacks and is at the same time as simple as possible.

Goes well with [almost-sinatra](https://github.com/rkh/almost-sinatra), [almost-rack](https://github.com/rkh/almost-rack) or [Ruby on Rails](https://github.com/rails/rails). Should work with any Rack-compatible application and most other apps, too.

Usage:

``` ruby
require 'almost-rack-protection'

use Almost::Rack::Protection
run MyApp
```

Protects against:

* SQL injection
* NoSQL injection
* Cross Site Scripting
* Broken Authentication / Session Management
* Insecure Direct Object References
* Login spoofing
* Cross Site Request Forgery
* Security Missconfiguration
* Insecure Cryptographic Storage
* Failure to Restrict URL Access
* Race condition (except in your Rack handler)
* Insufficient Transport Layer Protection
* Unvalidated Redirects and Forwards
* Windows Metafile vulnerability
* Password cracking
* Malicious File Execution
* Reflection attack
* Mass-Assignment Bugs
* CRIME
* Arbitrary code execution
* Buffer overflow
* Metasploit
* Data breach
* Frame injection
* Y2K bug
* Timing Attacks
* Remote file inclusion
* Some DoS attacks
* Off-by-one error
* Shoulder surfing
* Most other CVEs
