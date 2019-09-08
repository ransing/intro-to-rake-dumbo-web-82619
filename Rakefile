namespace :greeting do
   task :environment do
  require_relative './config/environment'
end
  # 
  desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

  desc 'outputs hola to the terminal'
task :hola do
  puts "hola de Rake!"
end




namespace :db do
  desc 'migrate changes to your database'
  task :environment do
  require_relative './config/environment'
end
  task :migrate => :environment do
    Student.create_table
  end
end