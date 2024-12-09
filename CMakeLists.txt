# Configurar la ruta a IPlug2
set(IPLUG2_PATH "${CMAKE_SOURCE_DIR}/IPlug2")

# Configurar la ruta al VST3 SDK
set(VST3_SDK_PATH "${CMAKE_SOURCE_DIR}/VST3_SDK")

# Incluir los archivos de IPlug2 y VST3 SDK
include_directories(${IPLUG2_PATH}/IPlug
                   ${VST3_SDK_PATH}/vst/vstaudioeffect)

