# Floyd-Rom-S7-edge
Custom rom for s7 edge 

Floyd 7.0 - 01.07.2022


- Fully rebuilt and rebased on N960FXXS9FVE1 May 2022 Patch
- Cumulative fixes and changes since April 2021
- Merged samsung security patches since v6
- Re-worked Audio / AudioFX System to mitigate issues
- Boost overall Audio/Bass And match it more with Pie
- Various misc fixes in the base forked from Note 8 Q project
- Performance improvment due to base changes
- Support Selinux Enforcing
- Update ALL the apps/featuers in bloat to latest Q release

Aroma
- MemorySaver/Storage booster included by default
- Update iOS Emojis to 14.6
- Include latest chinese smart manager with added features
- Add Manage App Data feature (enable/disable network per app)
- Updated Goodlock mod to 20220413
- Update AdAway to v5.12.1
- Fix BixbyRoutines FC when enabling brightness control
- Add latest SamsungDaily
- Remove Force RCS as it needs carrier and reciver support
- Remove VancedManager due it being Discontinued
- Add calculator directly in the rom
- Updated OMC packages to latest FUK1 package
- Remove S9+ Infinity Wallpaper package due to samsung stopping updates
- Add Toggle for SELinux Enforcing (Check F.A.Q for more details)

Fixes
- Fix issues with power/thermal HAL that caused lag and performance degredation
- Improve Auto brightness tables
- Fix IRIS sensor on Note 7 and make it work in secure folder and other places
- Fix note 7 lag on lock screen
- Disable Note 7 torch intensity slider to avoid FCs and workaorund it
- Fix Selfie capture with HeartRate sensor
- Support more NFC card types (Mifare plus Thanks @Pavlon333)
- Cleanup some of the broken constant logging services
- Disable High Brightness Warning
- Improve and update basic safetynet hiding without magisk
- Update Safetynet Fix to bypass recent GMS restrictions (Thanks @@AndrzejDwo and @Ivan_Meler)
- Enable back Audio encoding in Slowmotion videos
- Remove problematic RAM configs
- add 2x zoom button in camera
- More improvments to RAM/ZRAM
- Fix wakeup freezes
- Fix Alarm issues
- More test fixes for Audio muting issue
- Improve Audio Quality / bass a bit
- Set Actual device name instead of note 9 by default
- Remove old deperecated props
- Various other misc changes in the ROM/Base
- Workaround initial FDSAN Error that causes issues
- Prevent Notes APP from updating on N7FE (to fix pen issue)</*)

CronosKernel
- CronosKernel V7.0
- Re-enable wakeups by eventpoll
- Revert problematic I2C stall fixes
- Revert CPUFreq relation back to stock
- Enable back HMP Boosting on GPU to avoid wakeup issues
- Restore default DVFS CPU Behaviour
- Add custom tune build flag
- Optimze the kernel for performance instead of size
- Revert power-queue changes
- Revert GPU MIF clock back to stock
- Revert CPU Boost freq back to stock
- Merge updates for I2C From Exynos7870
- Restore N7FE Camera/Iris code
- Misc sound-core driver changes from Exynos7870
- Enable CIFS Driver
- Disable Forced Permissive
- Enable back Audit logging
- Increase default audio in moro_sound
- Set Torch brightness to max on Note7 due to lack of slider
- fix pm_qos kernel panic in camera driver

