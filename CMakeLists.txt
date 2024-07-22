# Версия CMake, ниже которой он не сможет работать
cmake_minimum_required(VERSION 3.27 FATAL_ERROR) 

# Название проекта (будет использовано в .sln MSVS)
project(BattleCity)

# Добавление исполняемых файлов(Имя исп. файла + путь к исходникам) 
add_executable(BattleCity src/main.cpp)