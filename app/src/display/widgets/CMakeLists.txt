# Copyright (c) 2020 The ZMK Contributors
# SPDX-License-Identifier: MIT

target_sources_ifdef(CONFIG_ZMK_WIDGET_BATTERY_STATUS app PRIVATE battery_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_OUTPUT_STATUS app PRIVATE output_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_PERIPHERAL_STATUS app PRIVATE peripheral_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_LAYER_STATUS app PRIVATE layer_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_WPM_STATUS app PRIVATE wpm_status.c)
target_sources_ifdef(CONFIG_ZMK_WIDGET_INDICATORS_STATUS app PRIVATE hid_indicators_status.c)
