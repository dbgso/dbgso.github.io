require 'asciidoctor'

guard 'shell' do
  watch(/^docs\/.*\.adoc$/) {|m|
    Asciidoctor.convert_file m[0]
  }
end
