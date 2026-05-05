set(COMPONENT_ADD_INCLUDEDIRS
    "include")

idf_component_register(
    SRCS "./src/PCF85063A.c" "./src/timegm.c"
    INCLUDE_DIRS "include"
)