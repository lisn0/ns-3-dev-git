set(name uan-cw-example)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libinternet} ${libmobility} ${libstats}
                      ${libapplications} ${libuan}
)
build_lib_example(
  "${name}" "${source_files}" "${header_files}" "${libraries_to_link}"
)

set(name uan-rc-example)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libinternet} ${libmobility} ${libstats}
                      ${libapplications} ${libuan}
)
build_lib_example(
  "${name}" "${source_files}" "${header_files}" "${libraries_to_link}"
)

set(name uan-6lowpan-example)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libinternet} ${libmobility} ${libstats}
                      ${libapplications} ${libuan} ${libsixlowpan}
)
build_lib_example(
  "${name}" "${source_files}" "${header_files}" "${libraries_to_link}"
)

set(name uan-ipv4-example)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libinternet} ${libmobility} ${libstats}
                      ${libapplications} ${libuan}
)
build_lib_example(
  "${name}" "${source_files}" "${header_files}" "${libraries_to_link}"
)

set(name uan-raw-example)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libinternet} ${libmobility} ${libstats}
                      ${libapplications} ${libuan}
)
build_lib_example(
  "${name}" "${source_files}" "${header_files}" "${libraries_to_link}"
)
