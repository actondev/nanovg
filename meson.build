project('nanovg', 'c')

inc = include_directories('src')

src = files(
  'src/nanovg.c',
  )

nanovg = library('nanovg',
                  src,
                  include_directories: inc
                )

nanovg_dep = declare_dependency(
  include_directories : inc,
  link_with : nanovg)
