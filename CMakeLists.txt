cmake_minimum_required(VERSION 3.16)
project(avr_spi C)

set(CMAKE_C_STANDARD 11)

add_executable(avr_spi
        spi_slave.c)
