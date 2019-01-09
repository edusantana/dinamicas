desc "compila código html5"
task :build do
  sh %(asciidoctor dinamicas.adoc -o docs/dinamicas.html && xdg-open docs/dinamicas.html)
  sh %(asciidoctor dinamicas-completas.adoc -o docs/dinamicas-completas.html && xdg-open docs/dinamicas-completas.html)
end

task :default => :build
