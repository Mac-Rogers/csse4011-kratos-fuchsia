cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(project/mobile)
target_sources(app PRIVATE src/main.c src/bluetooth.c src/bluetoothlisten.c src/us.c)
