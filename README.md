# テクノロジー（藤原）11/15授業

## Rails: 実行ログ

```
     create  vendor
      create  vendor/.keep
      create  package.json
      remove  config/initializers/cors.rb
      remove  config/initializers/new_framework_defaults_5_1.rb
         run  bundle install
The latest bundler is 1.16.0, but you are currently running 1.15.4.
To update, run `gem install bundler`
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Fetching gem metadata from https://rubygems.org/.........
Fetching version metadata from https://rubygems.org/..
Fetching dependency metadata from https://rubygems.org/.
Resolving dependencies...
Using rake 12.2.1
Using concurrent-ruby 1.0.5
Using minitest 5.10.3
Using thread_safe 0.3.6
Using builder 3.2.3
Using erubi 1.7.0
Using mini_portile2 2.3.0
Using crass 1.0.3
Using rack 2.0.3
Using nio4r 2.1.0
Using websocket-extensions 0.1.3
Using mini_mime 1.0.0
Using arel 8.0.0
Using public_suffix 3.0.1
Using bindex 0.5.0
Using bundler 1.15.4
Using byebug 9.1.0
Using ffi 1.9.18
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using method_source 0.9.0
Using thor 0.20.0
Using multi_json 1.12.2
Using rb-fsevent 0.10.2
Using ruby_dep 1.5.0
Using puma 3.10.0
Using rubyzip 1.2.1
Using tilt 2.0.8
Using sqlite3 1.3.13
Using turbolinks-source 5.0.3
Using i18n 0.9.1
Using tzinfo 1.2.4
Using nokogiri 1.8.1
Using rack-test 0.7.0
Using sprockets 3.7.1
Using websocket-driver 0.6.5
Using mail 2.7.0
Using addressable 2.5.2
Using childprocess 0.8.0
Using rb-inotify 0.9.10
Using coffee-script 2.4.1
Using uglifier 3.2.0
Using turbolinks 5.0.1
Using activesupport 5.1.4
Using loofah 2.1.1
Using xpath 2.1.0
Using selenium-webdriver 3.7.0
Using listen 3.1.5
Using sass-listen 4.0.0
Using rails-dom-testing 2.0.3
Using globalid 0.4.1
Using activemodel 5.1.4
Using jbuilder 2.7.0
Using spring 2.0.2
Using rails-html-sanitizer 1.0.3
Using capybara 2.16.0
Using sass 3.5.3
Using activejob 5.1.4
Using activerecord 5.1.4
Using spring-watcher-listen 2.0.1
Using actionview 5.1.4
Using actionpack 5.1.4
Using actioncable 5.1.4
Using actionmailer 5.1.4
Using railties 5.1.4
Using sprockets-rails 3.2.1
Using coffee-rails 4.2.2
Using web-console 3.5.1
Fetching rails 5.1.4
Installing rails 5.1.4
Using sass-rails 5.0.7
Bundle complete! 16 Gemfile dependencies, 70 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
         run  bundle exec spring binstub --all
* bin/rake: spring inserted
* bin/rails: spring inserted
sight315:~/workspace/lecture-1115 (master) $ ls
README.md  asagao/
sight315:~/workspace/lecture-1115 (master) $ cd asagao/
sight315:~/workspace/lecture-1115/asagao (master) $ bundle install
The latest bundler is 1.16.0, but you are currently running 1.15.4.
To update, run `gem install bundler`
Using rake 12.2.1
Using concurrent-ruby 1.0.5
Using minitest 5.10.3
Using thread_safe 0.3.6
Using builder 3.2.3
Using erubi 1.7.0
Using mini_portile2 2.3.0
Using crass 1.0.3
Using rack 2.0.3
Using nio4r 2.1.0
Using websocket-extensions 0.1.3
Using mini_mime 1.0.0
Using arel 8.0.0
Using public_suffix 3.0.1
Using bindex 0.5.0
Using bundler 1.15.4
Using byebug 9.1.0
Using ffi 1.9.18
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using method_source 0.9.0
Using thor 0.20.0
Using multi_json 1.12.2
Using rb-fsevent 0.10.2
Using ruby_dep 1.5.0
Using puma 3.10.0
Using rubyzip 1.2.1
Using tilt 2.0.8
Using sqlite3 1.3.13
Using turbolinks-source 5.0.3
Using i18n 0.9.1
Using tzinfo 1.2.4
Using nokogiri 1.8.1
Using rack-test 0.7.0
Using sprockets 3.7.1
Using websocket-driver 0.6.5
Using mail 2.7.0
Using addressable 2.5.2
Using childprocess 0.8.0
Using rb-inotify 0.9.10
Using coffee-script 2.4.1
Using uglifier 3.2.0
Using turbolinks 5.0.1
Using activesupport 5.1.4
Using loofah 2.1.1
Using xpath 2.1.0
Using selenium-webdriver 3.7.0
Using listen 3.1.5
Using sass-listen 4.0.0
Using rails-dom-testing 2.0.3
Using globalid 0.4.1
Using activemodel 5.1.4
Using jbuilder 2.7.0
Using spring 2.0.2
Using rails-html-sanitizer 1.0.3
Using capybara 2.16.0
Using sass 3.5.3
Using activejob 5.1.4
Using activerecord 5.1.4
Using spring-watcher-listen 2.0.1
Using actionview 5.1.4
Using actionpack 5.1.4
Using actioncable 5.1.4
Using actionmailer 5.1.4
Using railties 5.1.4
Using sprockets-rails 3.2.1
Using coffee-rails 4.2.2
Using web-console 3.5.1
Using rails 5.1.4
Using sass-rails 5.0.7
Bundle complete! 16 Gemfile dependencies, 70 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
sight315:~/workspace/lecture-1115/asagao (master) $ ls
Gemfile       README.md  app/  config/    db/   log/          public/  tmp/
Gemfile.lock  Rakefile   bin/  config.ru  lib/  package.json  test/    vendor/
sight315:~/workspace/lecture-1115/asagao (master) $ bin/rails -b $IP -p $PORT
rails aborted!
OptionParser::AmbiguousOption: ambiguous option: -b
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands/rake/rake_command.rb:19:in `block in perform'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands/rake/rake_command.rb:18:in `perform'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/command.rb:46:in `invoke'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands.rb:16:in `<top (required)>'
/home/ubuntu/workspace/lecture-1115/asagao/bin/rails:9:in `require'
/home/ubuntu/workspace/lecture-1115/asagao/bin/rails:9:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/rails.rb:28:in `load'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/rails.rb:28:in `call'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/command.rb:7:in `call'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client.rb:30:in `run'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/bin/spring:49:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/binstub.rb:31:in `load'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/binstub.rb:31:in `<top (required)>'
/home/ubuntu/workspace/lecture-1115/asagao/bin/spring:15:in `<top (required)>'
bin/rails:3:in `load'
bin/rails:3:in `<main>'

