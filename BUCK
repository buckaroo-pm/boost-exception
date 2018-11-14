cxx_library(
  name = 'exception',
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config',     
  ], 
  visibility = [
    'PUBLIC',
  ],
)
