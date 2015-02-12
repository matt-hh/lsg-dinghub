namespace :lsg do
  task :compile do
    system 'bundle exec livingstyleguide compile app/assets/stylesheets/styleguide.lsg styleguide.html'
  end

  task :publish do
    Rake::Task['lsg:compile'].invoke
    system 'git co gh-pages'
    system 'mv styleguide.html index.html'
    system 'git add index.html'
    system "git ci -am 'Update styleguide (#{`date`})'"
    system 'git push origin gh-pages'
    system 'git co master'
  end
end

task :default => "lsg:compile"
