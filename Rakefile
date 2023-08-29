desc 'host the site locally'
task :host do
  sh "budo -d docs"
end

desc 'build style.json'
task :build do
  sh <<-EOS
charites build --provider maplibre --compact-output style.yml \
../parquet-1/14321/style.json
  EOS
end

