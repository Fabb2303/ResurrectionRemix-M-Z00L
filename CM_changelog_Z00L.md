# Cyanogenmod 13 Z00L Changelog

### cm-13.0-20160428-NIGHTLY-Z00L.zip

- Generate all color swatches. (android_packages_apps_Eleven)
- Add toString() methods to BitmapWithColors class. (android_packages_apps_Eleven)
- Load palette in background. (android_packages_apps_Eleven)
- audiofx: Use CMAudioService for session callbacks (android_packages_apps_AudioFX)
- cmsdk: Add CMAudioManager (cm_platform_sdk)
- cm: Add CMAudioService the platform (android_vendor_cm)
- media: Remove effect session callbacks from the framework (android_frameworks_base)
- audiopolicy: Add AudioSessionInfo API (android_frameworks_av)
- audiopolicy: Revert all session callback patches. (android_frameworks_av)
- WundergroundCM: Fix partlycloudy weather code response. (android_packages_apps_WundergroundWeatherProvider)
- [4/4] Update dialer for CallMethodHelper refactor (android_packages_apps_Dialer)
- [3/4] Update incall for callmethodhelper refactor (android_packages_apps_InCallUI)
- [2/4] Update contacts for CallMethodHelper refactor (android_packages_apps_Contacts)
- [1/4] Refactor CallMethodHelper (android_packages_apps_PhoneCommon)
- Add InCall providers call logs into the statistics pages (android_packages_apps_Dialer)
- Settings: restore proper live display color profile (android_packages_apps_Settings)
- WundergroundCM: Update README. (android_packages_apps_WundergroundWeatherProvider)
- DASH: Log the sensors_wrapper_activate lock/unlocks as verbose (android_hardware_sony_DASH)
- SetupWizard: Add Mod disovery language for mod ready devices (android_packages_apps_SetupWizard)
- SetupWizard: Ensure compliance with GMS TOS (android_packages_apps_SetupWizard)
- surfaceflinger: Add support for Exynos BGRA mixer (android_frameworks_native)
- Gello: don't move navigation bar when selecting url text (android_packages_apps_Gello)
- SysUI: Don't call removeAllViews on AdapterView (android_frameworks_base)
- msm8916-common: rootdir: Update init.qcom.bt.sh from CAF (android_device_asus_msm8916-common)
- msm8916-common: sepolicy: Add bluetooth_loader (android_device_asus_msm8916-common)
- Add MVNO configs for Lycamobile ES and Truphone ES (android_packages_apps_CarrierConfig)


### cm-13.0-20160427-NIGHTLY-Z00L.zip

- msm8916-common: Switch to set_prop() (android_device_asus_msm8916-common)
- drivers: tfxxxx: Remove dclick_flag check (android_kernel_asus_msm8916)
- Improve RTL layout behaviour. (android_packages_apps_Snap)
- Improve visualizer color selection. (android_packages_apps_Eleven)
- Simplify and improve dream, LLS and weather provider layouts. (android_packages_apps_Settings)
- Add uses-feature for play store targeting. (android_packages_apps_OpenWeatherMapProvider)
- livedisplay: Fix another transition issue (cm_platform_sdk)
- WifiNudge: Use PreciseCallState to only show on outgoing calls (android_packages_apps_Dialer)
- fastboot: Add Nextbit's USB vendor id (android_system_core)
- Hide coachmark if dialpad opens with text pre-filled (android_packages_apps_Dialer)
- CallButtons: Prevent FRP bypass via the video calling option (android_packages_apps_InCallUI)
- Check if Volte is enabled in ImsManager to determine Volte support (android_packages_apps_PhoneCommon)
- Fix call method spinner text cutoff (android_packages_apps_PhoneCommon)
- Relocate weather provider samples to CMSDK samples folder (android)
- WundergroundCM: Add uses-feature for play store targeting. (android_packages_apps_WundergroundWeatherProvider)
- Initial checking of OpenWeatherMap weather provider service (android_packages_apps_OpenWeatherMapProvider)
- Add Weather Content Provider [5/5] (android_frameworks_base)
- Add OpenWeatherMapProvider (android)
- Refactor cLock to use the new Weather API (android_packages_apps_LockClock)
- Setting : Don't show search for activities not within same shared user id (android_packages_apps_Settings)
- SetupWizard: Handle register theme change listener crash (android_packages_apps_SetupWizard)
- Gello: remove holo-like share dialog (android_packages_apps_Gello)
- Gello: kang in two methods which changed their location and access (android_packages_apps_Gello)
- Gello: Share bitmap via stream vs bitmap (android_packages_apps_Gello)
- Gello: definitive ad block list (android_packages_apps_Gello)
- Gello: web_refiner: Fix EasyList URLs (android_packages_apps_Gello)
- Trebuchet : Update default workspace for dialer (android_packages_apps_Trebuchet)
- Remove cyngn dialer (android_vendor_cm)
- SetupWizard: Fix test app building (android_packages_apps_SetupWizard)
- vold: Fix cryptfs changepw parsing (android_system_vold)
- Fix nudge counts (android_packages_apps_Dialer)
- Add Renault MediaNav to HFP 1.7 blacklist (android_system_bt)
- Mount pstore filesystem while in recovery (android_bootable_recovery)


