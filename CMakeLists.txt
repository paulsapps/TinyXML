set(TinyXml_FILES
tinystr.cpp
tinystr.h
tinyxml.cpp
tinyxml.h
tinyxmlerror.cpp
tinyxmlparser.cpp
)

add_library(TinyXml STATIC ${TinyXml_FILES})
