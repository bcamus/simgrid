set(bin_files ${bin_files}    ${CMAKE_CURRENT_SOURCE_DIR}/fix-paje-trace.sh
                              ${CMAKE_CURRENT_SOURCE_DIR}/generate-dwarf-functions
                              ${CMAKE_CURRENT_SOURCE_DIR}/normalize-pointers.py
                              ${CMAKE_CURRENT_SOURCE_DIR}/sg_unit_extractor.pl
                              ${CMAKE_CURRENT_SOURCE_DIR}/sg_xml_unit_converter.py
                              ${CMAKE_CURRENT_SOURCE_DIR}/simgrid_update_xml.pl
                              ${CMAKE_CURRENT_SOURCE_DIR}/simgrid_convert_TI_traces.py
                              ${CMAKE_CURRENT_SOURCE_DIR}/doxygen/fig2dev_postprocessor.pl
                              ${CMAKE_CURRENT_SOURCE_DIR}/doxygen/xbt_log_extract_hierarchy.pl
                              ${CMAKE_CURRENT_SOURCE_DIR}/MSG_visualization/colorize.pl
                              ${CMAKE_CURRENT_SOURCE_DIR}/MSG_visualization/trace2fig.pl          PARENT_SCOPE)

set(txt_files ${txt_files}    ${CMAKE_CURRENT_SOURCE_DIR}/pkg-config/simgrid.pc.in
                              ${CMAKE_CURRENT_SOURCE_DIR}/simgrid.supp
                              ${CMAKE_CURRENT_SOURCE_DIR}/simgrid2vite.sed                        PARENT_SCOPE)
