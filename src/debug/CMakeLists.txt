add_subdirectory(daccess)
add_subdirectory(dbgutil)
add_subdirectory(ildbsymlib)
add_subdirectory(ee)
if(WIN32)
    add_subdirectory(di)
    add_subdirectory(shim)
endif(WIN32)
