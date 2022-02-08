# README

This README documents steps necessary to get the application up and running.

* asdf: 
ASDF allows you to install binaries the way you like. You should never need to 'sudo'. Install asdf from https://github.com/asdf-vm/asdf. Use homebrew and make sure you add
```
echo -e "\n. $(brew --prefix asdf)/libexec/asdf.sh" >> ${ZDOTDIR:-~}/.zshrc
```
to your .zshrc

```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ asdf
version: v0.9.0
```

* Shell used zshrc
   

* Ruby version
```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ ruby -v
ruby 2.7.0p0 (2019-12-25 revision 647ee6f091) [x86_64-darwin20]
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ which ruby
/Users/ankurv/.asdf/shims/ruby
```

* Node

```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ node -v
v16.13.2

➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ which node
/Users/ankurv/.asdf/shims/node
```

* Rails
```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ rails -v
Rails 7.0.1
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ which rails
/Users/ankurv/.asdf/shims/rails
```

* Sqlite 3
```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ sqlite3   
SQLite version 3.32.3 2020-06-18 14:16:19
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite> 
[1]  + 92142 suspended  sqlite3

➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ which sqlite3
/usr/bin/sqlite3

```

* Yarn
```
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ yarn -v
1.22.10
➜  ~/Documents/work/ruby-on-rails/blog git:(main) ✗ which yarn
/Users/ankurv/.asdf/shims/yarn
```





