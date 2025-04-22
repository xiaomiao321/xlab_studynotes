cmake_minimum_required(VERSION 3.10) # 最小支持版本

project(print) # 项目名称

add_executable(print main.c print.c print1.c) # 添加可执行文件，将main.c作为入口文件