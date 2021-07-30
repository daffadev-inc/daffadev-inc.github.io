---
layout: post
image: https://drive.google.com/uc?export=download&id=1tvkeGbgF7pfg9WRAEPiR9ZsMyAfDviMh
title: Install APK tool di Linux
category: Linux
excerpt_separator: <!--more-->
---

Cara install APKtool di linux mint, buka terminal lalu Copy Paste Kode dibawah.<!--more-->
# Get latest version from https://bitbucket.org/iBotPeaches/apktool/downloads
<pre>
export apktool_version=2.3.1

sudo -E sh -c 'wget https://bitbucket.org/iBotPeaches/apktool/downloads/apktool_$apktool_version.jar -O /usr/local/bin/apktool.jar'

sudo chmod +r /usr/local/bin/apktool.jar

sudo sh -c 'wget https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/linux/apktool -O /usr/local/bin/apktool'

sudo chmod +x /usr/local/bin/apktool
</pre>

# To use:

# apktool d TelephonyProvider.apk -o TelephonyProvider
