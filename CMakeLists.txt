CMAKE_MINIMUM_REQUIRED(VERSION 3.4...3.28 FATAL_ERROR)
PROJECT(ImGui VERSION 4.6 LANGUAGES C CXX)

ADD_LIBRARY(ImGui STATIC
    imconfig.h
    imgui_internal.h
    imgui.h
    imstb_rectpack.h
    imstb_textedit.h
    imstb_truetype.h
    imgui_demo.cpp
    imgui_draw.cpp
    imgui_tables.cpp
    imgui_widgets.cpp
    imgui.cpp
)
