cxx_library(
  name = 'cds',
  header_namespace = 'cds',
  exported_headers = subdir_glob([
    ('cds', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
)
