cmake_minimum_required(VERSION 3.22)
project(_ee205_lab_08d_animal_farm_1_to_clion)

set(CMAKE_CXX_STANDARD 14)

add_executable(_ee205_lab_08d_animal_farm_1_to_clion main.cpp catDatabase.h config.h addCats.cpp addCats.h catDatabase.cpp deleteCats.cpp deleteCats.h reportCats.cpp reportCats.h updateCats.cpp updateCats.h)
