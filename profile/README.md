## Realme C25 Series Sources - all in one Sources for realme C25 and realme C25s

### Our Team!
- [eun0115](https://github.com/eun0115) - Lead Developer
- [Fire7ly](https://github.com/fire7ly) - Recovery Developer

## Heres what you need to clone to build
### Android 11 Trees
git clone https://github.com/eun0115/gear_kernel_even/ kernel/realme/even ; cd kernel/realme/even ; git reset --hard 1d888a0ab5bef89c6440292b1ef64f300b4d3088 ; cd ../../.. ; git clone https://github.com/KharaMe-devices/vendor_realme_even vendor/realme/even ; git clone https://github.com/Realme-C25-Series-Development/android_packages_apps_RealmeDirac -b lineage-18.1 packages/apps/RealmeDirac ; git clone https://github.com/Realme-C25-Series-Development/android_packages_apps_RealmeParts -b lineage-18.1 packages/apps/RealmeParts ;  git clone https://github.com/KharaMe-devices/vendor_realme_even-ims -b eleven-rmui2 vendor/realme/even-ims ; git clone https://github.com/KharaMe-devices/device_realme_even -b eleven-rmui2 device/realme/even ; cd device/realme/even

### Android 12 Trees
git clone https://github.com/eun0115/4.14_kernel_even/ kernel/realme/even ; cd kernel/realme/even ; git reset --hard d16fc802610fc2be4e0c7959f9660cd2ec4a9917 ; cd ../../.. ; git clone https://github.com/Realme-C25-Series-Development/vendor_realme_even vendor/realme/even ; git clone https://github.com/Realme-C25-Series-Development/vendor_realme_even-ims vendor/realme/even-ims; git clone https://github.com/Realme-C25-Series-Development/android_packages_apps_RealmeDirac -b lineage-19.0 packages/apps/RealmeDirac ; git clone https://github.com/Realme-C25-Series-Development/android_packages_apps_RealmeParts -b lineage-19.0 packages/apps/RealmeParts ; git clone https://github.com/Realme-C25-Series-Development/device_realme_even device/realme/even ; cd device/realme/even
