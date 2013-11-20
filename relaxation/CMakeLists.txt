include_geo_sim_sdk()
link_geo_sim_sdk()

file(GLOB header *.h)
file(GLOB source *.cpp)
add_library(remesh-relaxation SHARED ${header} ${source})