Caused by:
OptionParser::InvalidOption: invalid option: b
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands/rake/rake_command.rb:19:in `block in perform'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands/rake/rake_command.rb:18:in `perform'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/command.rb:46:in `invoke'
/usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/commands.rb:16:in `<top (required)>'
/home/ubuntu/workspace/lecture-1115/asagao/bin/rails:9:in `require'
/home/ubuntu/workspace/lecture-1115/asagao/bin/rails:9:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/rails.rb:28:in `load'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/rails.rb:28:in `call'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client/command.rb:7:in `call'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/client.rb:30:in `run'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/bin/spring:49:in `<top (required)>'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/binstub.rb:31:in `load'
/usr/local/rvm/gems/ruby-2.4.0/gems/spring-2.0.2/lib/spring/binstub.rb:31:in `<top (required)>'
/home/ubuntu/workspace/lecture-1115/asagao/bin/spring:15:in `<top (required)>'
bin/rails:3:in `load'
bin/rails:3:in `<main>'
(See full trace by running task with --trace)
sight315:~/workspace/lecture-1115/asagao (master) $ bin/rails s -b $IP -p $PORT                                             
=> Booting Puma
=> Rails 5.1.4 application starting in development 
=> Run `rails server -h` for more startup options
Puma starting in single mode...
* Version 3.10.0 (ruby 2.4.0-p0), codename: Russell's Teapot
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://0.0.0.0:8080
Use Ctrl-C to stop
Started GET "/" for 125.204.151.95 at 2017-11-15 01:12:30 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by Rails::WelcomeController#index as HTML
  Rendering /usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/templates/rails/welcome/index.html.erb
  Rendered /usr/local/rvm/gems/ruby-2.4.0@global/gems/railties-5.1.4/lib/rails/templates/rails/welcome/index.html.erb (2.7ms)
Completed 200 OK in 213ms (Views: 7.6ms)


