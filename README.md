# manifest

Android Manifest

Instructions:
  - mkdir ~/bin
  - PATH=~/bin:$PATH
  - curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
  - chmod a+x ~/bin/repo
  - git config --global user.name "Your Name"
  - git config --global user.email "you@example.com"
  - mkdir myAndroid
  - cd myAndroid
  - repo init -u ssh://git@git.seco.com/arm/nxp/imx/develop/android/android_9.0.0/manifest.git -b p9.0.0_2.2.0-ga
  - repo sync -j 20 [ --force-sync ]
  - drink a very long coffee

To compile:
  - source setup&#60;board-name&#62; (Eg: setupA62, setupC20 ...)
  - make -j 4
  - drink a very long long coffee
  - prepare_distro_uuu.sh

To flash board: sudo ./uuu uuu-android-&#60;imx-architecture>-&#60;board-name&#62;-&#60;video-display&#62;-&#60;mmc-size&#62;.lst 



  
