aekasarn_sources = [
  'main.c',
  'aekasarn-application.c',
  'aekasarn-window.c',
]

aekasarn_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.4'),
]

aekasarn_sources += gnome.compile_resources('aekasarn-resources',
  'aekasarn.gresource.xml',
  c_name: 'aekasarn'
)

executable('aekasarn', aekasarn_sources,
  dependencies: aekasarn_deps,
       install: true,
)
