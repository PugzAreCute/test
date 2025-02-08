---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "FOSSonTop"
  text: "AOSP Docs"
  actions:
    - theme: brand
      text: Add Content to Docs
      link: https://github.com/FOSSonTop/aosp
    - theme: alt
      text: Go Back
      link: ../index
features:
  - title: Build Guide
    description: Simple Android Build Guide with General steps to get started.
    link: ./building-101
#features:
#  - icon: We'll fill these later as we're doing the migration
#    title: 
#    link: 
---

### Information and Guides

Here are some general links and guides:

- [Building 101](./wiki/Building_101)
- [Glossary of key terms](./wiki/Glossary)
- [Debugging/Taking Logs](./wiki/Debugging)
- IMY's Bringup Guides
  - [Intro](./wiki/imy-bringup/intro)
    - [Episode 1](./wiki/imy-bringup/Episode-1/bringup)
      - [Glossary/Lore Deep Dive](./wiki/imy-bringup/Lore-Explanation/filler_ep1)
- [Notes for Samsung Exynos Devices](./wiki/Exynos_Notes)

### Useful Resources

Here, we have some more useful resources:

#### English Language
- [Google's AOSP Build Guide](https://source.android.com/docs/setup/build/building)
- [Lineage Build Guide](https:/./wiki.lineageos.org/devices/bacon/build)
- [Divest OS (EOL) Build Guide](https://web.archive.org/web/20241223172341/https://divestos.org/pages/build)
- [Lopestom's Bringup guides](https://gist.github.com/lopestom)
- [RealOGs Bringup Guide](https://blog.realogs.in/android-device-tree-bringup)
- [DaltonFury42's Build Guide](https://medium.com/@daltonfury42/building-lineageos-for-your-device-a7d26ab50549)
- [AtlanPrime's Build Guide](https://customromguide.github.io/)
- [Mohamed Rashik's AOSP Build Guide](https://medium.com/@mmohamedrashik/a-beginners-guide-to-building-android-from-aosp-03ab4913614b)
- [Robin W. Hunter's Build Guide](https://bitgrounds.tech/posts/porting-android-to-unsupported-devices-part2/)
- [AlaskaLinuxUser Youtube](https://www.youtube.com/channel/UCnGqG_jyyXmTzdamBpKfeHA)
- [AlaskaLinuxUser Blog](https://alaskalinuxuser3.ddns.net)
- [Awesome Android AOSP](https://github.com/Akipe/awesome-android-aosp/blob/main/readme.md)
- [LineageOS Vendor Tree Guide](https:/./wiki.lineageos.org/proprietary_blobs.html)

#### Turkish Language
- [Yusuf İpek's Build Guide](https://yusufipek.me/custom-rom-derleme-rehberi/)

#### Ukrainian Language
- [Roker2's Build Guide](https://roker2.github.io/BookAboutBuilding/ua/)

### GSI and more Resources:

Here are resources useful for GSI developers and users:

- [Phhusson's Treble-Experimentations](https://github.com/phhusson/treble_experimentations./wiki)

### Signing Guides(Non-Crave)

Here are some guides on signing builds:
(avoid using on Crave)

- [Inline Guide for Dev-Keys by A2L5E0X1](https://gist.github.com/A2L5E0X1/54cb1b3a49030a9ebf8608b4e68073f5)
- [Inline Guide by CrDroid](https://crdroid.net/blog/2024-06-01-sign-your-crDroid-builds-and-keep-play-integrity-happy)
- [Detailed Guide by LineageOS](https:/./wiki.lineageos.org/signing_builds)
- [Detailed Guide by AOSP](https://source.android.com/docs/core/ota/sign_builds)

### SELinux Guides

Here is some documentation to deal with SELinux:

- [AOSP General SELinux](https://source.android.com/security/selinux/customize)
- [AOSP Device SELinux](https://source.android.com/security/selinux/device-policy)
- [LineageOS SELinux Guide](https://lineageos.org/engineering/HowTo-SELinux)

### Tools

Here, you can find some useful scripts to make things easier while developing

- [Azwhikaru's Action-TWRP-Builder](https://github.com/azwhikaru/Action-TWRP-Builder)
  - Build Recoveries Online using Github Actions
- [SebaUbuntu's Twrpdtgen](https://github.com/twrpdtgen/twrpdtgen)
  - Generate a minimal android device tree to start work on building a recovery like TWRP
- [SebaUbuntu's Aospdtgen](https://github.com/sebaubuntu-python/aospdtgen)
  - Generate a minimal android device tree to start work on building LineageOS
- [DumprX](https://github.com/DumprX/DumprX)
  - Extract your OEM's default ROMs to import things like Modules, Prebuilt Kernel, Vendor Blobs, Audio Configations, etc.
- [cd-Crypton's extract_proprietary_blobs](https://github.com/cd-Crypton/extract_proprietary_blobs)
  - Create a Vendor Tree from a Dump using Github Actions
- [Manifest Tester](https://github.com/sounddrill31/manifest_tester)
  - Test local and rom manifest xml files to ensure sync works as expected
- [Local Manifest Generator](https://github.com/sounddrill31/actions_generate_local_manifests)
  - Quickly generate local manifests from git clone, rm and repo init commands

## Chat Groups

- [Get Help](./wiki/Get_Help)
