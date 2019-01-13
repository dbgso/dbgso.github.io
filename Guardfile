require 'asciidoctor'

guard 'shell' do
  watch(/^docs\/.*\.adoc$/) {|m|
    `asciidoctor --backend html5 -a data-uri docs/index.adoc`
  }
end
  
# guard 'livereload' do
#     watch(/.*\.html$/) {|m|}
# end