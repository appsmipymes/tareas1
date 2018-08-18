# tareas1



PASANTE@B7-502-03 MINGW64 ~
$ heroku --version
heroku/7.9.3 win32-x64 node-v10.9.0

PASANTE@B7-502-03 MINGW64 ~
$ cd Desktop/

PASANTE@B7-502-03 MINGW64 ~/Desktop
$ cd yoaprendo/

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ cd

PASANTE@B7-502-03 MINGW64 ~
$ cd Desktop

PASANTE@B7-502-03 MINGW64 ~/Desktop
$ cd UAC-104-grupo-3/

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3 (master)
$ cd proyecto/

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto (master)
$ cd synecor/

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ bondle install
bash: bondle: command not found

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ bondle install gem
bash: bondle: command not found

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ bundle install
Using rake 12.3.1
Using concurrent-ruby 1.0.5
Using i18n 1.0.1
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.2.0
Using builder 3.2.3
Using erubi 1.7.1
Using mini_portile2 2.3.0
Using nokogiri 1.8.4 (x64-mingw32)
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.2
Using rails-html-sanitizer 1.0.4
Using actionview 5.2.0
Using rack 2.0.5
Using rack-test 1.1.0
Using actionpack 5.2.0
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.7.0
Using actioncable 5.2.0
Using globalid 0.4.1
Using activejob 5.2.0
Using mini_mime 1.0.0
Using mail 2.7.0
Using actionmailer 5.2.0
Using activemodel 5.2.0
Using arel 9.0.0
Using activerecord 5.2.0
Using mimemagic 0.3.2
Using marcel 0.3.2
Using activestorage 5.2.0
Using public_suffix 3.0.2
Using addressable 2.5.2
Using io-like 0.3.0
Using archive-zip 0.11.0
Using bindex 0.5.0
Using msgpack 1.2.4 (x64-mingw32)
Using bootsnap 1.3.1
Using bundler 1.16.3
Using byebug 10.0.2
Using xpath 3.1.0
Using capybara 3.5.1
Using ffi 1.9.25 (x64-mingw32)
Using childprocess 0.9.0
Using chromedriver-helper 1.2.0
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.0
Using thor 0.20.0
Using railties 5.2.0
Using coffee-rails 4.2.2
Using duktape 2.0.1.0
Using multi_json 1.13.1
Using jbuilder 2.7.0
Using puma 3.12.0
Using sprockets 3.7.2
Using sprockets-rails 3.2.1
Using rails 5.2.0
Using rb-fsevent 0.10.3
Using rb-inotify 0.9.10
Using rubyzip 1.2.1
Using sass-listen 4.0.0
Using sass 3.5.7
Using tilt 2.0.8
Using sass-rails 5.0.7
Using selenium-webdriver 3.14.0
Using sqlite3 1.3.13 (x64-mingw32)
Using turbolinks-source 5.1.0
Using turbolinks 5.1.1
Using tzinfo-data 1.2018.5
Using uglifier 4.1.17
Using web-console 3.6.2
Bundle complete! 16 Gemfile dependencies, 76 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ rails s
=> Booting Puma
=> Rails 5.2.0 application starting in development
=> Run `rails server -h` for more startup options
*** SIGUSR2 not implemented, signal based restart unavailable!
*** SIGUSR1 not implemented, signal based restart unavailable!
*** SIGHUP not implemented, signal based logs reopening unavailable!
Puma starting in single mode...
* Version 3.12.0 (ruby 2.4.4-p296), codename: Llamas in Pajamas
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://0.0.0.0:3000
Use Ctrl-C to stop
Started GET "/home/index" for 127.0.0.1 at 2018-08-18 10:57:08 -0500
Processing by HomeController#index as HTML
  Rendering home/index.html.erb within layouts/application
  Rendered home/index.html.erb within layouts/application (1.0ms)
Completed 200 OK in 70ms (Views: 46.3ms | ActiveRecord: 0.0ms)


Started GET "/contacto/index.html" for 127.0.0.1 at 2018-08-18 10:57:13 -0500
Processing by ContactoController#index as HTML
  Rendering contacto/index.html.erb within layouts/application
  Rendered contacto/index.html.erb within layouts/application (0.0ms)
Completed 200 OK in 59ms (Views: 40.7ms | ActiveRecord: 0.0ms)


Started GET "/home/index.html" for 127.0.0.1 at 2018-08-18 10:57:29 -0500
Processing by HomeController#index as HTML
  Rendering home/index.html.erb within layouts/application
  Rendered home/index.html.erb within layouts/application (1.0ms)
Completed 200 OK in 49ms (Views: 36.0ms | ActiveRecord: 0.0ms)


Started GET "/informacion/index.html" for 127.0.0.1 at 2018-08-18 10:57:31 -0500
Processing by InformacionController#index as HTML
  Rendering informacion/index.html.erb within layouts/application
  Rendered informacion/index.html.erb within layouts/application (0.0ms)
Completed 200 OK in 60ms (Views: 40.3ms | ActiveRecord: 0.0ms)


- Gracefully stopping, waiting for requests to finish
=== puma shutdown: 2018-08-18 10:58:59 -0500 ===
- Goodbye!
Exiting

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ ls
app/  bin/  config/  config.ru  db/  Gemfile  Gemfile.lock  lib/  log/  package.json  public/  Rakefile  README.md  test/  tmp/  vendor/

PASANTE@B7-502-03 MINGW64 ~/Desktop/UAC-104-grupo-3/proyecto/synecor (master)
$ cd

PASANTE@B7-502-03 MINGW64 ~
$ cd Desktop/

PASANTE@B7-502-03 MINGW64 ~/Desktop
$ ls
'~$ase visual studio code.docx'        04-08-2018/                      clase18/     'MICLASE 18 AGOSTO 2018 EN GIT.docx'   rest/              yoapre
'~$CLASE 18 AGOSTO 2018 EN GIT.docx'  'clase visual studio code.docx'   desktop.ini   Postman.lnk*                          UAC-104-grupo-3/

PASANTE@B7-502-03 MINGW64 ~/Desktop
$ cd yoaprendo/

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ ls
app/  bin/  config/  config.ru  db/  Gemfile  Gemfile.lock  lib/  log/  package.json  public/  Rakefile  README.md  storage/  test/  tmp/  vendor/

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ heroku login
heroku: Enter your login credentials
Email: appsmipymes@gmail.com
Password: /Pdulce$8

Logged in as appsmipymes@gmail.com
^C▒Desea terminar el trabajo por lotes (S/N)? s
s

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ ls
app/  bin/  config/  config.ru  db/  Gemfile  Gemfile.lock  lib/  log/  package.json  public/  Rakefile  README.md  storage/  test/  tmp/  vendor/

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ touch Procfile

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ ls
app/  bin/  config/  config.ru  db/  Gemfile  Gemfile.lock  lib/  log/  package.json  Procfile  public/  Rakefile  README.md  storage/  test/  tmp/

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
error: src refspec master does not match any.
error: failed to push some refs to 'https://git.heroku.com/appsmipymes.git'

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore
        .ruby-version
        Gemfile
        Gemfile.lock
        Procfile
        README.md
        Rakefile
        app/
        bin/
        config.ru
        config/
        db/
        lib/
        log/
        package.json
        public/
        test/
        tmp/
        vendor/

nothing added to commit but untracked files present (use "git add" to track)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore
        .ruby-version
        Gemfile
        Gemfile.lock
        Procfile
        README.md
        Rakefile
        app/
        bin/
        config.ru
        config/
        db/
        lib/
        log/
        package.json
        public/
        test/
        tmp/
        vendor/

nothing added to commit but untracked files present (use "git add" to track)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git commit -am "Proyecto Yo Aprendo"
On branch master

Initial commit

Untracked files:
        .gitignore
        .ruby-version
        Gemfile
        Gemfile.lock
        Procfile
        README.md
        Rakefile
        app/
        bin/
        config.ru
        config/
        db/
        lib/
        log/
        package.json
        public/
        test/
        tmp/
        vendor/

nothing added to commit but untracked files present

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore
        .ruby-version
        Gemfile
        Gemfile.lock
        Procfile
        README.md
        Rakefile
        app/
        bin/
        config.ru
        config/
        db/
        lib/
        log/
        package.json
        public/
        test/
        tmp/
        vendor/

