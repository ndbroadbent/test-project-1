require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

  ENV.keys.sort.each do |key|
    puts "#{key}: #{ENV[key]}"
  end

  sleep(0.01)
  putc '.'
  $stdout.flush

  exit 0 
end

task :default => :test
