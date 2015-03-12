

less_options = {
  all_on_start: true,
  all_after_change: true,
  output: 'css',
  patterns: [/^less\/app.less$/]
}

guard :less, less_options do
  (less_options[:patterns] + [%r{.+\.less$}]).each { |pattern| watch(pattern) }
end


guard 'livereload' do
  watch(%r{.+\..*$})
end