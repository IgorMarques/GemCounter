# SlackAndGemsCounter
Random project that, given an specific json with the blame of the gemfile of a group of projects, counts each time each developer added a gem to each project. Can also count some slack stuff (mentions per user, @channels per user and messages sent by user, all by channel).

##Outputs

###Gems

```
-----Igor Marques da Silva-----

GEMS:

rails: 1 - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable produc
sass-rails: 2 - Sass adapter for the Rails asset pipeline.
uglifier: 2 - Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
coffee-rails: 2 - CoffeeScript adapter for the Rails asset pipeline.
chosen-rails: 2 - Chosen is a javascript library of select box enhancer for jQuery and Protoype. This gem integrates Ch
jquery-rails: 2 - This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application.
turbolinks: 1 - Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)
jbuilder: 2 - Create JSON structures via a Builder-style DSL
sdoc: 2 - rdoc generator html with javascript search index.
spring: 2 - Rails application preloader
friendly_id: 1 - FriendlyId is the "Swiss Army bulldozer" of slugging and permalink plugins for
Active Record. It lets
simple_form: 1 - Forms made easy!
devise: 2 - Flexible authentication solution for Rails with Warden
bootstrap-sass: 1 - Twitter's Bootstrap, converted to Sass and ready to drop into Rails or Compass
autoprefixer-rails: 1 - Parse CSS and add vendor prefixes to CSS rules using values from the Can I Use website.
carrierwave: 1 - Upload files in your Ruby applications, map them to a range of ORMs, store them on different backends
font-awesome-sass: 3 - Font-Awesome SASS gem for use in Ruby projects
seedbank: 1 -
    Extends Rails seeds to split out complex seeds into multiple
    files and lets each environment
draper: 1 - Draper adds an object-oriented layer of presentation logic to your Rails apps.
cancancan: 2 - Continuation of the simple authorization solution for Rails which is decoupled from user roles. All p
kaminari: 1 - Kaminari is a Scope &amp; Engine based, clean, powerful, agnostic, customizable and sophisticated pag
newrelic_rpm: 1 - New Relic is a performance management system, developed by New Relic,
Inc (http://www.newrelic.com).
validates_cpf_cnpj: 1 - CPF and CNPJ validations for ActiveModel and Rails
factory_girl: 1 - factory_girl provides a framework and DSL for defining and
                      using factories - le
maskedinput-rails: 1 - jquery.maskedinput for rails.
valid_email: 1 - ActiveModel Validation for email

TOTAL: 26

-----Marcos Siqueira Jr-----

GEMS:

rails4-autocomplete: 1 - Use jQuery's autocomplete plugin with Rails 4.

TOTAL: 1

-----Lucas Bibiano-----

GEMS:

rails: 2 - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable produc
unicorn: 1 - \Unicorn is an HTTP server for Rack applications designed to only serve
fast clients on low-latency,
draper: 1 - Draper adds an object-oriented layer of presentation logic to your Rails apps.
devise: 1 - Flexible authentication solution for Rails with Warden
rest_client: 1 - Same as rest-client, but removes mime-types dependency. -- A simple HTTP and REST client for Ruby, in
carrierwave: 1 - Upload files in your Ruby applications, map them to a range of ORMs, store them on different backends
fog: 1 - The Ruby cloud services library. Supports all major cloud providers including AWS, Rackspace, Linode,
ransack: 1 - Ransack is the successor to the MetaSearch gem. It improves and expands upon MetaSearch's functionali
simple_form: 1 - Forms made easy!
sass-rails: 1 - Sass adapter for the Rails asset pipeline.
bootstrap-sass: 1 - Twitter's Bootstrap, converted to Sass and ready to drop into Rails or Compass
bootswatch-rails: 1 - Bootswatches converted to SCSS ready to use in Rails asset pipeline.
uglifier: 1 - Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
coffee-rails: 1 - CoffeeScript adapter for the Rails asset pipeline.
jquery-rails: 1 - This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application.
turbolinks: 1 - Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)
jbuilder: 1 - Create JSON structures via a Builder-style DSL
sdoc: 1 - rdoc generator html with javascript search index.
rails_12factor: 1 - Run Rails the 12factor way

TOTAL: 19

-----Iago-----

GEMS:

bootstrap-sass: 1 - Twitter's Bootstrap, converted to Sass and ready to drop into Rails or Compass
simple_form: 1 - Forms made easy!
validates_cpf_cnpj: 1 - CPF and CNPJ validations for ActiveModel and Rails
momentjs-rails: 1 -     Moment.js is a lightweight javascript date library for parsing, manipulating, and formatting date
bootstrap-daterangepicker-rails: 1 - Rails 4.1.x plugin to allow for the easy use of Dan Grossman's Bootstrap DateRangePicker
kaminari: 1 - Kaminari is a Scope &amp; Engine based, clean, powerful, agnostic, customizable and sophisticated pag
has_scope: 1 - Maps controller filters to your resource scopes
draper: 1 - Draper adds an object-oriented layer of presentation logic to your Rails apps.

TOTAL: 8

-----Luiz Rogério-----

GEMS:

rails_12factor: 1 - Run Rails the 12factor way

TOTAL: 1

-----Higorhicaro-----

GEMS:

rails: 1 - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable produc
draper: 1 - Draper adds an object-oriented layer of presentation logic to your Rails apps.
uglifier: 1 - Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
coffee-rails: 1 - CoffeeScript adapter for the Rails asset pipeline.
jquery-rails: 1 - This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application.
turbolinks: 1 - Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)
jbuilder: 1 - Create JSON structures via a Builder-style DSL
rails_12factor: 1 - Run Rails the 12factor way
bootstrap-sass: 1 - Twitter's Bootstrap, converted to Sass and ready to drop into Rails or Compass
simple_form: 1 - Forms made easy!
puma: 1 - Puma is a simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications. P
magic_encoding: 1 - Easily add magic comments for encoding on multiple ruby source files
bootswatch-rails: 1 - Bootswatches converted to SCSS ready to use in Rails asset pipeline.
coveralls: 1 - A Ruby implementation of the Coveralls API.
devise: 1 - Flexible authentication solution for Rails with Warden
chosen-rails: 1 - Chosen is a javascript library of select box enhancer for jQuery and Protoype. This gem integrates Ch
nested_form: 1 - Gem to conveniently handle multiple models in a single form with Rails 3 and jQuery or Prototype.
ransack: 1 - Ransack is the successor to the MetaSearch gem. It improves and expands upon MetaSearch's functionali
by_star: 1 - ActiveRecord and Mongoid extension for easier date scopes and time ranges

TOTAL: 19

-----andreza-----

GEMS:

sass-rails: 1 - Sass adapter for the Rails asset pipeline.

TOTAL: 1

-----Karyd'ja-----

GEMS:

therubyracer: 2 - Call JavaScript code and manipulate JavaScript objects from Ruby. Call Ruby code and manipulate Ruby
compass-rails: 1 - Integrate Compass into Rails 3.0 and up.
bootswatch-rails: 1 - Bootswatches converted to SCSS ready to use in Rails asset pipeline.

TOTAL: 3

-----Victor Hugo de Oliveira-----

GEMS:

maskedinput-rails: 1 - jquery.maskedinput for rails.
font-awesome-sass: 1 - Font-Awesome SASS gem for use in Ruby projects
summernote-rails: 1 - This gem packages the editor Summernote for Rails' assets pipeline

TOTAL: 3

-----higor-----

GEMS:

wicked_pdf: 1 - Wicked PDF uses the shell utility wkhtmltopdf to serve a PDF file to a user from HTML.
In other words

TOTAL: 1

-----bengurgel-----

GEMS:

wkhtmltopdf-binary: 1 - Provides binaries for WKHTMLTOPDF project in an easily accessible package.

TOTAL: 1

-----karydja-----

GEMS:

rails: 1 - Ruby on Rails is a full-stack web framework optimized for programmer happiness and sustainable produc
pg: 1 - Pg is the Ruby interface to the {PostgreSQL RDBMS}[http://www.postgresql.org/].

It works with {Postg
simple_form: 1 - Forms made easy!
bootstrap-sass: 1 - Twitter's Bootstrap, converted to Sass and ready to drop into Rails or Compass
chosen-rails: 1 - Chosen is a javascript library of select box enhancer for jQuery and Protoype. This gem integrates Ch
maskedinput-rails: 1 - jquery.maskedinput for rails.
rails_12factor: 1 - Run Rails the 12factor way

TOTAL: 7

-----SeuRAUL-----

GEMS:

sass-rails: 1 - Sass adapter for the Rails asset pipeline.
uglifier: 1 - Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
coffee-rails: 1 - CoffeeScript adapter for the Rails asset pipeline.
jquery-rails: 1 - This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application.
jbuilder: 1 - Create JSON structures via a Builder-style DSL
devise: 1 - Flexible authentication solution for Rails with Warden
cancancan: 1 - Continuation of the simple authorization solution for Rails which is decoupled from user roles. All p
rspec: 1 - BDD for Ruby
rspec-rails: 1 - RSpec for Rails
shoulda-matchers: 1 - Making tests easy on the fingers and eyes
factory_girl_rails: 1 - factory_girl_rails provides integration between
    factory_girl and rails 3 (currently just automati
capybara: 1 - Capybara is an integration testing tool for rack based web applications. It simulates how a user woul
simplecov: 1 - Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage a

TOTAL: 13

-----Raquel-----

GEMS:

autoprefixer-rails: 1 - Parse CSS and add vendor prefixes to CSS rules using values from the Can I Use website.
sprockets-rails: 1 - Sprockets Rails integration
font-awesome-sass: 1 - Font-Awesome SASS gem for use in Ruby projects

TOTAL: 3
```

