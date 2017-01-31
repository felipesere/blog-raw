task :add, [:tags, :categories] do |t, args|
  time = Time.new.strftime("%Y-%m-%d %H:%M:%S")
  date = Time.new.strftime("%Y-%m-%d")
  STDOUT.puts("Title: ")
  title = STDIN.gets.chomp
  file_name = title.downcase.gsub(/ /,'-')
  template =   <<eos
---
title: #{title}
date: #{time}
categories: []
tags: []
published: false
---

Some text...
eos
  open("_posts/#{date}-#{file_name}.markdown", 'w') do |file|
    file.puts template
  end
end

task :preview do
  sh "bundle exec jekyll serve -w --unpublished"
end

task :build do
  sh "bundle exec jekyll build --incremental -d live"
end
