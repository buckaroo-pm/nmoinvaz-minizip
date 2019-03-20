cxx_library(
  name = 'minizip',
  exported_headers = glob(['*.h']),
  srcs = glob(['*.c'], exclude=['iowin32.c']),
  platform_srcs = [
    ('win32.*', ['iowin32.c'])
  ],
  visibility = ['PUBLIC']
)
