guard 'livereload' do
  watch(%r{public/.+\.(html)})
  watch(%r{public/css/.+\.(css)})
  watch(%r{public/js/.+\.(js)})
  watch(%r{public/img/.+.(png|jpg|gif)})
end

guard 'sass', input: '_scss', output: 'css', style: :compressed

guard 'coffeescript', input: '_coffee', output: 'js'

guard 'jekyll' do
  watch /.*/
end
