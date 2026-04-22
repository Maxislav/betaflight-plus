
make arm_sdk_install
make configs
make clean

make CONFIG=VYRIY EXTRA_FLAGS="-DUSE_ALT_HOLD"

set debug_mode = RX_TIMING