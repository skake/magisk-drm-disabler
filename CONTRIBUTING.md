You're welcome to create pull requests and issues for bug reports or feature requests.

If creating a PR, please make sure to do it on GitLab.

## Testers welcome!

If you're interested in becoming a tester, please send me an e-mail or PM with your device(s) model, Android version and any other relevant info and I'll get back to you.

If trying to remove DRM libs, please remember that some libraries relate to Digital Restrictions Management while some refer to Direct Rendering Management. Removing the latter will cause graphics breakages through the whole system and possibly bootloops.

## Libraries that have been tested and cause a bootloop:
```
android.hardware.drm@1.0.so
android.hardware.drm@1.1.so
android.hardware.drm@1.2.so
libdrm.so
libdrmframework.so
libmediardm.so
libmediardmmetrics_lite.so
```
