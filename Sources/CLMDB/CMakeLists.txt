add_library(CLMDB STATIC
  mdb.c
  midl.c)
target_include_directories(CLMDB PUBLIC
  include)

set_property(GLOBAL APPEND PROPERTY LMDB_EXPORTS CLMDB)