^C- Gracefully stopping, waiting for requests to finish
=== puma shutdown: 2017-11-15 01:12:50 +0000 ===
- Goodbye!
Exiting
sight315:~/workspace/lecture-1115/asagao (master) $ touch config/initializers/generators.rb
sight315:~/workspace/lecture-1115/asagao (master) $ c9 config/initializers/generators.rb                                   
sight315:~/workspace/lecture-1115/asagao (master) $ bin/rails g controller top index
Running via Spring preloader in process 15671
      create  app/controllers/top_controller.rb
       route  get 'top/index'
      invoke  erb
      create    app/views/top
      create    app/views/top/index.html.erb
      invoke  test_unit
      create    test/controllers/top_controller_test.rb
      invoke  helper
      create    app/helpers/top_helper.rb
      invoke    test_unit
      invoke  assets
      invoke    coffee
      create      app/assets/javascripts/top.coffee
      invoke    scss
      create      app/assets/stylesheets/top.scss
sight315:~/workspace/lecture-1115/asagao (master) $ bin/rails s -b $IP -p $PORT
=> Booting Puma
=> Rails 5.1.4 application starting in development 
=> Run `rails server -h` for more startup options
Puma starting in single mode...
* Version 3.10.0 (ruby 2.4.0-p0), codename: Russell's Teapot
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://0.0.0.0:8080
Use Ctrl-C to stop
Started GET "/" for 125.204.151.95 at 2017-11-15 02:15:42 +0000
Cannot render console from 125.204.151.95! Allowed networks: 127.0.0.1, ::1, 127.0.0.0/127.255.255.255
Processing by TopController#index as HTML
  Rendering top/index.html.erb within layouts/application
  Rendered top/index.html.erb within layouts/application (1.5ms)
Completed 200 OK in 919ms (Views: 654.4ms)