### cm-13.0-20160426-NIGHTLY-Z00L.zip

- Fixed the cutoff timestamp for MMS deletion by limit. (android_packages_apps_Messaging)
- XML Pull Parser optimizations (android_libcore)
- livedisplay: Add some unit tests (cm_platform_sdk)
- settings: Remove LiveDisplay preferences if not available (android_packages_apps_Settings)
- cmsdk: Fix crash when getting LiveDisplay config (cm_platform_sdk)
- livedisplay: Connect display modes to CMHW (cm_platform_sdk)
- ThemeChooser: don't try to set bg color when displaying from font filter (android_packages_apps_ThemeChooser)
- Add new method to LookupHandlerThread for calling new API interfaces (android_packages_apps_ContactsCommon)
- Implement lookup provider for 4x3 and 3x3 widget (android_packages_apps_Messaging)
- msm8916-common: Preload & cache bootanimation (android_device_asus_msm8916-common)
- Makefile moved to vendor/cm (android_external_gello_build)
- bootanimation: Switch to readahead (android_frameworks_base)
- fastboot: add ZTE to the list of known vendors (android_system_core)
- cluster-plug: Treat offline little cores as "unloaded" (android_kernel_asus_msm8916)
- cluster_plug: Making cluster low_power/active synchronous state changes (android_kernel_asus_msm8916)
- Fix bug in CallManager unregisterForPhoneStates() (android_frameworks_opt_telephony)
- Bring back original color (android_packages_apps_Messaging)
- CMBugReport: add bypass processing config (android_packages_apps_CMBugreport)
- Ensure synchronized access of JNI callback object (android_packages_apps_Bluetooth)
- SetupWizard: GMS page controls the next step (android_packages_apps_SetupWizard)
- Settings: fix incorrect default sim/sms/data selection logic (android_packages_apps_Settings)
- LLS: Update LLS slide offsets when focus changes (android_frameworks_base)



### cm-13.0-20160425-NIGHTLY-Z00L.zip

- msm8916-common: Update USB configuration (android_device_asus_msm8916-common)
- arm64: boot: Makefile: Point the dt append finding code to qcom directory (android_kernel_asus_msm8916)
- SoundRecorder: cleanup (android_packages_apps_SoundRecorder)
- Screencast: cleanup (android_packages_apps_Screencast)
- Eleven: Cleanup all the whitespace (android_packages_apps_Eleven)
- add medianav to unsupported device for hfp 1.7 (android_system_bt)
- Themes: Add tint mode so custom icons can show in power usage detail (android_packages_apps_Settings)
- stagefright-plugins: Fix port reset problem (android_external_stagefright-plugins)
- stagefright-plugins: Fix eos flush problem. (android_external_stagefright-plugins)
- livedisplay: Fix three bugs (cm_platform_sdk)
- Null check before accessing AP objects (android_frameworks_opt_net_wifi)


