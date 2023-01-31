# android-ndk
android ndk download url for kernel compile

#### android-ndk-r10e for https://github.com/pagxir/ASUS_Z01GD_1-15.0410.1904.104 kernel compile

http://dl.google.com/android/repository/android-ndk-r10e-linux-x86_64.zip

#### use gradle to build android app

wget https://dl.google.com/android/repository/commandlinetools-linux-9477386_latest.zip
unzip commandlinetools-linux-9477386_latest.zip
cd cmdline-tools/bin && ./sdkmanager --licenses --sdk_root=${HOME}/android-sdk/Sdk/

export ANDROID_HOME=${HOME}/android-sdk/Sdk/
bash gradlew
