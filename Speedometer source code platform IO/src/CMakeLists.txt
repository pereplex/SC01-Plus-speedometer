SET(SOURCES components/ui_comp_button1.c
    components/ui_comp.c
    screens/ui_Screen1.c
    screens/ui_Screen2.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_speedbg_png.c
    images/ui_img_speedfg_png.c
    images/ui_img_compass_png.c
    fonts/ui_font_Display16.c
    fonts/ui_font_Display24.c
    fonts/ui_font_Display40.c
    fonts/ui_font_Display90.c)

add_library(ui ${SOURCES})
