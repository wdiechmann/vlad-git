require "rubygems"
require "hoe"

Hoe.plugin :doofus, :git

Hoe.spec "vlad-git" do
  developer "John Barnette", "jbarnette@rubyforge.org"
  developer "Aaron Suggs", "aaron@ktheory.com"

  self.extra_rdoc_files = FileList["*.rdoc"]
  self.history_file     = "CHANGELOG.rdoc"
  self.readme_file      = "README.rdoc"
  self.rubyforge_name   = "hitsquad"
  self.testlib          = :minitest
  self.extra_deps       << ["vlad", ">= 2.1.0"]
end
