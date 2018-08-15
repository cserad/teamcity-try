set(SOURCES
        main.cpp
        gameobject.cpp
        ship.cpp
        bullet.cpp
        game.cpp
        asteroid.cpp
)

set(INCLUDE_DIRS
    ${CMAKE_CURRENT_SOURCE_DIR}
    ${SFML_INCLUDE_DIR}
)

add_executable(asteroid ${SOURCES})

target_link_libraries(asteroid sfml-graphics sfml-system)
