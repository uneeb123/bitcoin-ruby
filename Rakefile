begin
  require 'bundler/gem_tasks'
rescue LoadError
end

desc 'Generate RDoc documentation'
task :rdoc do
  `rm -rf rdoc`
  system("rdoc -a -A -H -t 'bitcoin-ruby RDoc' -W 'https://github.com/mhanne/bitcoin-ruby/tree/master/%s' -o rdoc -m README.rdoc examples/ doc/ lib/ README.rdoc COPYING")
end