###Mentions

```
----BANCO-DE-VAGAS----
lucasbibiano - 33 mentions para esta pessoa
marcosjr182 - 7 mentions para esta pessoa
bernardo - 4 mentions para esta pessoa
karydja - 1 mentions para esta pessoa
igor_marques - 1 mentions para esta pessoa

----GEPE----
andrezap - 14 mentions para esta pessoa
igor_marques - 40 mentions para esta pessoa
lucasbibiano - 50 mentions para esta pessoa
ikaro_souza - 31 mentions para esta pessoa
higor - 63 mentions para esta pessoa
victor-oliveira - 42 mentions para esta pessoa
bernardo - 3 mentions para esta pessoa
seuraul - 1 mentions para esta pessoa
marcosjr182 - 1 mentions para esta pessoa

----APURN----
lucasbibiano - 33 mentions para esta pessoa
igor_marques - 5 mentions para esta pessoa
marcosjr182 - 11 mentions para esta pessoa

----LU-LANCHES----
karydja - 98 mentions para esta pessoa
hackel - 70 mentions para esta pessoa
igor_marques - 65 mentions para esta pessoa
seuraul - 42 mentions para esta pessoa
higor - 16 mentions para esta pessoa
iagomds - 103 mentions para esta pessoa
lucasbibiano - 49 mentions para esta pessoa
bernardo - 3 mentions para esta pessoa

----PULL_REQUESTS----
igor_marques - 6 mentions para esta pessoa
rubenbdpaz - 2 mentions para esta pessoa
iagomds - 3 mentions para esta pessoa
lucasbibiano - 6 mentions para esta pessoa
waldyr - 5 mentions para esta pessoa
karydja - 6 mentions para esta pessoa
seuraul - 1 mentions para esta pessoa

----DUVIDAS----
karydja - 6 mentions para esta pessoa
iagomds - 12 mentions para esta pessoa
waldyr - 9 mentions para esta pessoa
igor_marques - 2 mentions para esta pessoa
luizrogeriocn - 4 mentions para esta pessoa
lucasbibiano - 2 mentions para esta pessoa
marcosjr182 - 3 mentions para esta pessoa
bernardo - 5 mentions para esta pessoa

----ELEJA-SE----
lucasbibiano - 70 mentions para esta pessoa
waldyr - 49 mentions para esta pessoa
iagomds - 16 mentions para esta pessoa
luizrogeriocn - 42 mentions para esta pessoa
igor_marques - 30 mentions para esta pessoa
karydja - 2 mentions para esta pessoa
seuraul - 1 mentions para esta pessoa

----CONCRETO----
bernardo - 1 mentions para esta pessoa
lucasbibiano - 3 mentions para esta pessoa
victor-oliveira - 1 mentions para esta pessoa

----TRABALHANDO-EM----
igor_marques - 3 mentions para esta pessoa
lucasbibiano - 2 mentions para esta pessoa
higor - 2 mentions para esta pessoa
seuraul - 1 mentions para esta pessoa
victor-oliveira - 1 mentions para esta pessoa
karydja - 2 mentions para esta pessoa
rubenbdpaz - 1 mentions para esta pessoa
marcosjr182 - 1 mentions para esta pessoa

----IMOBILIARIA----
lucasbibiano - 105 mentions para esta pessoa
rubenbdpaz - 50 mentions para esta pessoa
igor_marques - 20 mentions para esta pessoa
waldyr - 5 mentions para esta pessoa
diegopl - 18 mentions para esta pessoa
karydja - 1 mentions para esta pessoa
iagomds - 1 mentions para esta pessoa

----ADMINISTRATIVO----
lucasbibiano - 12 mentions para esta pessoa
seuraul - 25 mentions para esta pessoa
karydja - 103 mentions para esta pessoa
higor - 30 mentions para esta pessoa
igor_marques - 67 mentions para esta pessoa
lucasalveslm - 1 mentions para esta pessoa
victor-oliveira - 8 mentions para esta pessoa
iagomds - 2 mentions para esta pessoa
bernardo - 1 mentions para esta pessoa

----COOPERATIVACULTURAL----
marcosjr182 - 88 mentions para esta pessoa
bernardo - 13 mentions para esta pessoa
igor_marques - 13 mentions para esta pessoa
waldyr - 5 mentions para esta pessoa
lucasbibiano - 5 mentions para esta pessoa

----LINKS-INTERESSANTES----
lucasbibiano - 6 mentions para esta pessoa
iagomds - 11 mentions para esta pessoa
seuraul - 2 mentions para esta pessoa
igor_marques - 6 mentions para esta pessoa
karydja - 6 mentions para esta pessoa
higor - 3 mentions para esta pessoa
bernardo - 3 mentions para esta pessoa
waldyr - 1 mentions para esta pessoa
victor-oliveira - 1 mentions para esta pessoa

----GENERAL----
lucasalveslm - 3 mentions para esta pessoa
seuraul - 62 mentions para esta pessoa
waldyr - 5 mentions para esta pessoa
lucasbibiano - 42 mentions para esta pessoa
igor_marques - 143 mentions para esta pessoa
victor-oliveira - 25 mentions para esta pessoa
karydja - 114 mentions para esta pessoa
bernardo - 23 mentions para esta pessoa
hackel - 28 mentions para esta pessoa
ikaro_souza - 14 mentions para esta pessoa
iagomds - 44 mentions para esta pessoa
andrezap - 4 mentions para esta pessoa
higor - 101 mentions para esta pessoa
diegopl - 3 mentions para esta pessoa
luizrogeriocn - 16 mentions para esta pessoa
rubenbdpaz - 5 mentions para esta pessoa
marcosjr182 - 1 mentions para esta pessoa
luanfonceca - 1 mentions para esta pessoa

----RANDOM----
hackel - 16 mentions para esta pessoa
karydja - 47 mentions para esta pessoa
lucasbibiano - 13 mentions para esta pessoa
iagomds - 40 mentions para esta pessoa
waldyr - 10 mentions para esta pessoa
diegopl - 7 mentions para esta pessoa
igor_marques - 55 mentions para esta pessoa
higor - 25 mentions para esta pessoa
luizrogeriocn - 6 mentions para esta pessoa
bernardo - 4 mentions para esta pessoa
seuraul - 12 mentions para esta pessoa
ikaro_souza - 8 mentions para esta pessoa
marcosjr182 - 1 mentions para esta pessoa
rubenbdpaz - 2 mentions para esta pessoa
victor-oliveira - 5 mentions para esta pessoa
andrezap - 3 mentions para esta pessoa
luanfonceca - 1 mentions para esta pessoa
```

 ###channels sent

 ```
 ----BANCO-DE-VAGAS----
lucasbibiano - 3 @channels enviados
igor_marques - 9 @channels enviados
marcosjr182 - 0 @channels enviados
karydja - 0 @channels enviados
bernardo - 1 @channels enviados
higor - 0 @channels enviados

----GEPE----
higor - 14 @channels enviados
igor_marques - 132 @channels enviados
marcosjr182 - 0 @channels enviados
lucasbibiano - 16 @channels enviados
victor-oliveira - 19 @channels enviados
andrezap - 3 @channels enviados
ikaro_souza - 11 @channels enviados
bernardo - 1 @channels enviados
karydja - 0 @channels enviados
seuraul - 0 @channels enviados

----APURN----
lucasbibiano - 6 @channels enviados
igor_marques - 7 @channels enviados
marcosjr182 - 2 @channels enviados
victor-oliveira - 0 @channels enviados

----LU-LANCHES----
iagomds - 12 @channels enviados
igor_marques - 65 @channels enviados
hackel - 4 @channels enviados
karydja - 44 @channels enviados
lucasbibiano - 3 @channels enviados
seuraul - 7 @channels enviados
higor - 3 @channels enviados
bernardo - 0 @channels enviados
victor-oliveira - 1 @channels enviados

----PULL_REQUESTS----
igor_marques - 31 @channels enviados
seuraul - 0 @channels enviados
iagomds - 0 @channels enviados
karydja - 2 @channels enviados
waldyr - 1 @channels enviados
lucasbibiano - 0 @channels enviados
andrezap - 0 @channels enviados
higor - 0 @channels enviados
bernardo - 0 @channels enviados
hackel - 0 @channels enviados
ikaro_souza - 0 @channels enviados
luanfonceca - 0 @channels enviados
marcosjr182 - 0 @channels enviados
rubenbdpaz - 0 @channels enviados
luizrogeriocn - 0 @channels enviados
victor-oliveira - 0 @channels enviados

----DUVIDAS----
igor_marques - 13 @channels enviados
lucasbibiano - 0 @channels enviados
waldyr - 1 @channels enviados
iagomds - 0 @channels enviados
karydja - 11 @channels enviados
bernardo - 0 @channels enviados
luizrogeriocn - 1 @channels enviados
marcosjr182 - 2 @channels enviados
seuraul - 0 @channels enviados
victor-oliveira - 0 @channels enviados
andrezap - 0 @channels enviados
hackel - 0 @channels enviados
ikaro_souza - 0 @channels enviados
higor - 0 @channels enviados
luanfonceca - 0 @channels enviados
rubenbdpaz - 0 @channels enviados

----ELEJA-SE----
igor_marques - 54 @channels enviados
iagomds - 2 @channels enviados
waldyr - 0 @channels enviados
lucasbibiano - 8 @channels enviados
luizrogeriocn - 0 @channels enviados
karydja - 0 @channels enviados

----CONCRETO----
igor_marques - 1 @channels enviados
lucasbibiano - 1 @channels enviados
bernardo - 0 @channels enviados
victor-oliveira - 0 @channels enviados

----TRABALHANDO-EM----
lucasbibiano - 8 @channels enviados
karydja - 11 @channels enviados
victor-oliveira - 2 @channels enviados
igor_marques - 23 @channels enviados
diegopl - 0 @channels enviados
ikaro_souza - 2 @channels enviados
higor - 0 @channels enviados
iagomds - 0 @channels enviados
seuraul - 0 @channels enviados
waldyr - 0 @channels enviados
andrezap - 0 @channels enviados
rubenbdpaz - 0 @channels enviados
hackel - 0 @channels enviados
lucasalveslm - 2 @channels enviados
luizrogeriocn - 0 @channels enviados
marcosjr182 - 0 @channels enviados

----IMOBILIARIA----
lucasbibiano - 8 @channels enviados
igor_marques - 27 @channels enviados
rubenbdpaz - 1 @channels enviados
waldyr - 0 @channels enviados
diegopl - 1 @channels enviados
higor - 0 @channels enviados
karydja - 0 @channels enviados

----ADMINISTRATIVO----
igor_marques - 75 @channels enviados
higor - 1 @channels enviados
seuraul - 0 @channels enviados
lucasbibiano - 1 @channels enviados
karydja - 6 @channels enviados
bernardo - 2 @channels enviados
victor-oliveira - 1 @channels enviados

----COOPERATIVACULTURAL----
igor_marques - 10 @channels enviados
marcosjr182 - 3 @channels enviados
lucasbibiano - 0 @channels enviados
bernardo - 1 @channels enviados
waldyr - 0 @channels enviados
hackel - 0 @channels enviados

----LINKS-INTERESSANTES----
karydja - 3 @channels enviados
lucasbibiano - 13 @channels enviados
waldyr - 0 @channels enviados
iagomds - 8 @channels enviados
seuraul - 1 @channels enviados
igor_marques - 9 @channels enviados
andrezap - 0 @channels enviados
hackel - 0 @channels enviados
luanfonceca - 0 @channels enviados
higor - 0 @channels enviados
luizrogeriocn - 0 @channels enviados
bernardo - 0 @channels enviados
victor-oliveira - 0 @channels enviados
ikaro_souza - 0 @channels enviados
diegopl - 0 @channels enviados
marcosjr182 - 0 @channels enviados

----GENERAL----
seuraul - 15 @channels enviados
higor - 19 @channels enviados
lucasalveslm - 1 @channels enviados
igor_marques - 451 @channels enviados
diegopl - 0 @channels enviados
karydja - 99 @channels enviados
iagomds - 9 @channels enviados
rubenbdpaz - 0 @channels enviados
ikaro_souza - 19 @channels enviados
hackel - 9 @channels enviados
lucasbibiano - 34 @channels enviados
bernardo - 3 @channels enviados
victor-oliveira - 7 @channels enviados
waldyr - 0 @channels enviados
andrezap - 1 @channels enviados
marcosjr182 - 0 @channels enviados
luanfonceca - 0 @channels enviados
luizrogeriocn - 1 @channels enviados

----RANDOM----
seuraul - 3 @channels enviados
igor_marques - 14 @channels enviados
lucasbibiano - 4 @channels enviados
karydja - 25 @channels enviados
iagomds - 8 @channels enviados
higor - 4 @channels enviados
ikaro_souza - 1 @channels enviados
waldyr - 1 @channels enviados
diegopl - 0 @channels enviados
hackel - 3 @channels enviados
andrezap - 0 @channels enviados
victor-oliveira - 2 @channels enviados
lucasalveslm - 0 @channels enviados
luizrogeriocn - 1 @channels enviados
rubenbdpaz - 0 @channels enviados
bernardo - 0 @channels enviados
marcosjr182 - 0 @channels enviados
luanfonceca - 0 @channels enviados
```