$ cd ~/workspace/lecture-1115
^[
^C- Gracefully stopping, waiting for requests to finish
=== puma shutdown: 2017-11-15 02:53:57 +0000 ===
- Goodbye!
Exiting
sight315:~/workspace/lecture-1115/asagao (master) $ $ cd ~/workspace/lecture-1115
bash: $: command not found
sight315:~/workspace/lecture-1115/asagao (master) $ cd ~/workspace/lecture-1115
sight315:~/workspace/lecture-1115 (master) $ git add *
sight315:~/workspace/lecture-1115 (master) $ git commit -m '11/15 Rails授業'
[master 2365812] 11/15 Rails授業
 83 files changed, 1220 insertions(+)
 create mode 100644 asagao/.gitignore
 create mode 100644 asagao/Gemfile
 create mode 100644 asagao/Gemfile.lock
 create mode 100644 asagao/README.md
 create mode 100644 asagao/Rakefile
 create mode 100644 asagao/app/assets/config/manifest.js
 create mode 100644 asagao/app/assets/images/.keep
 create mode 100644 asagao/app/assets/javascripts/application.js
 create mode 100644 asagao/app/assets/javascripts/cable.js
 create mode 100644 asagao/app/assets/javascripts/channels/.keep
 create mode 100644 asagao/app/assets/javascripts/top.coffee
 create mode 100644 asagao/app/assets/stylesheets/application.css
 create mode 100644 asagao/app/assets/stylesheets/top.scss
 create mode 100644 asagao/app/channels/application_cable/channel.rb
 create mode 100644 asagao/app/channels/application_cable/connection.rb
 create mode 100644 asagao/app/controllers/application_controller.rb
 create mode 100644 asagao/app/controllers/concerns/.keep
 create mode 100644 asagao/app/controllers/top_controller.rb
 create mode 100644 asagao/app/helpers/application_helper.rb
 create mode 100644 asagao/app/helpers/top_helper.rb
 create mode 100644 asagao/app/jobs/application_job.rb
 create mode 100644 asagao/app/mailers/application_mailer.rb
 create mode 100644 asagao/app/models/application_record.rb
 create mode 100644 asagao/app/models/concerns/.keep
 create mode 100644 asagao/app/views/layouts/application.html.erb
 create mode 100644 asagao/app/views/layouts/mailer.html.erb
 create mode 100644 asagao/app/views/layouts/mailer.text.erb
 create mode 100644 asagao/app/views/top/index.html.erb
 create mode 100755 asagao/bin/bundle
 create mode 100755 asagao/bin/rails
 create mode 100755 asagao/bin/rake
 create mode 100755 asagao/bin/setup
 create mode 100755 asagao/bin/spring
 create mode 100755 asagao/bin/update
 create mode 100755 asagao/bin/yarn
 create mode 100644 asagao/config.ru
 create mode 100644 asagao/config/application.rb
 create mode 100644 asagao/config/boot.rb
 create mode 100644 asagao/config/cable.yml
 create mode 100644 asagao/config/database.yml
 create mode 100644 asagao/config/environment.rb
 create mode 100644 asagao/config/environments/development.rb
 create mode 100644 asagao/config/environments/production.rb
 create mode 100644 asagao/config/environments/test.rb
 create mode 100644 asagao/config/initializers/application_controller_renderer.rb
 create mode 100644 asagao/config/initializers/assets.rb
 create mode 100644 asagao/config/initializers/backtrace_silencers.rb
 create mode 100644 asagao/config/initializers/cookies_serializer.rb
 create mode 100644 asagao/config/initializers/filter_parameter_logging.rb
 create mode 100644 asagao/config/initializers/generators.rb
 create mode 100644 asagao/config/initializers/inflections.rb
 create mode 100644 asagao/config/initializers/mime_types.rb
 create mode 100644 asagao/config/initializers/wrap_parameters.rb
 create mode 100644 asagao/config/locales/en.yml
 create mode 100644 asagao/config/puma.rb
 create mode 100644 asagao/config/routes.rb
 create mode 100644 asagao/config/secrets.yml
 create mode 100644 asagao/config/spring.rb
 create mode 100644 asagao/db/seeds.rb
 create mode 100644 asagao/lib/assets/.keep
 create mode 100644 asagao/lib/tasks/.keep
 create mode 100644 asagao/log/.keep
 create mode 100644 asagao/package.json
 create mode 100644 asagao/public/404.html
 create mode 100644 asagao/public/422.html
 create mode 100644 asagao/public/500.html
 create mode 100644 asagao/public/apple-touch-icon-precomposed.png
 create mode 100644 asagao/public/apple-touch-icon.png
 create mode 100644 asagao/public/favicon.ico
 create mode 100644 asagao/public/robots.txt
 create mode 100644 asagao/test/application_system_test_case.rb
 create mode 100644 asagao/test/controllers/.keep
 create mode 100644 asagao/test/controllers/top_controller_test.rb
 create mode 100644 asagao/test/fixtures/.keep
 create mode 100644 asagao/test/fixtures/files/.keep
 create mode 100644 asagao/test/helpers/.keep
 create mode 100644 asagao/test/integration/.keep
 create mode 100644 asagao/test/mailers/.keep
 create mode 100644 asagao/test/models/.keep
 create mode 100644 asagao/test/system/.keep
 create mode 100644 asagao/test/test_helper.rb
 create mode 100644 asagao/tmp/.keep
 create mode 100644 asagao/vendor/.keep
sight315:~/workspace/lecture-1115 (master) $ git push
Username for 'https://github.com': ^C
sight315:~/workspace/lecture-1115 (master) $ git remote -v
origin  http://github.com/kd-tech-fj2017/lecture-1115.git (fetch)
origin  http://github.com/kd-tech-fj2017/lecture-1115.git (push)
sight315:~/workspace/lecture-1115 (master) $ git remote remove origin
sight315:~/workspace/lecture-1115 (master) $ git remote add origin git@github.com:sight-315/lecture-1115.git
sight315:~/workspace/lecture-1115 (master) $ git push
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Counting objects: 93, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (80/80), done.
Writing objects: 100% (93/93), 21.62 KiB | 2.40 MiB/s, done.
Total 93 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To github.com:sight-315/lecture-1115.git
   98d4f91..2365812  master -> master
sight315:~/workspace/lecture-1115 (master) $ git pull
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

sight315:~/workspace/lecture-1115 (master) $ git pull origin master -u
error: unknown switch `u'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --recurse-submodules[=<on-demand>]
                          control for recursive fetching of submodules

Options related to merging
    -r, --rebase[=<false|true|preserve|interactive>]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after rebase
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap

sight315:~/workspace/lecture-1115 (master) $ git pull -u origin master                                                      
error: unknown switch `u'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --recurse-submodules[=<on-demand>]
                          control for recursive fetching of submodules

Options related to merging
    -r, --rebase[=<false|true|preserve|interactive>]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after rebase
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap

sight315:~/workspace/lecture-1115 (master) $ git pull origin master 
Warning: Permanently added 'github.com,192.30.255.113' (RSA) to the list of known hosts.
From github.com:sight-315/lecture-1115
 * branch            master     -> FETCH_HEAD
Already up-to-date.
sight315:~/workspace/lecture-1115 (master) $ git pull -u origin master
error: unknown switch `u'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --recurse-submodules[=<on-demand>]
                          control for recursive fetching of submodules

Options related to merging
    -r, --rebase[=<false|true|preserve|interactive>]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after rebase
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap

sight315:~/workspace/lecture-1115 (master) $ git push -u origin master                                                      
Warning: Permanently added 'github.com,192.30.255.112' (RSA) to the list of known hosts.
Branch master set up to track remote branch master from origin.
Everything up-to-date
sight315:~/workspace/lecture-1115 (master) $ 
```