nothing added to commit but untracked files present (use "git add" to track)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add .
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in Gemfile.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in Gemfile.lock.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in Rakefile.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/config/manifest.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/javascripts/application.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/javascripts/cable.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/javascripts/users.coffee.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/stylesheets/application.css.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/stylesheets/scaffolds.scss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/stylesheets/users.scss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/channels/application_cable/channel.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/channels/application_cable/connection.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/controllers/application_controller.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/controllers/users_controller.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/helpers/application_helper.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/helpers/users_helper.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/jobs/application_job.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/mailers/application_mailer.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/models/application_record.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/models/user.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/layouts/application.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/layouts/mailer.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/layouts/mailer.text.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/_form.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/_user.json.jbuilder.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/edit.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/index.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/index.json.jbuilder.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/new.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/show.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/users/show.json.jbuilder.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/bundle.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/rails.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/rake.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/setup.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/update.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in bin/yarn.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config.ru.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/application.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/boot.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/cable.yml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/database.yml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/environment.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/environments/development.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/environments/production.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/environments/test.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/application_controller_renderer.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/assets.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/backtrace_silencers.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/content_security_policy.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/cookies_serializer.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/filter_parameter_logging.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/inflections.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/mime_types.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/initializers/wrap_parameters.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/locales/en.yml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/puma.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/routes.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/storage.yml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in db/migrate/20180818143755_create_users.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in db/seeds.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in public/404.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in public/422.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in public/500.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in public/robots.txt.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/application_system_test_case.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/controllers/users_controller_test.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/fixtures/users.yml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/models/user_test.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/system/users_test.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/test_helper.rb.
The file will have its original line endings in your working directory.

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git commit -am "Proyecto yo aprendo"
[master (root-commit) 200bf1a] Proyecto yo aprendo
 Committer: APRENDIZ SENA LABORATORIOS <PASANTE@Laboratorios.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 98 files changed, 1623 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 .ruby-version
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 Procfile
 create mode 100644 README.md
 create mode 100644 Rakefile
 create mode 100644 app/assets/config/manifest.js
 create mode 100644 app/assets/images/.keep
 create mode 100644 app/assets/javascripts/application.js
 create mode 100644 app/assets/javascripts/cable.js
 create mode 100644 app/assets/javascripts/channels/.keep
 create mode 100644 app/assets/javascripts/users.coffee
 create mode 100644 app/assets/stylesheets/application.css
 create mode 100644 app/assets/stylesheets/scaffolds.scss
 create mode 100644 app/assets/stylesheets/users.scss
 create mode 100644 app/channels/application_cable/channel.rb
 create mode 100644 app/channels/application_cable/connection.rb
 create mode 100644 app/controllers/application_controller.rb
 create mode 100644 app/controllers/concerns/.keep
 create mode 100644 app/controllers/users_controller.rb
 create mode 100644 app/helpers/application_helper.rb
 create mode 100644 app/helpers/users_helper.rb
 create mode 100644 app/jobs/application_job.rb
 create mode 100644 app/mailers/application_mailer.rb
 create mode 100644 app/models/application_record.rb
 create mode 100644 app/models/concerns/.keep
 create mode 100644 app/models/user.rb
 create mode 100644 app/views/layouts/application.html.erb
 create mode 100644 app/views/layouts/mailer.html.erb
 create mode 100644 app/views/layouts/mailer.text.erb
 create mode 100644 app/views/users/_form.html.erb
 create mode 100644 app/views/users/_user.json.jbuilder
 create mode 100644 app/views/users/edit.html.erb
 create mode 100644 app/views/users/index.html.erb
 create mode 100644 app/views/users/index.json.jbuilder
 create mode 100644 app/views/users/new.html.erb
 create mode 100644 app/views/users/show.html.erb
 create mode 100644 app/views/users/show.json.jbuilder
 create mode 100644 bin/bundle
 create mode 100644 bin/rails
 create mode 100644 bin/rake
 create mode 100644 bin/setup
 create mode 100644 bin/update
 create mode 100644 bin/yarn
 create mode 100644 config.ru
 create mode 100644 config/application.rb
 create mode 100644 config/boot.rb
 create mode 100644 config/cable.yml
 create mode 100644 config/credentials.yml.enc
 create mode 100644 config/database.yml
 create mode 100644 config/environment.rb
 create mode 100644 config/environments/development.rb
 create mode 100644 config/environments/production.rb
 create mode 100644 config/environments/test.rb
 create mode 100644 config/initializers/application_controller_renderer.rb
 create mode 100644 config/initializers/assets.rb
 create mode 100644 config/initializers/backtrace_silencers.rb
 create mode 100644 config/initializers/content_security_policy.rb
 create mode 100644 config/initializers/cookies_serializer.rb
 create mode 100644 config/initializers/filter_parameter_logging.rb
 create mode 100644 config/initializers/inflections.rb
 create mode 100644 config/initializers/mime_types.rb
 create mode 100644 config/initializers/wrap_parameters.rb
 create mode 100644 config/locales/en.yml
 create mode 100644 config/puma.rb
 create mode 100644 config/routes.rb
 create mode 100644 config/storage.yml
 create mode 100644 db/migrate/20180818143755_create_users.rb
 create mode 100644 db/schema.rb
 create mode 100644 db/seeds.rb
 create mode 100644 lib/assets/.keep
 create mode 100644 lib/tasks/.keep
 create mode 100644 log/.keep
 create mode 100644 package.json
 create mode 100644 public/404.html
 create mode 100644 public/422.html
 create mode 100644 public/500.html
 create mode 100644 public/apple-touch-icon-precomposed.png
 create mode 100644 public/apple-touch-icon.png
 create mode 100644 public/favicon.ico
 create mode 100644 public/robots.txt
 create mode 100644 test/application_system_test_case.rb
 create mode 100644 test/controllers/.keep
 create mode 100644 test/controllers/users_controller_test.rb
 create mode 100644 test/fixtures/.keep
 create mode 100644 test/fixtures/files/.keep
 create mode 100644 test/fixtures/users.yml
 create mode 100644 test/helpers/.keep
 create mode 100644 test/integration/.keep
 create mode 100644 test/mailers/.keep
 create mode 100644 test/models/.keep
 create mode 100644 test/models/user_test.rb
 create mode 100644 test/system/.keep
 create mode 100644 test/system/users_test.rb
 create mode 100644 test/test_helper.rb
 create mode 100644 tmp/.keep
 create mode 100644 vendor/.keep

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Counting objects: 111, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (96/96), done.
Writing objects: 100% (111/111), 26.19 KiB | 1.31 MiB/s, done.
Total 111 (delta 2), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote:  !     Warning: Multiple default buildpacks reported the ability to handle this app. The first buildpack in the list below will be used.
remote:                         Detected buildpacks: Ruby,Node.js
remote:                         See https://devcenter.heroku.com/articles/buildpacks#buildpack-detect-order
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.4.4
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4
remote:        The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Fetching rake 12.3.1
remote:        Fetching concurrent-ruby 1.0.5
remote:        Fetching minitest 5.11.3
remote:        Installing rake 12.3.1
remote:        Installing minitest 5.11.3
remote:        Installing concurrent-ruby 1.0.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.7.1
remote:        Installing erubi 1.7.1
remote:        Fetching mini_portile2 2.3.0
remote:        Fetching crass 1.0.4
remote:        Fetching rack 2.0.5
remote:        Installing mini_portile2 2.3.0
remote:        Installing crass 1.0.4
remote:        Fetching nio4r 2.3.1
remote:        Installing rack 2.0.5
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 9.0.0
remote:        Installing arel 9.0.0
remote:        Fetching mimemagic 0.3.2
remote:        Fetching msgpack 1.2.4
remote:        Installing msgpack 1.2.4 with native extensions
remote:        Installing mimemagic 0.3.2
remote:        Using bundler 1.15.2
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching method_source 0.9.0
remote:        Installing method_source 0.9.0
remote:        Fetching thor 0.20.0
remote:        Installing thor 0.20.0
remote:        Fetching duktape 2.0.1.0
remote:        Installing duktape 2.0.1.0 with native extensions
remote:        Fetching ffi 1.9.25
remote:        Installing ffi 1.9.25 with native extensions
remote:        Fetching multi_json 1.13.1
remote:        Installing multi_json 1.13.1
remote:        Fetching pg 1.0.0
remote:        Installing pg 1.0.0 with native extensions
remote:        Fetching puma 3.12.0
remote:        Installing puma 3.12.0 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching tilt 2.0.8
remote:        Installing tilt 2.0.8
remote:        Fetching sqlite3 1.3.13
remote:        Installing sqlite3 1.3.13 with native extensions
remote:        Fetching turbolinks-source 5.1.0
remote:        Installing turbolinks-source 5.1.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching i18n 1.1.0
remote:        Installing i18n 1.1.0
remote:        Fetching nokogiri 1.8.4
remote:        Installing nokogiri 1.8.4 with native extensions
remote:        Fetching websocket-driver 0.7.0
remote:        Installing websocket-driver 0.7.0 with native extensions
remote:        Fetching mail 2.7.0
remote:        Installing mail 2.7.0
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching marcel 0.3.2
remote:        Installing marcel 0.3.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching uglifier 4.1.18
remote:        Installing uglifier 4.1.18
remote:        Fetching bootsnap 1.3.1
remote:        Installing bootsnap 1.3.1 with native extensions
remote:        Fetching rb-inotify 0.9.10
remote:        Installing rb-inotify 0.9.10
remote:        Fetching turbolinks 5.1.1
remote:        Installing turbolinks 5.1.1
remote:        Fetching activesupport 5.2.1
remote:        Installing activesupport 5.2.1
remote:        Gem::Ext::BuildError: ERROR: Failed to build gem native extension.
remote:
remote:        current directory:
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13/ext/sqlite3
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/ruby-2.4.4/bin/ruby -r
remote:        ./siteconf20180818-271-1ev6e8b.rb extconf.rb
remote:        checking for sqlite3.h... no
remote:        sqlite3.h is missing. Try 'brew install sqlite3',
remote:        'yum install sqlite-devel' or 'apt-get install libsqlite3-dev'
remote:        and check your shared library search path (the
remote:        location where your sqlite3 shared library is located).
remote:        *** extconf.rb failed ***
remote:        Could not create Makefile due to some reason, probably lack of necessary
remote:        libraries and/or headers.  Check the mkmf.log file for more details.  You may
remote:        need configuration options.
remote:
remote:        Provided configuration options:
remote:         --with-opt-dir
remote:         --without-opt-dir
remote:         --with-opt-include
remote:         --without-opt-include=${opt-dir}/include
remote:         --with-opt-lib
remote:         --without-opt-lib=${opt-dir}/lib
remote:         --with-make-prog
remote:         --without-make-prog
remote:         --srcdir=.
remote:         --curdir
remote:        --ruby=/tmp/build_3a943693154e3419f1a462de7bde862a/vendor/ruby-2.4.4/bin/$(RUBY_BASE_NAME)
remote:         --with-sqlite3-config
remote:         --without-sqlite3-config
remote:         --with-pkg-config
remote:         --without-pkg-config
remote:         --with-sqlite3-dir
remote:         --without-sqlite3-dir
remote:         --with-sqlite3-include
remote:         --without-sqlite3-include=${sqlite3-dir}/include
remote:         --with-sqlite3-lib
remote:         --without-sqlite3-lib=${sqlite3-dir}/lib
remote:
remote:        To see why this extension failed to compile, please check the mkmf.log which can
remote:        be found here:
remote:
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/mkmf.log
remote:
remote:        extconf failed, exit code 1
remote:
remote:        Gem files will remain installed in
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13
remote:        for inspection.
remote:        Results logged to
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/gem_make.out
remote:
remote:        An error occurred while installing sqlite3 (1.3.13), and Bundler cannot
remote:        continue.
remote:        Make sure that `gem install sqlite3 -v '1.3.13'` succeeds before bundling.
remote:
remote:        In Gemfile:
remote:          sqlite3
remote:        Bundler Output: The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Fetching rake 12.3.1
remote:        Fetching concurrent-ruby 1.0.5
remote:        Fetching minitest 5.11.3
remote:        Installing rake 12.3.1
remote:        Installing minitest 5.11.3
remote:        Installing concurrent-ruby 1.0.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.7.1
remote:        Installing erubi 1.7.1
remote:        Fetching mini_portile2 2.3.0
remote:        Fetching crass 1.0.4
remote:        Fetching rack 2.0.5
remote:        Installing mini_portile2 2.3.0
remote:        Installing crass 1.0.4
remote:        Fetching nio4r 2.3.1
remote:        Installing rack 2.0.5
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 9.0.0
remote:        Installing arel 9.0.0
remote:        Fetching mimemagic 0.3.2
remote:        Fetching msgpack 1.2.4
remote:        Installing msgpack 1.2.4 with native extensions
remote:        Installing mimemagic 0.3.2
remote:        Using bundler 1.15.2
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching method_source 0.9.0
remote:        Installing method_source 0.9.0
remote:        Fetching thor 0.20.0
remote:        Installing thor 0.20.0
remote:        Fetching duktape 2.0.1.0
remote:        Installing duktape 2.0.1.0 with native extensions
remote:        Fetching ffi 1.9.25
remote:        Installing ffi 1.9.25 with native extensions
remote:        Fetching multi_json 1.13.1
remote:        Installing multi_json 1.13.1
remote:        Fetching pg 1.0.0
remote:        Installing pg 1.0.0 with native extensions
remote:        Fetching puma 3.12.0
remote:        Installing puma 3.12.0 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching tilt 2.0.8
remote:        Installing tilt 2.0.8
remote:        Fetching sqlite3 1.3.13
remote:        Installing sqlite3 1.3.13 with native extensions
remote:        Fetching turbolinks-source 5.1.0
remote:        Installing turbolinks-source 5.1.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching i18n 1.1.0
remote:        Installing i18n 1.1.0
remote:        Fetching nokogiri 1.8.4
remote:        Installing nokogiri 1.8.4 with native extensions
remote:        Fetching websocket-driver 0.7.0
remote:        Installing websocket-driver 0.7.0 with native extensions
remote:        Fetching mail 2.7.0
remote:        Installing mail 2.7.0
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching marcel 0.3.2
remote:        Installing marcel 0.3.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching uglifier 4.1.18
remote:        Installing uglifier 4.1.18
remote:        Fetching bootsnap 1.3.1
remote:        Installing bootsnap 1.3.1 with native extensions
remote:        Fetching rb-inotify 0.9.10
remote:        Installing rb-inotify 0.9.10
remote:        Fetching turbolinks 5.1.1
remote:        Installing turbolinks 5.1.1
remote:        Fetching activesupport 5.2.1
remote:        Installing activesupport 5.2.1
remote:        Gem::Ext::BuildError: ERROR: Failed to build gem native extension.
remote:
remote:        current directory:
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13/ext/sqlite3
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/ruby-2.4.4/bin/ruby -r
remote:        ./siteconf20180818-271-1ev6e8b.rb extconf.rb
remote:        checking for sqlite3.h... no
remote:        sqlite3.h is missing. Try 'brew install sqlite3',
remote:        'yum install sqlite-devel' or 'apt-get install libsqlite3-dev'
remote:        and check your shared library search path (the
remote:        location where your sqlite3 shared library is located).
remote:        *** extconf.rb failed ***
remote:        Could not create Makefile due to some reason, probably lack of necessary
remote:        libraries and/or headers.  Check the mkmf.log file for more details.  You may
remote:        need configuration options.
remote:
remote:        Provided configuration options:
remote:         --with-opt-dir
remote:         --without-opt-dir
remote:         --with-opt-include
remote:         --without-opt-include=${opt-dir}/include
remote:         --with-opt-lib
remote:         --without-opt-lib=${opt-dir}/lib
remote:         --with-make-prog
remote:         --without-make-prog
remote:         --srcdir=.
remote:         --curdir
remote:        --ruby=/tmp/build_3a943693154e3419f1a462de7bde862a/vendor/ruby-2.4.4/bin/$(RUBY_BASE_NAME)
remote:         --with-sqlite3-config
remote:         --without-sqlite3-config
remote:         --with-pkg-config
remote:         --without-pkg-config
remote:         --with-sqlite3-dir
remote:         --without-sqlite3-dir
remote:         --with-sqlite3-include
remote:         --without-sqlite3-include=${sqlite3-dir}/include
remote:         --with-sqlite3-lib
remote:         --without-sqlite3-lib=${sqlite3-dir}/lib
remote:
remote:        To see why this extension failed to compile, please check the mkmf.log which can
remote:        be found here:
remote:
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/mkmf.log
remote:
remote:        extconf failed, exit code 1
remote:
remote:        Gem files will remain installed in
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13
remote:        for inspection.
remote:        Results logged to
remote:        /tmp/build_3a943693154e3419f1a462de7bde862a/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/gem_make.out
remote:
remote:        An error occurred while installing sqlite3 (1.3.13), and Bundler cannot
remote:        continue.
remote:        Make sure that `gem install sqlite3 -v '1.3.13'` succeeds before bundling.
remote:
remote:        In Gemfile:
remote:          sqlite3
remote:
remote:  !
remote:  !     Failed to install gems via Bundler.
remote:  !     Detected sqlite3 gem which is not supported on Heroku:
remote:  !     https://devcenter.heroku.com/articles/sqlite3
remote:  !
remote:  !     Push rejected, failed to compile Ruby app.
remote:
remote:  !     Push failed
remote: Verifying deploy...
remote:
remote: !       Push rejected to appsmipymes.
remote:
To https://git.heroku.com/appsmipymes.git
 ! [remote rejected] master -> master (pre-receive hook declined)
