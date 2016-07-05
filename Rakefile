task :default => [:clean, :zip]

task :clean do |t|
  sh "rm -rf ./readable_marxists.zip"
end

task :zip do |t|
  sh "zip -r readable_marxists.zip ./* -x .git Rakefile README.md"
end
