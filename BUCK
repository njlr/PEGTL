include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'pegtl',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 'pegtl.hh'),
    ('', 'pegtl/**/*.hh'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
