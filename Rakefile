task :default => :bin

desc "Ejecurtar el fichero /lib/Fracciones.rb"
task :bin do
	sh "ruby lib/Fracciones.rb"
end

desc "Test con documentacion"
task :test do
  sh "rspec -I. spec/Fracciones_spec.rb --format documentation"
end

desc "Test con documentacion en HTML"
task :thtml do
  sh "rspec -I. spec/Fracciones_spec.rb --format html"
end