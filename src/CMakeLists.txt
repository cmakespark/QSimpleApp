set(SOURCES
    main.cpp
)

set(HEADERS
)

createapp(NAME QSimpleApp
    VERSION 2.0.0
    CONSOLE
    SOURCES ${SOURCES}
    HEADERS ${HEADERS}
    DEPS CC2::SimpleLib Qt${QT_MAJOR_VERSION_REQUIRED}::Core)
