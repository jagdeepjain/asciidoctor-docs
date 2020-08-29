namespace :doc do
  desc 'build doc'
  task :build, [:name] do |t, args|
    puts args[:name]
    puts "Converting document to HTML..."
    `bundle exec asciidoctor -a stylesheet=asciidoctor.css #{args[:name]}.adoc`
    puts " -- check the equivalent HTML"
  end
end
