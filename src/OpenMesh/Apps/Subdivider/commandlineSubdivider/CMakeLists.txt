include (VCICommon)

include_directories (
  ../../../..
  ${CMAKE_CURRENT_SOURCE_DIR}
)

vci_add_executable (commandlineSubdivider ../subdivider.cc)

target_link_libraries (commandlineSubdivider
  OpenMeshCore
  OpenMeshTools
)

