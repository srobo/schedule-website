task :clean do
  sh('rm -rf _site')
end

task :dependencies do
  sh('bundle install --path gems')
end

task :dev => [:dependencies] do
  sh('bundle exec jekyll serve --drafts --config _config.yml')
end