###Messages
```
----BANCO-DE-VAGAS----
lucasbibiano - 536 mensagens
igor_marques - 677 mensagens
marcosjr182 - 46 mensagens
karydja - 10 mensagens
bernardo - 26 mensagens
higor - 2 mensagens

----GEPE----
higor - 618 mensagens
igor_marques - 1389 mensagens
marcosjr182 - 2 mensagens
lucasbibiano - 449 mensagens
victor-oliveira - 590 mensagens
andrezap - 88 mensagens
ikaro_souza - 254 mensagens
bernardo - 21 mensagens
karydja - 13 mensagens
seuraul - 0 mensagens

----APURN----
lucasbibiano - 476 mensagens
igor_marques - 480 mensagens
marcosjr182 - 39 mensagens
victor-oliveira - 0 mensagens

----LU-LANCHES----
iagomds - 869 mensagens
igor_marques - 2420 mensagens
hackel - 367 mensagens
karydja - 3285 mensagens
lucasbibiano - 700 mensagens
seuraul - 239 mensagens
higor - 91 mensagens
bernardo - 72 mensagens
victor-oliveira - 20 mensagens

----PULL_REQUESTS----
igor_marques - 109 mensagens
seuraul - 5 mensagens
iagomds - 14 mensagens
karydja - 52 mensagens
waldyr - 16 mensagens
lucasbibiano - 15 mensagens
andrezap - 0 mensagens
higor - 0 mensagens
bernardo - 0 mensagens
hackel - 0 mensagens
ikaro_souza - 0 mensagens
luanfonceca - 0 mensagens
marcosjr182 - 0 mensagens
rubenbdpaz - 0 mensagens
luizrogeriocn - 0 mensagens
victor-oliveira - 0 mensagens

----DUVIDAS----
igor_marques - 208 mensagens
lucasbibiano - 58 mensagens
waldyr - 100 mensagens
iagomds - 74 mensagens
karydja - 149 mensagens
bernardo - 9 mensagens
luizrogeriocn - 110 mensagens
marcosjr182 - 4 mensagens
seuraul - 6 mensagens
victor-oliveira - 1 mensagens
andrezap - 0 mensagens
hackel - 0 mensagens
ikaro_souza - 0 mensagens
higor - 0 mensagens
luanfonceca - 0 mensagens
rubenbdpaz - 0 mensagens

----ELEJA-SE----
igor_marques - 2384 mensagens
iagomds - 324 mensagens
waldyr - 518 mensagens
lucasbibiano - 868 mensagens
luizrogeriocn - 560 mensagens
karydja - 27 mensagens

----CONCRETO----
igor_marques - 66 mensagens
lucasbibiano - 85 mensagens
bernardo - 0 mensagens
victor-oliveira - 36 mensagens

----TRABALHANDO-EM----
lucasbibiano - 30 mensagens
karydja - 97 mensagens
victor-oliveira - 9 mensagens
igor_marques - 151 mensagens
diegopl - 6 mensagens
ikaro_souza - 4 mensagens
higor - 4 mensagens
iagomds - 27 mensagens
seuraul - 34 mensagens
waldyr - 2 mensagens
andrezap - 0 mensagens
rubenbdpaz - 4 mensagens
hackel - 13 mensagens
lucasalveslm - 4 mensagens
luizrogeriocn - 2 mensagens
marcosjr182 - 4 mensagens

----IMOBILIARIA----
lucasbibiano - 1293 mensagens
igor_marques - 1883 mensagens
rubenbdpaz - 98 mensagens
waldyr - 102 mensagens
diegopl - 157 mensagens
higor - 0 mensagens
karydja - 1 mensagens

----ADMINISTRATIVO----
igor_marques - 2209 mensagens
higor - 158 mensagens
seuraul - 228 mensagens
lucasbibiano - 263 mensagens
karydja - 1787 mensagens
bernardo - 18 mensagens
victor-oliveira - 55 mensagens

----COOPERATIVACULTURAL----
igor_marques - 429 mensagens
marcosjr182 - 132 mensagens
lucasbibiano - 49 mensagens
bernardo - 23 mensagens
waldyr - 37 mensagens
hackel - 0 mensagens

----LINKS-INTERESSANTES----
karydja - 88 mensagens
lucasbibiano - 120 mensagens
waldyr - 93 mensagens
iagomds - 124 mensagens
seuraul - 68 mensagens
igor_marques - 146 mensagens
andrezap - 0 mensagens
hackel - 3 mensagens
luanfonceca - 1 mensagens
higor - 9 mensagens
luizrogeriocn - 8 mensagens
bernardo - 10 mensagens
victor-oliveira - 2 mensagens
ikaro_souza - 0 mensagens
diegopl - 0 mensagens
marcosjr182 - 0 mensagens

----GENERAL----
seuraul - 986 mensagens
higor - 819 mensagens
lucasalveslm - 13 mensagens
igor_marques - 4674 mensagens
diegopl - 83 mensagens
karydja - 2631 mensagens
iagomds - 917 mensagens
rubenbdpaz - 25 mensagens
ikaro_souza - 78 mensagens
hackel - 289 mensagens
lucasbibiano - 1343 mensagens
bernardo - 242 mensagens
victor-oliveira - 502 mensagens
waldyr - 232 mensagens
andrezap - 23 mensagens
marcosjr182 - 21 mensagens
luanfonceca - 23 mensagens
luizrogeriocn - 70 mensagens

----RANDOM----
seuraul - 303 mensagens
igor_marques - 978 mensagens
lucasbibiano - 554 mensagens
karydja - 1149 mensagens
iagomds - 803 mensagens
higor - 176 mensagens
ikaro_souza - 31 mensagens
waldyr - 280 mensagens
diegopl - 49 mensagens
hackel - 288 mensagens
andrezap - 8 mensagens
victor-oliveira - 47 mensagens
lucasalveslm - 9 mensagens
luizrogeriocn - 301 mensagens
rubenbdpaz - 6 mensagens
bernardo - 0 mensagens
marcosjr182 - 0 mensagens
luanfonceca - 0 mensagens
```
