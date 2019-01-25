cxx_library(
  name = 'minizip',
  exported_headers = glob(['*.h', 'aes/*.h']),
  srcs = glob(['*.c', 'aes/*.c'], exclude=['iowin32.c']),
  platform_srcs = [
    ('win32.*', ['iowin32.c'])
  ],
  visibility = ['PUBLIC']
)
