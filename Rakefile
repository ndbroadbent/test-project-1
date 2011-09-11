require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

  ENV.keys.sort.each do |key|
    puts "#{key}: #{ENV[key]}"
  end

  1.upto(1) do
    sleep(0.01)
    putc '.'
    $stdout.flush
  end
  status = File.read("status").strip.to_i rescue 0
  exit status
end

task :default => :test

