set(simulatorapi_source_files
  simapi/simapi/simmapper.c
  simapi/simapi/simmapper.h
  simapi/simapi/simdata.h
  simapi/simapi/test.h
  simapi/include/acdata.h
  simapi/include/rf2data.h
  simapi/include/pcars2data.h
  simapi/include/scs2data.h
  simapi/simmap/basicmap.h
  simapi/simmap/mapacdata.c
  simapi/simmap/mapacdata.h
  simapi/simapi/ac.h
  simapi/simapi/rf2.h
  simapi/simapi/pcars2.h
  simapi/simapi/scs2.h
)

add_library(simulatorapi STATIC ${simulatorapi_source_files})
