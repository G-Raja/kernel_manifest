
# Download Kernel source
 Refer to https://source.android.com/setup/build/building-kernels

 Make separate kernel directory apart from Android source.

  $ cd <kernel directory>
  $ repo init -u https://github.com/G-Raja/kernel_manifest -b arpi4-5.10
  $ repo sync
 
# Build Kernel
  $ build/build.sh

  Output files are under out/arpi4-5.10/dist/
    Image.gz
    bcm2711-rpi-*.dtb
    vc4-kms-v3d-pi4.dtbo