error: failed to push some refs to 'https://git.heroku.com/appsmipymes.git'

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Counting objects: 111, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (96/96), done.
Writing objects: 100% (111/111), 26.19 KiB | 1.54 MiB/s, done.
Total 111 (delta 2), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote:  !     Warning: Multiple default buildpacks reported the ability to handle this app. The first buildpack in the list below will be used.
remote:                         Detected buildpacks: Ruby,Node.js
remote:                         See https://devcenter.heroku.com/articles/buildpacks#buildpack-detect-order
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.4.4
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4
remote:        The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Fetching rake 12.3.1
remote:        Fetching concurrent-ruby 1.0.5
remote:        Fetching minitest 5.11.3
remote:        Installing minitest 5.11.3
remote:        Installing rake 12.3.1
remote:        Installing concurrent-ruby 1.0.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.7.1
remote:        Fetching mini_portile2 2.3.0
remote:        Installing erubi 1.7.1
remote:        Installing mini_portile2 2.3.0
remote:        Fetching crass 1.0.4
remote:        Fetching rack 2.0.5
remote:        Installing crass 1.0.4
remote:        Fetching nio4r 2.3.1
remote:        Installing rack 2.0.5
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 9.0.0
remote:        Installing arel 9.0.0
remote:        Fetching mimemagic 0.3.2
remote:        Fetching msgpack 1.2.4
remote:        Installing msgpack 1.2.4 with native extensions
remote:        Installing mimemagic 0.3.2
remote:        Using bundler 1.15.2
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching method_source 0.9.0
remote:        Installing method_source 0.9.0
remote:        Fetching thor 0.20.0
remote:        Installing thor 0.20.0
remote:        Fetching duktape 2.0.1.0
remote:        Installing duktape 2.0.1.0 with native extensions
remote:        Fetching ffi 1.9.25
remote:        Installing ffi 1.9.25 with native extensions
remote:        Fetching multi_json 1.13.1
remote:        Installing multi_json 1.13.1
remote:        Fetching pg 1.0.0
remote:        Installing pg 1.0.0 with native extensions
remote:        Fetching puma 3.12.0
remote:        Installing puma 3.12.0 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching tilt 2.0.8
remote:        Installing tilt 2.0.8
remote:        Fetching sqlite3 1.3.13
remote:        Installing sqlite3 1.3.13 with native extensions
remote:        Fetching turbolinks-source 5.1.0
remote:        Installing turbolinks-source 5.1.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching i18n 1.1.0
remote:        Installing i18n 1.1.0
remote:        Fetching nokogiri 1.8.4
remote:        Installing nokogiri 1.8.4 with native extensions
remote:        Fetching websocket-driver 0.7.0
remote:        Installing websocket-driver 0.7.0 with native extensions
remote:        Fetching mail 2.7.0
remote:        Installing mail 2.7.0
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching marcel 0.3.2
remote:        Installing marcel 0.3.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching uglifier 4.1.18
remote:        Installing uglifier 4.1.18
remote:        Fetching bootsnap 1.3.1
remote:        Installing bootsnap 1.3.1 with native extensions
remote:        Fetching rb-inotify 0.9.10
remote:        Installing rb-inotify 0.9.10
remote:        Fetching turbolinks 5.1.1
remote:        Installing turbolinks 5.1.1
remote:        Fetching activesupport 5.2.1
remote:        Installing activesupport 5.2.1
remote:        Gem::Ext::BuildError: ERROR: Failed to build gem native extension.
remote:
remote:        current directory:
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13/ext/sqlite3
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/ruby-2.4.4/bin/ruby -r
remote:        ./siteconf20180818-260-zfl28q.rb extconf.rb
remote:        checking for sqlite3.h... no
remote:        sqlite3.h is missing. Try 'brew install sqlite3',
remote:        'yum install sqlite-devel' or 'apt-get install libsqlite3-dev'
remote:        and check your shared library search path (the
remote:        location where your sqlite3 shared library is located).
remote:        *** extconf.rb failed ***
remote:        Could not create Makefile due to some reason, probably lack of necessary
remote:        libraries and/or headers.  Check the mkmf.log file for more details.  You may
remote:        need configuration options.
remote:
remote:        Provided configuration options:
remote:         --with-opt-dir
remote:         --without-opt-dir
remote:         --with-opt-include
remote:         --without-opt-include=${opt-dir}/include
remote:         --with-opt-lib
remote:         --without-opt-lib=${opt-dir}/lib
remote:         --with-make-prog
remote:         --without-make-prog
remote:         --srcdir=.
remote:         --curdir
remote:        --ruby=/tmp/build_f65bada0071010c7625282146c2c668c/vendor/ruby-2.4.4/bin/$(RUBY_BASE_NAME)
remote:         --with-sqlite3-config
remote:         --without-sqlite3-config
remote:         --with-pkg-config
remote:         --without-pkg-config
remote:         --with-sqlite3-dir
remote:         --without-sqlite3-dir
remote:         --with-sqlite3-include
remote:         --without-sqlite3-include=${sqlite3-dir}/include
remote:         --with-sqlite3-lib
remote:         --without-sqlite3-lib=${sqlite3-dir}/lib
remote:
remote:        To see why this extension failed to compile, please check the mkmf.log which can
remote:        be found here:
remote:
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/mkmf.log
remote:
remote:        extconf failed, exit code 1
remote:
remote:        Gem files will remain installed in
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13
remote:        for inspection.
remote:        Results logged to
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/gem_make.out
remote:
remote:        An error occurred while installing sqlite3 (1.3.13), and Bundler cannot
remote:        continue.
remote:        Make sure that `gem install sqlite3 -v '1.3.13'` succeeds before bundling.
remote:
remote:        In Gemfile:
remote:          sqlite3
remote:        Bundler Output: The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Fetching rake 12.3.1
remote:        Fetching concurrent-ruby 1.0.5
remote:        Fetching minitest 5.11.3
remote:        Installing minitest 5.11.3
remote:        Installing rake 12.3.1
remote:        Installing concurrent-ruby 1.0.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.7.1
remote:        Fetching mini_portile2 2.3.0
remote:        Installing erubi 1.7.1
remote:        Installing mini_portile2 2.3.0
remote:        Fetching crass 1.0.4
remote:        Fetching rack 2.0.5
remote:        Installing crass 1.0.4
remote:        Fetching nio4r 2.3.1
remote:        Installing rack 2.0.5
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 9.0.0
remote:        Installing arel 9.0.0
remote:        Fetching mimemagic 0.3.2
remote:        Fetching msgpack 1.2.4
remote:        Installing msgpack 1.2.4 with native extensions
remote:        Installing mimemagic 0.3.2
remote:        Using bundler 1.15.2
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching method_source 0.9.0
remote:        Installing method_source 0.9.0
remote:        Fetching thor 0.20.0
remote:        Installing thor 0.20.0
remote:        Fetching duktape 2.0.1.0
remote:        Installing duktape 2.0.1.0 with native extensions
remote:        Fetching ffi 1.9.25
remote:        Installing ffi 1.9.25 with native extensions
remote:        Fetching multi_json 1.13.1
remote:        Installing multi_json 1.13.1
remote:        Fetching pg 1.0.0
remote:        Installing pg 1.0.0 with native extensions
remote:        Fetching puma 3.12.0
remote:        Installing puma 3.12.0 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching tilt 2.0.8
remote:        Installing tilt 2.0.8
remote:        Fetching sqlite3 1.3.13
remote:        Installing sqlite3 1.3.13 with native extensions
remote:        Fetching turbolinks-source 5.1.0
remote:        Installing turbolinks-source 5.1.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching i18n 1.1.0
remote:        Installing i18n 1.1.0
remote:        Fetching nokogiri 1.8.4
remote:        Installing nokogiri 1.8.4 with native extensions
remote:        Fetching websocket-driver 0.7.0
remote:        Installing websocket-driver 0.7.0 with native extensions
remote:        Fetching mail 2.7.0
remote:        Installing mail 2.7.0
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching marcel 0.3.2
remote:        Installing marcel 0.3.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching uglifier 4.1.18
remote:        Installing uglifier 4.1.18
remote:        Fetching bootsnap 1.3.1
remote:        Installing bootsnap 1.3.1 with native extensions
remote:        Fetching rb-inotify 0.9.10
remote:        Installing rb-inotify 0.9.10
remote:        Fetching turbolinks 5.1.1
remote:        Installing turbolinks 5.1.1
remote:        Fetching activesupport 5.2.1
remote:        Installing activesupport 5.2.1
remote:        Gem::Ext::BuildError: ERROR: Failed to build gem native extension.
remote:
remote:        current directory:
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13/ext/sqlite3
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/ruby-2.4.4/bin/ruby -r
remote:        ./siteconf20180818-260-zfl28q.rb extconf.rb
remote:        checking for sqlite3.h... no
remote:        sqlite3.h is missing. Try 'brew install sqlite3',
remote:        'yum install sqlite-devel' or 'apt-get install libsqlite3-dev'
remote:        and check your shared library search path (the
remote:        location where your sqlite3 shared library is located).
remote:        *** extconf.rb failed ***
remote:        Could not create Makefile due to some reason, probably lack of necessary
remote:        libraries and/or headers.  Check the mkmf.log file for more details.  You may
remote:        need configuration options.
remote:
remote:        Provided configuration options:
remote:         --with-opt-dir
remote:         --without-opt-dir
remote:         --with-opt-include
remote:         --without-opt-include=${opt-dir}/include
remote:         --with-opt-lib
remote:         --without-opt-lib=${opt-dir}/lib
remote:         --with-make-prog
remote:         --without-make-prog
remote:         --srcdir=.
remote:         --curdir
remote:        --ruby=/tmp/build_f65bada0071010c7625282146c2c668c/vendor/ruby-2.4.4/bin/$(RUBY_BASE_NAME)
remote:         --with-sqlite3-config
remote:         --without-sqlite3-config
remote:         --with-pkg-config
remote:         --without-pkg-config
remote:         --with-sqlite3-dir
remote:         --without-sqlite3-dir
remote:         --with-sqlite3-include
remote:         --without-sqlite3-include=${sqlite3-dir}/include
remote:         --with-sqlite3-lib
remote:         --without-sqlite3-lib=${sqlite3-dir}/lib
remote:
remote:        To see why this extension failed to compile, please check the mkmf.log which can
remote:        be found here:
remote:
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/mkmf.log
remote:
remote:        extconf failed, exit code 1
remote:
remote:        Gem files will remain installed in
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/gems/sqlite3-1.3.13
remote:        for inspection.
remote:        Results logged to
remote:        /tmp/build_f65bada0071010c7625282146c2c668c/vendor/bundle/ruby/2.4.0/extensions/x86_64-linux/2.4.0/sqlite3-1.3.13/gem_make.out
remote:
remote:        An error occurred while installing sqlite3 (1.3.13), and Bundler cannot
remote:        continue.
remote:        Make sure that `gem install sqlite3 -v '1.3.13'` succeeds before bundling.
remote:
remote:        In Gemfile:
remote:          sqlite3
remote:
remote:  !
remote:  !     Failed to install gems via Bundler.
remote:  !     Detected sqlite3 gem which is not supported on Heroku:
remote:  !     https://devcenter.heroku.com/articles/sqlite3
remote:  !
remote:  !     Push rejected, failed to compile Ruby app.
remote:
remote:  !     Push failed
remote: Verifying deploy...
remote:
remote: !       Push rejected to appsmipymes.
remote:
To https://git.heroku.com/appsmipymes.git
 ! [remote rejected] master -> master (pre-receive hook declined)
