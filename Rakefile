begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name     'alfred-chrome-bookmark'
  authors  'Soloman Weng'
  email    'soloman1124@gmail.com'
}