### cm-13.0-20160424-NIGHTLY-Z00L.zip

- drivers: tfxxxx: Remove proximity check (android_kernel_asus_msm8916)
- arch/arm: dts: MSM8939 switch to msec idle-timeout (android_kernel_asus_msm8916)
- msm: kgsl: Fix direct references to HZ (android_kernel_asus_msm8916)
- arm64/configs: Enable several USB ethernet drivers (android_kernel_asus_msm8916)
- CMBugReport: better bug report uploading (android_packages_apps_CMBugreport)
- Support for new properties to identify country based ecc #s added by RIL (android_frameworks_base)
- Update Ambient SDK to 1.5.5 (android_vendor_cm)
- WundergroundCM: Update iconography. (android_packages_apps_WundergroundWeatherProvider)
- NPE: check that cn is null and return (android_packages_apps_Dialer)
- Fix crash in Settings when clicking on Phone Number Lookup (android_packages_apps_Dialer)
- sepolicy: Allow recovery to mount on tmpfs (android_vendor_cm)
- Text/Multimedia message limit feature (android_packages_apps_Messaging)
- camera: fix large tiler memory leakages (android_hardware_ti_omap4)
- LLS: Show notification panel if LLS crashes (android_frameworks_base)
- LLS: Fix screen off event firing when not interactive (android_frameworks_base)
- libhwui: Remove opaque check for everything (android_frameworks_base)
- audiopolicy: Fix notification not sent for session release (android_frameworks_av)
- Keyguard: switch to cm-specific device provisioned flag (android_frameworks_base)
- CMSettings: add CM_SETUP_WIZARD_COMPLETED key (cm_platform_sdk)
- SetupWizard: add a CM-specific setup-complete settings key (android_packages_apps_SetupWizard)
- Telecom: refresh missed call notification on locale change (android_packages_services_Telecomm)
- livedisplay: Always check for transition (cm_platform_sdk)
- fmapp2: Allow value for the default fm recording duration to be overlayed. (android_hardware_qcom_fm)
- SettingsProvider : load region-specific settings (android_frameworks_base)
- Check for default WeatherInfo values (android_packages_providers_WeatherProvider)
- Settings: Add back Accessibility (android_packages_apps_Dialer)
- msm8916-common: Boost mic globally (android_device_asus_msm8916-common)
- Themes: Update icon mapping on boot (android_frameworks_base)
- Snap: Add support for focus distance (android_packages_apps_Snap)
- Improvements to Nudges (android_packages_apps_Dialer)
- Search: Show FAB in the right place (android_packages_apps_Dialer)
- Quick search results: fix to match selected item in spinner (android_packages_apps_Dialer)
- Add metrics event for selecting call method (android_packages_apps_Dialer)
- Revert and modify "Change in InCallAPI handover button UI" (android_packages_apps_InCallUI)
- livedisplay: Bugfixes and cleanups (cm_platform_sdk)
- Revert "Snap: Improve focusing" (android_packages_apps_Snap)
- WundergroundCM: Make sure to set the current days forecast. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Update gradlewrapper version and only pull from mc. (android_packages_apps_WundergroundWeatherProvider)
- cmsdk: Ignore "samples" subdir. (cm_platform_sdk)
- manifest: Add Weather Underground weather provider service sample. (android)
- WundergroundCM: Point at maven central for artifact. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Provide weathercondition to weathercode map. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Add api key verification mechanism. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Provide attribution and do clean up. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Add settings activity. (android_packages_apps_WundergroundWeatherProvider)
- WundergroundCM: Build against release artifact. (android_packages_apps_WundergroundWeatherProvider)
- sensorservice: fix an invalid format string (android_frameworks_native)
- sensorservice: add power usage to dumpsys (android_frameworks_native)
- Convert call log and call stats details to new contact blocking code. (android_packages_apps_Dialer)
- Call Statistics: fix NPE on rotation (android_packages_apps_Dialer)
- DO NOT MERGE Enhance AVRCP Absolute Volume control implementation (android_packages_apps_Bluetooth)
- default.xml: cm: Update to 6.0.1_r30 (android)
- Update Ambient SDK to 1.5.3 (android_vendor_cm)
- Import national-roaming settings from f/b (android_packages_apps_CarrierConfig)
- Merge tag 'android-6.0.1_r30' into HEAD (android_frameworks_base)
- DO NOT MERGE: Use GregorianCalendar.add() when searching for next alarm. (android_frameworks_base)
- Exit getAllValidScorers early if not the primary. (android_frameworks_base)
- Fix missing observer reply callbacks (android_frameworks_base)
- DO NOT MERGE ANYWHERE: UsageStatsService: Fix app idle issue at rollover time (android_frameworks_base)
- DO NOT MERGE ANYWHERE: UsageStats: Fix issue where initializing data for first time would cause crash (android_frameworks_base)
- DO NOT MERGE ANYWHERE: UsageStats: Use new settings key idle_duration2 for app idle (android_frameworks_base)
- DO NOT MERGE Check apps idle states on time changes (android_frameworks_base)
- DO NOT MERGE Fix for syncs being dropped when appIdle is on (android_frameworks_base)
- DO NOT MERGE ANYWHERE: Don't change screen on time on time changes (android_frameworks_base)
- DO NOT MERGE ANYWHERE: Hack to get devices booting again. (android_frameworks_base)
- DO NOT MERGE Bluetooth: Restrict gain for Absolute volume case (android_frameworks_base)
- DO NOT MERGE Read Bluetooth interop database entries from settings (1/2) (android_frameworks_base)
- Conflict resolution CL to ag/868720 when cp'ing to mnc-mr1-release (android_frameworks_base)
- Redact Account info from getCurrentSyncs (android_frameworks_base)
- DO NOT MERGE Add ability to add interop entries dynamically (2/2) (android_system_bt)
- DO NOT MERGE Remove Porsche car-kit pairing workaround (android_system_bt)
- DO NOT MERGE Blacklist devices for absolute volume control (android_system_bt)
- DO NOT SUBMIT Revert "DO NOT MERGE Blacklist devices for absolute volume control" (android_system_bt)
- Trust CA certificates added for the whole OS only (android_packages_apps_CertInstaller)
- Merge tag 'android-6.0.1_r30' into HEAD (android_packages_apps_CertInstaller)
- [DO NOT MERGE ANYWHERE] Null terminate MAP instance information (android_packages_apps_Bluetooth)
- Fix memory leak in Bluetooth AVRCP JNI (android_packages_apps_Bluetooth)
- DO NOT MERGE Read Bluetooth interop database entries from settings (2/2) (android_packages_apps_Bluetooth)
- DO NOT MERGE Add ability to add interop entries dynamically (1/2) (android_hardware_libhardware)
- Merge tag 'android-6.0.1_r30' into HEAD (android_hardware_libhardware)
- DO NOT MERGE Update libpng to 1.6.20 (android_external_libpng)
- Merge tag 'android-6.0.1_r30' into HEAD (android_external_libpng)
- Fix integer overflows in recovery procedure. (android_bootable_recovery)
- Merge tag 'android-6.0.1_r30' into HEAD (android_bootable_recovery)
- Update timezone data to 2016a (android_bionic)
- Merge tag 'android-6.0.1_r30' into HEAD (android_bionic)
- Add Weather API test coverage (cm_platform_sdk)
- Add json-c for 8996 builds (android)
- Lockscreen : Fix dead-zone in bottom area (android_frameworks_base)
- Revert "Lockscreen : Ensure window bounds change after view animations" (android_frameworks_base)
