
make arm_sdk_install
make configs
make clean

make CONFIG=VYRIY EXTRA_FLAGS="-DUSE_ALT_HOLD"
make CONFIG=VYRIY EXTRA_FLAGS="-DUSE_ALTITUDE_HOLD"

make CONFIG=SPEEDYBEEF405V3

set debug_mode = RX_TIMING

set ap_follow_mode = 1700, 2100, 4 // AUX 4 from 1700 2100
set ap_follow_angle = 15 // 15 degree
set altitude_source = BARO_ONLY