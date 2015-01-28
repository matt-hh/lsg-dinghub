namespace :lsg do
  task :compile do
    system 'bundle exec livingstyleguide compile app/assets/stylesheets/styleguide.lsg public/styleguide.html'
  end
end

task :default => "lsg:compile"
