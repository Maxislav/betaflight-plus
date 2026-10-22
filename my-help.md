
make arm_sdk_install
make configs
make clean

make CONFIG=VYRIY EXTRA_FLAGS="-DUSE_ALT_HOLD"
make CONFIG=VYRIY EXTRA_FLAGS="-DUSE_ALTITUDE_HOLD"

make CONFIG=SPEEDYBEEF405V3

set debug_mode = RX_TIMING


set ap_cruise_angle = 15 // 15 degree
set altitude_source = BARO_ONLY