curl http://<username>:<password>@<ipAddress>/Monarch/syncconnect/sdk.aspx?command=<command>

# all settings
/api/command/reboot GET
/api/time PUT

/x-protobuf/reply/GetUserRoleRequest GET

/api/context/settings GET
/api/context/settings/network GET
/api/context/settings/boot_partition_select GET
/api/context/settings/friendly_name GET
/api/context/settings/audio_out/hdmi GET
/api/context/settings/boot_partition_select PUT for set
/api/context/settings/video_out/procamps GET

/api/context GET
/api/context/info GET
/api/context/info/monitor_edid GET
/api/context/info/default_settings GET

/api/users/[Username] PATCH

# encoder
/api/context/settings/encoder/capture GET
/api/context/settings/encoder/capture/video GET
/api/context/settings/encoder/capture/audio GET
/api/context/settings/encoder/encoding GET
/api/context/settings/encoder/video_output GET
/api/context/settings/encoder/default_image GET
/api/context/settings/encoder/hdmi_in_edid GET

# decoder
/api/context/settings/decoder/streams GET
/api/context/settings/decoder/streams/{Id} GET
