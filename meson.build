project('Tangram',
  version: '1.3.1',
  meson_version: '>= 0.50.0',
)

app_id = 're.sonny.Tangram'

conf = configuration_data()
conf.set('BINDIR', join_paths([ get_option('prefix'), 'bin' ]))

i18n = import('i18n')

subdir('data')
subdir('src')
subdir('po')

meson.add_install_script('build-aux/meson/postinstall.py')
