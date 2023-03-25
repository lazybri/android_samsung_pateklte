# android_samsung_pateklte
 SM-W2015 Device Tree

## build command:
source build/envsetup.sh && export ALLOW_MISSING_DEPENDENCIES=true && lunch omni_pateklte-userdebug && mka bootimage

(optional)
export USE_CCACHE=1 && export CCACHE_EXEC=/usr/bin/ccache && ccache -M 50G && ccache -o compression=true
