
cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "src/TinyGPS++.cpp"
                       INCLUDE_DIRS "src" 
                       REQUIRES arduino)

