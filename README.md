# Cloned following repos - aosp-9.0 branch
Device: 
https://github.com/Unlegacy-Android/android_device_lge_mako and modified it for Carbon

Kernel: 
https://github.com/Unlegacy-Android/android_kernel_qcom_msm8960/tree/stable

https://github.com/Unlegacy-Android/proprietary_vendor_lge
https://github.com/Unlegacy-Android/proprietary_vendor_qcom
https://github.com/Unlegacy-Android/proprietary_vendor_broadcom
https://github.com/Unlegacy-Android/proprietary_vendor_widevine

https://github.com/Unlegacy-Android/android_hardware_interfaces and picked this commit to avoid build commit:
https://github.com/LineageOS/android_hardware_interfaces/commit/795990cca6f0979ec9cd397e345bd87a247ff97f

Picked these commits in system/core:
git fetch https://gerrit.unlegacy-android.org/Unlegacy-Android/android_system_core refs/changes/60/10160/7 && git cherry-pick FETCH_HEAD
git fetch https://gerrit.unlegacy-android.org/Unlegacy-Android/android_system_core refs/changes/86/10486/5 && git cherry-pick FETCH_HEAD
git fetch https://gerrit.unlegacy-android.org/Unlegacy-Android/android_system_core refs/changes/87/10487/2 && git cherry-pick FETCH_HEAD
