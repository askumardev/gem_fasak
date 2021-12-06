# gem_fasak

* https://guides.rubygems.org/make-your-own-gem/


* Create a folder
* cd folder
* create .gem spec file using  - `gem build name.gemspec`
  * Successfully built RubyGem
  * Name: name
  * Version: 0.0.0
  * File: name-0.0.0.gem
* write the gem specifications
* mkdir lib
* cd lib
* create a ruby file with .rb extension and implement the code
* cd ..
* gem install ./name-0.0.0.gem
* `curl -u ***** https://rubygems.org/api/v1/api_key.yaml > ~/.gem/credentials; chmod 0600 ~/.gem/credentials`
* `gem push name-0.0.0.gem`
* `gem list -r name`
