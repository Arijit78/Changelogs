## 2.1 Vince
- August Security Patch
- EOL Build
- Upstream kernel to 4.9.327

## 2.0 Vince
- August Security Patch
- Add vendorsetup script
- Reorder blobs
- Add a script to reorder blobs list
- Update Project-Elixir flags and props
- Use Fingerprint from source
- Set TARGET_RECOVERY_DEVICE_MODULES := libinit_vince
- Set TARGET_BOOT_ANIMATION_RES := 720
- Ship Teamfiles Pixel Launcher
- Enable IORAP feature
- Switch to SkiaGL Threaded
- Remove vendor RenderScript implementation
- Compile HWUI for better performance
- Switch to QTI health implementation
- Undefine BOARD_HAS_QCOM_WLAN
- Drop TARGET_HAS_NO_POWER_STATS
- Set BUILD_BROKEN_TREBLE_SYSPROP_NEVERALLOW := true
- Set BUILD_BROKEN_ENFORCE_SYSPROP_OWNER := true
- Use SYSTEM_EXT_PRIVATE_SEPOLICY_DIRS
- Remove neverallows
- Allow every app to read camera props
- Enable config_avoidGfxAccel for 3GB variants
- Rework dalvik
- Update Dalvik heap configuration
- Adapt new libinit changes
- Drop no longer necessary libbase include dir
- Restart QCRILD on airplane mode
- Restart QCRILD on data switch
- Restart QCRILD on decryption
- Disable Chimera.GmsIntentOperationService
- Apply aggressive write caching
- Add offline charging LED indicator
- Allocate 512MB for zram writeback backend
- Fix zram init process
- Disable ULL mode
- Don't advertise vorbis offloading support
- Tweak gps.conf a bit more
- Switch GPS xtra servers to xtrapath{4, 5, 6}
- gps Update GPS config for S
- Remove ssl GPS xtra servers
- New configs for better stability & accuracy
- Fix typo in thermal configs
- Enable running_without_sync_framework
- Re-enable in call music
- Don't manually set call vol steps
- Disable hwc vds in surface flinger
- Drop force triple frame buffers
- Replace deprecated sf props
- Remove USB extra config prop
- Set up USB Properties
- Set the maximum WFD resolution to 1080p@30
- Add overlays for battery health nodes
- Offload WM shell to another thread
- Fix deprecated power profile items
- Allow to be rotated in all 4 rotations
- Speed up animations
- Set default window animation/transition scales
- Revert "Nuke libinit [WIP]"
- Revert "Checkout audio configs from https://github.com/xiaomi-msm8953-devs"
- Revert "Switch to userspace LMKD"
- Upstream kernel to 4.9.325

## 1.7 Vince
- May Security Patch
- No device side changes
- Upstream kernel to 4.9.314

## 1.6 Vince
- April Security Patch
- No device side changes
- Upstream kernel to 4.9.312

## 1.5 Vince
- February Security Patch
- Drop lineage overlay
- Drop antradio_library
- Downgrade IRadioConfig to 1.0
- Build vendor variant of vendor.display.config@1.0
- Build libdisplayconfig.qti from source
- Update IDisplayConfig to 2.0 version
- Show ColorModes from config_availableColorModes
- Address init denial
- Update boot time error
- Add support for Face Unlock
- Update Redfin FP to March
- Switch to Cosmic clang
- Upstream kernel to 4.9.307

## 1.4 Vince
- February Security Patch
- Set vendor.post_boot.parsed=1
- Set BPF support level
- Enable debug.sf.latch_unsignaled
- Update Redfin FP to Feb
- Disable in call music
- Checkout audio configs from https://github.com/xiaomi-msm8953-devs
- Update Media and Graphic blobs from LA.UM.9.6.2.r1-04200-89xx.0
- Update WiFi blobs from LA.UM.9.6.3.r1-04400-89xx.0
- Switch to userspace LMKD
- Add vulkan and egl hardware variant properties
- Switch to Vulkan UI renderer
- Update Vulkan Configs
- Upstream kernel to 4.9.300

## 1.3 Vince
- Initial build
- January security patch
- Enforcing build
- Safetynet passes by default
- Bankings apps are working fine
- Unlimited Google photos in original quality available
