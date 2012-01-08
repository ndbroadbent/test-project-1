require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

  ENV.keys.sort.each do |key|
    puts "#{key}: #{ENV[key]}"
  end

<<<<<<< HEAD
  1.upto(1) do
    sleep(0.01)
    putc '.'
    $stdout.flush
  end
  status = File.read("status").strip.to_i rescue 0
  exit status
=======
  sleep(0.01)
  putc '.'
  $stdout.flush

  exit 1 
>>>>>>> a100e9efef9dec1cb883b8ecfaf32befd239a6b8
end

task :default => :test

