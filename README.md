# RPIPicoFreeRTOScpp
CPP Memory Management in FreeRTOS on the Raspberry PI Pico.

This is a small example project to show how to override New and Delete to use the FreeRTOS memory model. This means at least a memory mode that have alloc and free available.

Not to override New and Delete the SDK requires that we enable exceptions!

I've also used the newer freertos_config target approach rather than using FREERTOS_CONFIG_FILE_DIRECTORY. This is a little fiddle to get to work.


