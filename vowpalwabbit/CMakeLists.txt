add_subdirectory(active_interactor)
add_subdirectory(allreduce)
if(VW_BUILD_VW_C_WRAPPER)
  add_subdirectory(c_wrapper)
endif()
add_subdirectory(cli)
add_subdirectory(common)
add_subdirectory(config)
add_subdirectory(core)
add_subdirectory(explore)
add_subdirectory(io)
add_subdirectory(slim)
add_subdirectory(spanning_tree_bin)
add_subdirectory(spanning_tree)
if(BUILD_FLATBUFFERS)
  add_subdirectory(fb_parser)
endif()
