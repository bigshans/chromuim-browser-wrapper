# Chromium-browser-wrapper

# Introduction

This respository is prepared to build Chromium-browser-wrapper deb package. The Chromium in the Debian officical is not supported hardware acceleration so I have to use the ppa's Chromium. But the chromium from ppa is built for Ubuntu not for Debian, which causes compatibility issues in Debian. So I built this package to solve this problem.

# Build

To run command:

``` sh
./build.sh
```

# Install

``` sh
apt install ./chromium-browser-wrapper.deb
```