error: failed to push some refs to 'https://git.heroku.com/appsmipymes.git'

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   Gemfile
        modified:   Gemfile.lock

no changes added to commit (use "git add" and/or "git commit -a")

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   Gemfile
        modified:   Gemfile.lock

no changes added to commit (use "git add" and/or "git commit -a")

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add .
warning: LF will be replaced by CRLF in Gemfile.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in Gemfile.lock.
The file will have its original line endings in your working directory.

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git commit
[master c080dd7] proyecto yo aprendo:
 Committer: APRENDIZ SENA LABORATORIOS <PASANTE@Laboratorios.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 1 insertion(+), 3 deletions(-)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Counting objects: 115, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (100/100), done.
Writing objects: 100% (115/115), 26.46 KiB | 1.20 MiB/s, done.
Total 115 (delta 6), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote:  !     Warning: Multiple default buildpacks reported the ability to handle this app. The first buildpack in the list below will be used.
remote:                         Detected buildpacks: Ruby,Node.js
remote:                         See https://devcenter.heroku.com/articles/buildpacks#buildpack-detect-order
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.4.4
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4
remote:        The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Fetching rake 12.3.1
remote:        Fetching concurrent-ruby 1.0.5
remote:        Fetching minitest 5.11.3
remote:        Installing minitest 5.11.3
remote:        Installing rake 12.3.1
remote:        Installing concurrent-ruby 1.0.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.7.1
remote:        Installing erubi 1.7.1
remote:        Fetching mini_portile2 2.3.0
remote:        Fetching crass 1.0.4
remote:        Fetching rack 2.0.5
remote:        Installing mini_portile2 2.3.0
remote:        Installing crass 1.0.4
remote:        Fetching nio4r 2.3.1
remote:        Installing rack 2.0.5
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 9.0.0
remote:        Installing arel 9.0.0
remote:        Fetching mimemagic 0.3.2
remote:        Fetching msgpack 1.2.4
remote:        Installing msgpack 1.2.4 with native extensions
remote:        Installing mimemagic 0.3.2
remote:        Using bundler 1.15.2
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching method_source 0.9.0
remote:        Installing method_source 0.9.0
remote:        Fetching thor 0.20.0
remote:        Installing thor 0.20.0
remote:        Fetching duktape 2.0.1.0
remote:        Installing duktape 2.0.1.0 with native extensions
remote:        Fetching ffi 1.9.25
remote:        Installing ffi 1.9.25 with native extensions
remote:        Fetching multi_json 1.13.1
remote:        Installing multi_json 1.13.1
remote:        Fetching pg 1.0.0
remote:        Installing pg 1.0.0 with native extensions
remote:        Fetching puma 3.12.0
remote:        Installing puma 3.12.0 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching tilt 2.0.8
remote:        Installing tilt 2.0.8
remote:        Fetching turbolinks-source 5.1.0
remote:        Installing turbolinks-source 5.1.0
remote:        Fetching i18n 1.1.0
remote:        Installing i18n 1.1.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching nokogiri 1.8.4
remote:        Installing nokogiri 1.8.4 with native extensions
remote:        Fetching websocket-driver 0.7.0
remote:        Installing websocket-driver 0.7.0 with native extensions
remote:        Fetching mail 2.7.0
remote:        Installing mail 2.7.0
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching marcel 0.3.2
remote:        Installing marcel 0.3.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching uglifier 4.1.18
remote:        Installing uglifier 4.1.18
remote:        Fetching bootsnap 1.3.1
remote:        Installing bootsnap 1.3.1 with native extensions
remote:        Fetching rb-inotify 0.9.10
remote:        Installing rb-inotify 0.9.10
remote:        Fetching turbolinks 5.1.1
remote:        Installing turbolinks 5.1.1
remote:        Fetching activesupport 5.2.1
remote:        Installing activesupport 5.2.1
remote:        Fetching loofah 2.2.2
remote:        Installing loofah 2.2.2
remote:        Fetching sass-listen 4.0.0
remote:        Fetching rails-dom-testing 2.0.3
remote:        Installing sass-listen 4.0.0
remote:        Installing rails-dom-testing 2.0.3
remote:        Fetching globalid 0.4.1
remote:        Installing globalid 0.4.1
remote:        Fetching activemodel 5.2.1
remote:        Installing activemodel 5.2.1
remote:        Fetching jbuilder 2.7.0
remote:        Installing jbuilder 2.7.0
remote:        Fetching rails-html-sanitizer 1.0.4
remote:        Installing rails-html-sanitizer 1.0.4
remote:        Fetching sass 3.5.7
remote:        Fetching activejob 5.2.1
remote:        Installing activejob 5.2.1
remote:        Installing sass 3.5.7
remote:        Fetching activerecord 5.2.1
remote:        Fetching actionview 5.2.1
remote:        Installing actionview 5.2.1
remote:        Installing activerecord 5.2.1
remote:        Fetching actionpack 5.2.1
remote:        Installing actionpack 5.2.1
remote:        Fetching actionmailer 5.2.1
remote:        Fetching actioncable 5.2.1
remote:        Fetching activestorage 5.2.1
remote:        Installing actionmailer 5.2.1
remote:        Installing activestorage 5.2.1
remote:        Installing actioncable 5.2.1
remote:        Fetching railties 5.2.1
remote:        Installing railties 5.2.1
remote:        Fetching sprockets-rails 3.2.1
remote:        Installing sprockets-rails 3.2.1
remote:        Fetching rails 5.2.1
remote:        Fetching sass-rails 5.0.7
remote:        Fetching coffee-rails 4.2.2
remote:        Installing coffee-rails 4.2.2
remote:        Installing rails 5.2.1
remote:        Installing sass-rails 5.0.7
remote:        Bundle complete! 16 Gemfile dependencies, 62 gems now installed.
remote:        Gems in the groups development and test were not installed.
remote:        Bundled gems are installed into ./vendor/bundle.
remote:        Post-install message from sass:
remote:
remote:        Ruby Sass is deprecated and will be unmaintained as of 26 March 2019.
remote:
remote:        * If you use Sass as a command-line tool, we recommend using Dart Sass, the new
remote:          primary implementation: https://sass-lang.com/install
remote:
remote:        * If you use Sass as a plug-in for a Ruby web framework, we recommend using the
remote:          sassc gem: https://github.com/sass/sassc-ruby#readme
remote:
remote:        * For more details, please refer to the Sass blog:
remote:          http://sass.logdown.com/posts/7081811
remote:
remote:        Bundle completed (46.27s)
remote:        Cleaning up the bundler cache.
remote:        The latest bundler is 1.16.3, but you are currently running 1.15.2.
remote:        To update, run `gem install bundler`
remote: -----> Installing node-v8.10.0-linux-x64
remote: -----> Detecting rake tasks
remote: -----> Preparing app for Rails asset pipeline
remote:        Running: rake assets:precompile
remote:        Yarn executable was not detected in the system.
remote:        Download Yarn at https://yarnpkg.com/en/docs/install
remote:        I, [2018-08-18T16:58:27.640917 #1509]  INFO -- : Writing /tmp/build_498e6a35f75c562cb7fa52fb4d1b4416/public/assets/application-ed2ca553e56aa25736b603305fe4fbd441315d5226b21d094a4dd2be61c9b990.js
remote:        I, [2018-08-18T16:58:27.641575 #1509]  INFO -- : Writing /tmp/build_498e6a35f75c562cb7fa52fb4d1b4416/public/assets/application-ed2ca553e56aa25736b603305fe4fbd441315d5226b21d094a4dd2be61c9b990.js.gz
remote:        I, [2018-08-18T16:58:27.673545 #1509]  INFO -- : Writing /tmp/build_498e6a35f75c562cb7fa52fb4d1b4416/public/assets/application-35729bfbaf9967f119234595ed222f7ab14859f304ab0acc5451afb387f637fa.css
remote:        I, [2018-08-18T16:58:27.673962 #1509]  INFO -- : Writing /tmp/build_498e6a35f75c562cb7fa52fb4d1b4416/public/assets/application-35729bfbaf9967f119234595ed222f7ab14859f304ab0acc5451afb387f637fa.css.gz
remote:        Asset precompilation completed (19.49s)
remote:        Cleaning assets
remote:        Running: rake assets:clean
remote: -----> Detecting rails configuration
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: ###### WARNING:
remote:
remote:        You set your `config.active_storage.service` to :local in production.
remote:        If you are uploading files to this app, they will not persist after the app
remote:        is restarted, on one-off dynos, or if the app has multiple dynos.
remote:        Heroku applications have an ephemeral file system. To
remote:        persist uploaded files, please use a service such as S3 and update your Rails
remote:        configuration.
remote:
remote:        For more information can be found in this article:
remote:          https://devcenter.heroku.com/articles/active-storage-on-heroku
remote:
remote:
remote: ###### WARNING:
remote:
remote:        We detected that some binary dependencies required to
remote:        use all the preview features of Active Storage are not
remote:        present on this system.
remote:
remote:        For more information please see:
remote:          https://devcenter.heroku.com/articles/active-storage-on-heroku
remote:
remote:
remote:
remote: -----> Discovering process types
remote:        Procfile declares types     -> web
remote:        Default types for buildpack -> console, rake, worker
remote:
remote: -----> Compressing...
remote:        Done: 50.5M
remote: -----> Launching...
remote:        Released v5
remote:        https://appsmipymes.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/appsmipymes.git
 * [new branch]      master -> master

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ ^C

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ rails s
=> Booting Puma
=> Rails 5.2.1 application starting in development
=> Run `rails server -h` for more startup options
*** SIGUSR2 not implemented, signal based restart unavailable!
*** SIGUSR1 not implemented, signal based restart unavailable!
*** SIGHUP not implemented, signal based logs reopening unavailable!
Puma starting in single mode...
* Version 3.12.0 (ruby 2.4.4-p296), codename: Llamas in Pajamas
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://0.0.0.0:3000
Use Ctrl-C to stop
Started GET "/home/index.html" for 127.0.0.1 at 2018-08-18 13:33:23 -0500

ActiveRecord::PendingMigrationError (

Migrations are pending. To resolve this issue, run:

        bin/rails db:migrate RAILS_ENV=development

):

activerecord (5.2.1) lib/active_record/migration.rb:579:in `check_pending!'
activerecord (5.2.1) lib/active_record/migration.rb:556:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/callbacks.rb:28:in `block in call'
activesupport (5.2.1) lib/active_support/callbacks.rb:98:in `run_callbacks'
actionpack (5.2.1) lib/action_dispatch/middleware/callbacks.rb:26:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/executor.rb:14:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/debug_exceptions.rb:61:in `call'
web-console (3.6.2) lib/web_console/middleware.rb:135:in `call_app'
web-console (3.6.2) lib/web_console/middleware.rb:30:in `block in call'
web-console (3.6.2) lib/web_console/middleware.rb:20:in `catch'
web-console (3.6.2) lib/web_console/middleware.rb:20:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/show_exceptions.rb:33:in `call'
railties (5.2.1) lib/rails/rack/logger.rb:38:in `call_app'
railties (5.2.1) lib/rails/rack/logger.rb:26:in `block in call'
activesupport (5.2.1) lib/active_support/tagged_logging.rb:71:in `block in tagged'
activesupport (5.2.1) lib/active_support/tagged_logging.rb:28:in `tagged'
activesupport (5.2.1) lib/active_support/tagged_logging.rb:71:in `tagged'
railties (5.2.1) lib/rails/rack/logger.rb:26:in `call'
sprockets-rails (3.2.1) lib/sprockets/rails/quiet_assets.rb:13:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/remote_ip.rb:81:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/request_id.rb:27:in `call'
rack (2.0.5) lib/rack/method_override.rb:22:in `call'
rack (2.0.5) lib/rack/runtime.rb:22:in `call'
activesupport (5.2.1) lib/active_support/cache/strategy/local_cache_middleware.rb:29:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/executor.rb:14:in `call'
actionpack (5.2.1) lib/action_dispatch/middleware/static.rb:127:in `call'
rack (2.0.5) lib/rack/sendfile.rb:111:in `call'
railties (5.2.1) lib/rails/engine.rb:524:in `call'
puma (3.12.0) lib/puma/configuration.rb:225:in `call'
puma (3.12.0) lib/puma/server.rb:658:in `handle_request'
puma (3.12.0) lib/puma/server.rb:472:in `process_client'
puma (3.12.0) lib/puma/server.rb:332:in `block in run'
puma (3.12.0) lib/puma/thread_pool.rb:133:in `block in spawn_thread'
- Gracefully stopping, waiting for requests to finish
=== puma shutdown: 2018-08-18 13:36:46 -0500 ===
- Goodbye!
Exiting

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git heroku run rake db:migrate
git: 'heroku' is not a git command. See 'git --help'.

The most similar command is
        checkout

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ heroku run rake db:migrate
Running rake db:migrate on appsmipymes... starting, run.9168 (Free)
Running rake db:migrate on appsmipymes... connecting, run.9168 (Free)
Running rake db:migrate on appsmipymes... up, run.9168 (Free)
D, [2018-08-18T18:39:49.083662 #4] DEBUG -- :    (16.8ms)  CREATE TABLE "schema_migrations" ("version" character varying NOT NULL PRIMARY KEY)
D, [2018-08-18T18:39:49.104827 #4] DEBUG -- :    (14.4ms)  CREATE TABLE "ar_internal_metadata" ("key" character varying NOT NULL PRIMARY KEY, "value" character varying, "created_at" timestamp NOT NULL, "updated_at" timestamp NOT NULL)
D, [2018-08-18T18:39:49.111955 #4] DEBUG -- :    (2.9ms)  SELECT pg_try_advisory_lock(1981710982418237175)
D, [2018-08-18T18:39:49.188506 #4] DEBUG -- :    (1.9ms)  SELECT "schema_migrations"."version" FROM "schema_migrations" ORDER BY "schema_migrations"."version" ASC
I, [2018-08-18T18:39:49.190520 #4]  INFO -- : Migrating to CreateUsers (20180818143755)
D, [2018-08-18T18:39:49.208210 #4] DEBUG -- :    (1.1ms)  BEGIN
== 20180818143755 CreateUsers: migrating ======================================
-- create_table(:users)
D, [2018-08-18T18:39:49.217593 #4] DEBUG -- :    (8.1ms)  CREATE TABLE "users" ("id" bigserial primary key, "name" character varying, "email" character varying, "created_at" timestamp NOT NULL, "updated_at" timestamp NOT NULL)
   -> 0.0092s
== 20180818143755 CreateUsers: migrated (0.0093s) =============================

D, [2018-08-18T18:39:49.230320 #4] DEBUG -- :   ActiveRecord::SchemaMigration Create (3.0ms)  INSERT INTO "schema_migrations" ("version") VALUES ($1) RETURNING "version"  [["version", "20180818143755"]]
D, [2018-08-18T18:39:49.236009 #4] DEBUG -- :    (5.1ms)  COMMIT
D, [2018-08-18T18:39:49.262345 #4] DEBUG -- :   ActiveRecord::InternalMetadata Load (3.8ms)  SELECT  "ar_internal_metadata".* FROM "ar_internal_metadata" WHERE "ar_internal_metadata"."key" = $1 LIMIT $2  [["key", "environment"], ["LIMIT", 1]]
D, [2018-08-18T18:39:49.287180 #4] DEBUG -- :    (0.8ms)  BEGIN
D, [2018-08-18T18:39:49.290097 #4] DEBUG -- :   ActiveRecord::InternalMetadata Create (1.3ms)  INSERT INTO "ar_internal_metadata" ("key", "value", "created_at", "updated_at") VALUES ($1, $2, $3, $4) RETURNING "key"  [["key", "environment"], ["value", "production"], ["created_at", "2018-08-18 18:39:49.287620"], ["updated_at", "2018-08-18 18:39:49.287620"]]
D, [2018-08-18T18:39:49.292225 #4] DEBUG -- :    (1.4ms)  COMMIT
D, [2018-08-18T18:39:49.293639 #4] DEBUG -- :    (0.9ms)  SELECT pg_advisory_unlock(1981710982418237175)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ ^C

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Everything up-to-date

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add .
warning: LF will be replaced by CRLF in config/routes.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/javascripts/home.coffee.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/assets/stylesheets/home.scss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/controllers/home_controller.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/helpers/home_helper.rb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app/views/home/index.html.erb.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in test/controllers/home_controller_test.rb.
The file will have its original line endings in your working directory.

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   app/assets/javascripts/home.coffee
        new file:   app/assets/stylesheets/home.scss
        new file:   app/controllers/home_controller.rb
        new file:   app/helpers/home_helper.rb
        new file:   app/views/home/index.html.erb
        modified:   config/routes.rb
        new file:   public/imags/imagen.jpg
        new file:   rails
        new file:   test/controllers/home_controller_test.rb


PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git commit
[master 7e3a09e] imagen
 Committer: APRENDIZ SENA LABORATORIOS <PASANTE@Laboratorios.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 9 files changed, 25 insertions(+)
 create mode 100644 app/assets/javascripts/home.coffee
 create mode 100644 app/assets/stylesheets/home.scss
 create mode 100644 app/controllers/home_controller.rb
 create mode 100644 app/helpers/home_helper.rb
 create mode 100644 app/views/home/index.html.erb
 create mode 100644 public/imags/imagen.jpg
 create mode 100644 rails
 create mode 100644 test/controllers/home_controller_test.rb

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream heroku master


PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Counting objects: 22, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (19/19), done.
Writing objects: 100% (22/22), 30.33 KiB | 7.58 MiB/s, done.
Total 22 (delta 8), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.4.4
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4
remote:        The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Resolving dependencies...
remote:        Using rake 12.3.1
remote:        Using concurrent-ruby 1.0.5
remote:        Using minitest 5.11.3
remote:        Using thread_safe 0.3.6
remote:        Using builder 3.2.3
remote:        Using erubi 1.7.1
remote:        Using mini_portile2 2.3.0
remote:        Using crass 1.0.4
remote:        Using rack 2.0.5
remote:        Using nio4r 2.3.1
remote:        Using websocket-extensions 0.1.3
remote:        Using mini_mime 1.0.1
remote:        Using arel 9.0.0
remote:        Using mimemagic 0.3.2
remote:        Using msgpack 1.2.4
remote:        Using bundler 1.15.2
remote:        Using coffee-script-source 1.12.2
remote:        Using execjs 2.7.0
remote:        Using method_source 0.9.0
remote:        Using thor 0.20.0
remote:        Using duktape 2.0.1.0
remote:        Using ffi 1.9.25
remote:        Using multi_json 1.13.1
remote:        Using pg 1.0.0
remote:        Using puma 3.12.0
remote:        Using rb-fsevent 0.10.3
remote:        Using tilt 2.0.8
remote:        Using turbolinks-source 5.1.0
remote:        Using i18n 1.1.0
remote:        Using tzinfo 1.2.5
remote:        Using nokogiri 1.8.4
remote:        Using rack-test 1.1.0
remote:        Using sprockets 3.7.2
remote:        Using mail 2.7.0
remote:        Using websocket-driver 0.7.0
remote:        Using bootsnap 1.3.1
remote:        Using marcel 0.3.2
remote:        Using uglifier 4.1.18
remote:        Using coffee-script 2.4.1
remote:        Using rb-inotify 0.9.10
remote:        Using turbolinks 5.1.1
remote:        Using activesupport 5.2.1
remote:        Using loofah 2.2.2
remote:        Using sass-listen 4.0.0
remote:        Using sass 3.5.7
remote:        Using rails-html-sanitizer 1.0.4
remote:        Using rails-dom-testing 2.0.3
remote:        Using globalid 0.4.1
remote:        Using activemodel 5.2.1
remote:        Using jbuilder 2.7.0
remote:        Using activejob 5.2.1
remote:        Using activerecord 5.2.1
remote:        Using actionview 5.2.1
remote:        Using actionpack 5.2.1
remote:        Using actioncable 5.2.1
remote:        Using actionmailer 5.2.1
remote:        Using activestorage 5.2.1
remote:        Using railties 5.2.1
remote:        Using sprockets-rails 3.2.1
remote:        Using coffee-rails 4.2.2
remote:        Using rails 5.2.1
remote:        Using sass-rails 5.0.7
remote:        Bundle complete! 16 Gemfile dependencies, 62 gems now installed.
remote:        Gems in the groups development and test were not installed.
remote:        Bundled gems are installed into ./vendor/bundle.
remote:        Bundle completed (3.54s)
remote:        Cleaning up the bundler cache.
remote:        The latest bundler is 1.16.3, but you are currently running 1.15.2.
remote:        To update, run `gem install bundler`
remote: -----> Installing node-v8.10.0-linux-x64
remote: -----> Detecting rake tasks
remote: -----> Preparing app for Rails asset pipeline
remote:        Running: rake assets:precompile
remote:        Yarn executable was not detected in the system.
remote:        Download Yarn at https://yarnpkg.com/en/docs/install
remote:        I, [2018-08-18T19:59:09.662626 #413]  INFO -- : Writing /tmp/build_a6bb9efa7583e20dce14b6778eca0a3a/public/assets/application-608a101b8fa7bf1f7d89468bc241e7fcd1632973f9f3c1b5a78a66b719d80af4.js
remote:        I, [2018-08-18T19:59:09.663762 #413]  INFO -- : Writing /tmp/build_a6bb9efa7583e20dce14b6778eca0a3a/public/assets/application-608a101b8fa7bf1f7d89468bc241e7fcd1632973f9f3c1b5a78a66b719d80af4.js.gz
remote:        Asset precompilation completed (20.36s)
remote:        Cleaning assets
remote:        Running: rake assets:clean
remote: -----> Detecting rails configuration
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generated on Windows.
remote:        Bundler will do a full resolve so native gems are handled properly.
remote:        This may result in unexpected gem versions being used in your app.
remote:        In rare occasions Bundler may not be able to resolve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-windows-gemfile
remote:
remote: ###### WARNING:
remote:
remote:        You set your `config.active_storage.service` to :local in production.
remote:        If you are uploading files to this app, they will not persist after the app
remote:        is restarted, on one-off dynos, or if the app has multiple dynos.
remote:        Heroku applications have an ephemeral file system. To
remote:        persist uploaded files, please use a service such as S3 and update your Rails
remote:        configuration.
remote:
remote:        For more information can be found in this article:
remote:          https://devcenter.heroku.com/articles/active-storage-on-heroku
remote:
remote:
remote: ###### WARNING:
remote:
remote:        We detected that some binary dependencies required to
remote:        use all the preview features of Active Storage are not
remote:        present on this system.
remote:
remote:        For more information please see:
remote:          https://devcenter.heroku.com/articles/active-storage-on-heroku
remote:
remote:
remote:
remote: -----> Discovering process types
remote:        Procfile declares types     -> web
remote:        Default types for buildpack -> console, rake, worker
remote:
remote: -----> Compressing...
remote:        Done: 50.6M
remote: -----> Launching...
remote:        Released v6
remote:        https://appsmipymes.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/appsmipymes.git
   c080dd7..7e3a09e  master -> master

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in worki                                                                                       ng directory)

        modified:   app/views/home/index.html.erb

no changes added to commit (use "git add" and/or "git commit -                                                                                       a")

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add .
warning: LF will be replaced by CRLF in app/views/home/index.h                                                                                       tml.erb.
The file will have its original line endings in your working d                                                                                       irectory.

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   app/views/home/index.html.erb

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in worki                                                                                       ng directory)

        modified:   app/views/home/index.html.erb


PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git add .
warning: LF will be replaced by CRLF in app/views/home/index.h                                                                                       tml.erb.
The file will have its original line endings in your working d                                                                                       irectory.

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git commit -am "imagenes"
[master 5dcbc26] imagenes
 Committer: APRENDIZ SENA LABORATORIOS <PASANTE@Laboratorios.n                                                                                       et>
Your name and email address were configured automatically base                                                                                       d
on your username and hostname. Please check that they are accu                                                                                       rate.
You can suppress this message by setting them explicitly. Run                                                                                        the
following command and follow the instructions in your editor t                                                                                       o edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commi                                                                                       t with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)

PASANTE@B7-502-03 MINGW64 ~/Desktop/yoaprendo (master)
$ git push heroku master
Counting objects: 6, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 582 bytes | 582.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.4.4
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generate                                                                                       d on Windows.
remote:        Bundler will do a full resolve so native gems a                                                                                       re handled properly.
remote:        This may result in unexpected gem versions bein                                                                                       g used in your app.
remote:        In rare occasions Bundler may not be able to re                                                                                       solve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-w                                                                                       indows-gemfile
remote:
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:t                                                                                       est --path vendor/bundle --binstubs vendor/bundle/bin -j4
remote:        The dependency tzinfo-data (>= 0) will be unuse                                                                                       d by any of the platforms Bundler is installing for. Bundler i                                                                                       s installing for ruby but the dependency is only for x86-mingw                                                                                       32, x86-mswin32, x64-mingw32, java. To add those platforms to                                                                                        the bundle, run `bundle lock --add-platform x86-mingw32 x86-ms                                                                                       win32 x64-mingw32 java`.
remote:        Fetching gem metadata from https://rubygems.org                                                                                       /..........
remote:        Fetching version metadata from https://rubygems                                                                                       .org/..
remote:        Fetching dependency metadata from https://rubyg                                                                                       ems.org/.
remote:        Resolving dependencies...
remote:        Using rake 12.3.1
remote:        Using concurrent-ruby 1.0.5
remote:        Using minitest 5.11.3
remote:        Using thread_safe 0.3.6
remote:        Using builder 3.2.3
remote:        Using erubi 1.7.1
remote:        Using mini_portile2 2.3.0
remote:        Using crass 1.0.4
remote:        Using rack 2.0.5
remote:        Using nio4r 2.3.1
remote:        Using websocket-extensions 0.1.3
remote:        Using mini_mime 1.0.1
remote:        Using arel 9.0.0
remote:        Using mimemagic 0.3.2
remote:        Using msgpack 1.2.4
remote:        Using bundler 1.15.2
remote:        Using coffee-script-source 1.12.2
remote:        Using execjs 2.7.0
remote:        Using method_source 0.9.0
remote:        Using thor 0.20.0
remote:        Using duktape 2.0.1.0
remote:        Using ffi 1.9.25
remote:        Using multi_json 1.13.1
remote:        Using pg 1.0.0
remote:        Using puma 3.12.0
remote:        Using rb-fsevent 0.10.3
remote:        Using tilt 2.0.8
remote:        Using turbolinks-source 5.1.0
remote:        Using tzinfo 1.2.5
remote:        Using i18n 1.1.0
remote:        Using nokogiri 1.8.4
remote:        Using mail 2.7.0
remote:        Using marcel 0.3.2
remote:        Using bootsnap 1.3.1
remote:        Using coffee-script 2.4.1
remote:        Using uglifier 4.1.18
remote:        Using websocket-driver 0.7.0
remote:        Using rb-inotify 0.9.10
remote:        Using rack-test 1.1.0
remote:        Using sprockets 3.7.2
remote:        Using turbolinks 5.1.1
remote:        Using activesupport 5.2.1
remote:        Using loofah 2.2.2
remote:        Using sass-listen 4.0.0
remote:        Using rails-html-sanitizer 1.0.4
remote:        Using sass 3.5.7
remote:        Using rails-dom-testing 2.0.3
remote:        Using globalid 0.4.1
remote:        Using activemodel 5.2.1
remote:        Using jbuilder 2.7.0
remote:        Using actionview 5.2.1
remote:        Using activejob 5.2.1
remote:        Using activerecord 5.2.1
remote:        Using actionpack 5.2.1
remote:        Using actioncable 5.2.1
remote:        Using actionmailer 5.2.1
remote:        Using activestorage 5.2.1
remote:        Using railties 5.2.1
remote:        Using sprockets-rails 3.2.1
remote:        Using coffee-rails 4.2.2
remote:        Using rails 5.2.1
remote:        Using sass-rails 5.0.7
remote:        Bundle complete! 16 Gemfile dependencies, 62 ge                                                                                       ms now installed.
remote:        Gems in the groups development and test were no                                                                                       t installed.
remote:        Bundled gems are installed into ./vendor/bundle                                                                                       .
remote:        Bundle completed (3.21s)
remote:        Cleaning up the bundler cache.
remote:        The latest bundler is 1.16.3, but you are curre                                                                                       ntly running 1.15.2.
remote:        To update, run `gem install bundler`
remote: -----> Installing node-v8.10.0-linux-x64
remote: -----> Detecting rake tasks
remote: -----> Preparing app for Rails asset pipeline
remote:        Running: rake assets:precompile
remote:        Yarn executable was not detected in the system
remote:        Download Yarn at https://yarnpkg.com/en/docs/in                                                                                       stall
remote:        Asset precompilation completed (1.24s)
remote:        Cleaning assets
remote:        Running: rake assets:clean
remote: -----> Detecting rails configuration
remote:
remote: ###### WARNING:
remote:
remote:        Removing `Gemfile.lock` because it was generate                                                                                       d on Windows.
remote:        Bundler will do a full resolve so native gems a                                                                                       re handled properly.
remote:        This may result in unexpected gem versions bein                                                                                       g used in your app.
remote:        In rare occasions Bundler may not be able to re                                                                                       solve your dependencies at all.
remote:        https://devcenter.heroku.com/articles/bundler-w                                                                                       indows-gemfile
remote:
remote: ###### WARNING:
remote:
remote:        You set your `config.active_storage.service` to                                                                                        :local in production.
remote:        If you are uploading files to this app, they wi                                                                                       ll not persist after the app
remote:        is restarted, on one-off dynos, or if the app h                                                                                       as multiple dynos.
remote:        Heroku applications have an ephemeral file syst                                                                                       em. To
remote:        persist uploaded files, please use a service su                                                                                       ch as S3 and update your Rails
remote:        configuration.
remote:
remote:        For more information can be found in this artic                                                                                       le:
remote:          https://devcenter.heroku.com/articles/active-                                                                                       storage-on-heroku
remote:
remote:
remote: ###### WARNING:
remote:
remote:        We detected that some binary dependencies requi                                                                                       red to
remote:        use all the preview features of Active Storage                                                                                        are not
remote:        present on this system.
remote:
remote:        For more information please see:
remote:          https://devcenter.heroku.com/articles/active-                                                                                       storage-on-heroku
remote:
remote:
remote:
remote: -----> Discovering process types
remote:        Procfile declares types     -> web
remote:        Default types for buildpack -> console, rake, w                                                                                       orker
remote:
remote: -----> Compressing...
remote:        Done: 50.5M
remote: -----> Launching...
remote:        Released v7
remote:        https://appsmipymes.herokuapp.com/ deployed to                                                                                        Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/appsmipymes.git
   7e3a09e..5dcbc26  master -> master
