add_library(LMDB
  mdb.c
  midl.c)
target_include_directories(LMDB PUBLIC
  include)

set_property(GLOBAL APPEND PROPERTY LMDB_EXPORTS LMDB)
