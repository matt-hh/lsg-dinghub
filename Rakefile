namespace :lsg do
  task :compile do
    bundle_cmd = 'bundle exec'
    lsg_cmd = 'livingstyleguide compile'
    args = 'stylesheets/styleguide.lsg styleguide.html'
    run "#{bundle_cmd} #{lsg_cmd} #{args}"
  end

  task :publish do
    Rake::Task['lsg:compile'].invoke
    run 'git co gh-pages'
    run 'mv styleguide.html index.html'
    run 'git add index.html'
    run 'git add fonts'
    run "git ci -am 'Update styleguide (#{`date`})'"
    run 'git push origin gh-pages'
    run 'git co master'
  end

  def run(cmd)
    # puts cmd
    system cmd
  end
end

task :default => "lsg:compile"
