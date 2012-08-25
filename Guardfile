guard 'livereload' do
  watch(%r{public/.+\.(html)})
  watch(%r{public/css/.+\.(css)})
  watch(%r{public/js/.+\.(js)})
  watch(%r{public/img/.+.(png|jpg|gif)})
end

guard 'sass', input: 'scss', output: 'public/css', style: :compressed

guard 'coffeescript', input: 'coffee', output: 'public/js'
