require 'jekyll-import'

task :import, :source
task :import do |t, args|
  importer = JekyllImport::Importers::WordpressDotCom
  "Source #{args[:source]} not found" if File.exist? args[:source]
end

task :replace_image_path do
  files = FileList.new('.')
  puts files
end
