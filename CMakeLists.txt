cmake_minimum_required(VERSION 3.14)
project(siso C)

set(CMAKE_C_STANDARD 11)

add_executable(siso
        config.c
        config.h
        connection.c
        connection.h
        iscsi.c
        iscsi.h
        login.c
        login.h
        main.c
        misc.c
        misc.h
        scsi.c
        scsi.h
        session.c
        session.h
        siso.c
        siso.h
        target.c
        target.h
        vol.c
        vol.h
        volstd.c
        volstd.h)
