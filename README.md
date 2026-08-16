git config:

```bash
git config filter.settings-filter.clean "sed -E 's/^(name)\s\".*\"/\1 \"\"/'"
git config filter.profile-filter.clean "sed -E 's/^(localClientPlayerCachedLevel|pin_telemetry_report_date)\s\".*\"/\1 \"0\"/'"
```

launch options:

```
-novid -dev -netconport 42069 -no_render_on_input_thread +exec autoexec +mat_letterbox_aspect_goal 0 +mat_letterbox_aspect_threshold 0 +building_cubemaps 1
```
