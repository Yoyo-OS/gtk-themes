cmake_minimum_required(VERSION 3.5)
project(gtk-theme)
install(DIRECTORY Yoyo DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Yoyo-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Yoyo-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
