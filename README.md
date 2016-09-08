== README

## 初始化项目

    # 创建项目
    $ rails new capstrano_demo -B -T
    # 创建 migrate 内容
    $ rails g migration post title content:text

    # 添加 capistrano 相关 gem 到Gemfile
    gem 'capistrano'
    gem 'capistrano-rails'
    gem 'capistrano-rvm'

    $ bundle install

