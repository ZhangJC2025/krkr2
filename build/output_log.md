<pre><font color="#8AE234"><b>zhangjc@zhangjc-virtual-machine</b></font>:<font color="#729FCF"><b>~/Code/krkr2</b></font>$ ./scripts/build-linux.sh
Preset CMake variables:

  CMAKE_BUILD_TYPE=&quot;Debug&quot;
  CMAKE_EXPORT_COMPILE_COMMANDS:BOOL=&quot;TRUE&quot;
  LINUX:BOOL=&quot;TRUE&quot;

-- Running vcpkg install
Detecting compiler hash for triplet x64-linux...
Compiler found: /usr/bin/c++
The following packages are already installed:
    7zip:x64-linux@24.09#1
  * alsa:x64-linux@1.2.14
    argparse:x64-linux@3.2
  * at-spi2-atk:x64-linux@2.38.0#1
  * at-spi2-core:x64-linux@2.44.1#3
  * atk:x64-linux@2.38.0#10
  * boost-algorithm:x64-linux@1.88.0
  * boost-align:x64-linux@1.88.0
  * boost-array:x64-linux@1.88.0
  * boost-assert:x64-linux@1.88.0
  * boost-atomic:x64-linux@1.88.0
  * boost-bind:x64-linux@1.88.0
  * boost-charconv:x64-linux@1.88.0#1
  * boost-chrono:x64-linux@1.88.0
  * boost-cmake:x64-linux@1.88.0
  * boost-concept-check:x64-linux@1.88.0
  * boost-config:x64-linux@1.88.0
  * boost-container:x64-linux@1.88.0#1
  * boost-container-hash:x64-linux@1.88.0
  * boost-conversion:x64-linux@1.88.0
  * boost-core:x64-linux@1.88.0
  * boost-date-time:x64-linux@1.88.0
  * boost-describe:x64-linux@1.88.0
  * boost-detail:x64-linux@1.88.0
  * boost-dynamic-bitset:x64-linux@1.88.0
  * boost-endian:x64-linux@1.88.0
  * boost-exception:x64-linux@1.88.0
  * boost-function:x64-linux@1.88.0
  * boost-function-types:x64-linux@1.88.0
  * boost-functional:x64-linux@1.88.0
  * boost-fusion:x64-linux@1.88.0
  * boost-headers:x64-linux@1.88.0
  * boost-integer:x64-linux@1.88.0
  * boost-intrusive:x64-linux@1.88.0
  * boost-io:x64-linux@1.88.0
    boost-iostreams[core,zstd,zlib,lzma,bzip2]:x64-linux@1.88.0
  * boost-iterator:x64-linux@1.88.0
  * boost-lexical-cast:x64-linux@1.88.0
    boost-locale:x64-linux@1.88.0#1
  * boost-move:x64-linux@1.88.0
  * boost-mp11:x64-linux@1.88.0
  * boost-mpl:x64-linux@1.88.0
  * boost-numeric-conversion:x64-linux@1.88.0
  * boost-optional:x64-linux@1.88.0
    boost-phoenix:x64-linux@1.88.0
  * boost-pool:x64-linux@1.88.0
  * boost-predef:x64-linux@1.88.0
  * boost-preprocessor:x64-linux@1.88.0
  * boost-proto:x64-linux@1.88.0
  * boost-random:x64-linux@1.88.0
  * boost-range:x64-linux@1.88.0
  * boost-ratio:x64-linux@1.88.0
  * boost-regex:x64-linux@1.88.0
  * boost-smart-ptr:x64-linux@1.88.0
    boost-spirit:x64-linux@1.88.0
  * boost-static-assert:x64-linux@1.88.0
  * boost-system:x64-linux@1.88.0
  * boost-thread:x64-linux@1.88.0
  * boost-throw-exception:x64-linux@1.88.0
  * boost-tokenizer:x64-linux@1.88.0
  * boost-tuple:x64-linux@1.88.0
  * boost-type-index:x64-linux@1.88.0
  * boost-type-traits:x64-linux@1.88.0
  * boost-typeof:x64-linux@1.88.0
  * boost-uninstall:x64-linux@1.88.0
  * boost-unordered:x64-linux@1.88.0
  * boost-utility:x64-linux@1.88.0
  * boost-variant:x64-linux@1.88.0
  * boost-variant2:x64-linux@1.88.0
  * boost-winapi:x64-linux@1.88.0
  * box2d:x64-linux@3.1.1
  * brotli:x64-linux@1.1.0#1
    bullet3:x64-linux@3.25#3
  * bzip2[core,tool]:x64-linux@1.0.8#6
  * cairo[core,x11,gobject,freetype,fontconfig]:x64-linux@1.18.4
    catch2:x64-linux@3.10.0
  * chipmunk:x64-linux@7.0.3#7
    cocos2dx:x64-linux@3.17.2#5
  * curl[core,ssl,openssl,non-http]:x64-linux@8.15.0#1
  * dbus[core,systemd]:x64-linux@1.16.2#2
  * dirent:x64-linux@1.26
  * egl-registry:x64-linux@2024-01-25
  * expat:x64-linux@2.7.1
    ffmpeg:x64-linux@3.3.9
    fmt:x64-linux@11.2.0
  * fontconfig:x64-linux@2.15.0#4
  * freetype[core,zlib,png,bzip2,brotli]:x64-linux@2.13.3
  * fribidi:x64-linux@1.0.16
  * gdk-pixbuf[core,tiff,png,jpeg]:x64-linux@2.42.12#4
  * gettext[core,tools]:x64-linux@0.22.5#2
  * gettext-libintl:x64-linux@0.22.5#3
  * glew:x64-linux@2.2.0#6
    glfw3:x64-linux@3.4#1
  * glib:x64-linux@2.84.2#2
  * gperf:x64-linux@3.3
  * gtk3:x64-linux@3.24.43#1
  * harfbuzz[core,freetype]:x64-linux@11.3.3
    jxrlib:x64-linux@2019.10.9#7
    libarchive:x64-linux@3.7.7
  * libcap:x64-linux@2.73#1
  * libepoxy:x64-linux@1.5.10#2
  * libexif:x64-linux@0.6.25
  * libffi:x64-linux@3.5.2
    libgdiplus:x64-linux@5.6.1#4
  * libiconv:x64-linux@1.18#1
    libjpeg-turbo:x64-linux@3.1.1
  * liblzma:x64-linux@5.8.1
  * libmount:x64-linux@2.40
  * libogg:x64-linux@1.3.6#1
  * libpng:x64-linux@1.6.50
  * libsystemd:x64-linux@257.8
  * libuuid:x64-linux@1.0.3#15
  * libuv:x64-linux@1.51.0
    libvorbis:x64-linux@1.3.7#4
    libwebp[core,simd,nearlossless,libwebpmux]:x64-linux@1.6.0#1
  * libwebsockets:x64-linux@4.4.1
  * libxcrypt:x64-linux@4.4.38#1
  * libxml2[core,zlib,iconv]:x64-linux@2.14.5#1
    lz4:x64-linux@1.10.0
    oniguruma:x64-linux@6.9.10
    openal-soft:x64-linux@1.24.3#1
    opencv4[core,openmp]:x64-linux@4.7.0#6
  * opengl:x64-linux@2022-12-04#3
  * opengl-registry:x64-linux@2024-02-10#1
  * openssl:x64-linux@3.5.2
  * opus:x64-linux@1.5.2
    opusfile:x64-linux@0.12+20221121#1
  * pango:x64-linux@1.56.1#2
  * pcre2[core,platform-default-features,jit]:x64-linux@10.46
  * pixman:x64-linux@0.44.2
  * pkgconf:x64-linux@2.5.1#1
  * pthread:x64-linux@3.0.0#2
  * pthreads:x64-linux@3.0.0#14
    sdl2:x64-linux@2.32.10
    spdlog:x64-linux@1.15.3
  * sqlite3[core,json1]:x64-linux@3.50.4
  * tiff[core,zip,lzma,jpeg]:x64-linux@4.7.0
    uchardet:x64-linux@0.0.8
    unrar:x64-linux@6.0.7#1
  * vcpkg-boost:x64-linux@2025-03-29
    vcpkg-cmake:x64-linux@2024-04-23
  * vcpkg-cmake-config:x64-linux@2024-05-23
  * vcpkg-cmake-get-vars:x64-linux@2025-05-29
  * vcpkg-get-python-packages:x64-linux@2025-04-05
  * vcpkg-make:x64-linux@2025-08-21
  * vcpkg-pkgconfig-get-modules:x64-linux@2024-04-03
  * vcpkg-tool-meson:x64-linux@1.9.0
  * zlib:x64-linux@1.3.1
    zstd:x64-linux@1.5.7
7zip provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(7zip CONFIG REQUIRED)
  target_link_libraries(main PRIVATE 7zip::7zip)

argparse provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(argparse CONFIG REQUIRED)
  target_link_libraries(main PRIVATE argparse::argparse)

zstd provides CMake targets:

  find_package(zstd CONFIG REQUIRED)
  target_link_libraries(main PRIVATE zstd::libzstd)

The package boost-iostreams is compatible with built-in CMake targets of FindBoost.cmake:

    find_package(Boost REQUIRED COMPONENTS iostreams)
    target_link_libraries(main PRIVATE Boost::iostreams)

or the generated cmake configs via:

    find_package( REQUIRED CONFIG)
    target_link_libraries(main PRIVATE Boost::iostreams)

The package boost-locale is compatible with built-in CMake targets of FindBoost.cmake:

    find_package(Boost REQUIRED COMPONENTS locale)
    target_link_libraries(main PRIVATE Boost::locale)

or the generated cmake configs via:

    find_package( REQUIRED CONFIG)
    target_link_libraries(main PRIVATE Boost::locale)

The package boost-phoenix is compatible with built-in CMake targets of FindBoost.cmake:

    find_package(Boost REQUIRED COMPONENTS phoenix)
    target_link_libraries(main PRIVATE Boost::phoenix)

or the generated cmake configs via:

    find_package( REQUIRED CONFIG)
    target_link_libraries(main PRIVATE Boost::phoenix)

The package boost-spirit is compatible with built-in CMake targets of FindBoost.cmake:

    find_package(Boost REQUIRED COMPONENTS spirit)
    target_link_libraries(main PRIVATE Boost::spirit)

or the generated cmake configs via:

    find_package( REQUIRED CONFIG)
    target_link_libraries(main PRIVATE Boost::spirit)

bullet3 provides CMake targets:

  find_package(Bullet CONFIG REQUIRED)
  # specific set: BulletSoftBody, BulletDynamics, BulletInverseDynamics,
  #               BulletCollision, Bullet3Common, LinearMath
  target_link_libraries(main PRIVATE ${BULLET_LIBRARIES})
  # individual imported targets, e.g. for Bullet 3 libs
  target_link_libraries(main PRIVATE Bullet3Dynamics)

bullet3 provides pkg-config modules:

  # specific set: BulletSoftBody, BulletDynamics, BulletCollision, LinearMath
  bullet

catch2 provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(Catch2 CONFIG REQUIRED)
  target_link_libraries(main PRIVATE Catch2::Catch2 Catch2::Catch2WithMain)

catch2 provides pkg-config modules:

  # A modern, C++-native test framework for C++14 and above (links in default main)
  catch2-with-main

  # A modern, C++-native, test framework for C++14 and above
  catch2

libjpeg-turbo is compatible with built-in implementation-agnostic CMake targets:

    find_package(JPEG REQUIRED)
    target_link_libraries(main PRIVATE JPEG::JPEG)

libjpeg-turbo provides CMake targets for the TurboJPEG C API:

    find_package(libjpeg-turbo CONFIG REQUIRED)
    target_link_libraries(main PRIVATE $&lt;IF:$&lt;TARGET_EXISTS:libjpeg-turbo::turbojpeg&gt;,libjpeg-turbo::turbojpeg,libjpeg-turbo::turbojpeg-static&gt;)

libwebp provides CMake targets:

    find_package(WebP CONFIG REQUIRED)
    # basic usage
    target_link_libraries(main PRIVATE WebP::webp WebP::webpdecoder WebP::webpdemux)
    # for manipulating the WebP graphics format container (port feature libwebpmux)
    target_link_libraries(main PRIVATE WebP::libwebpmux)
    # for sharp RGB to YUV conversion
    target_link_libraries(main PRIVATE WebP::sharpyuv)

lz4 provides CMake targets:

  find_package(lz4 CONFIG REQUIRED)
  target_link_libraries(main PRIVATE lz4::lz4)

lz4 provides pkg-config modules:

  liblz4

glfw3 provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(glfw3 CONFIG REQUIRED)
  target_link_libraries(main PRIVATE glfw)

glfw3 provides pkg-config modules:

  # A multi-platform library for OpenGL, window and input
  glfw3

cocos2dx provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(cocos2dx CONFIG REQUIRED)
  # note: 8 additional targets are not displayed.
  target_link_libraries(main PRIVATE cocos2dx::cocos2d cocos2dx::ext_md5 cocos2dx::external cocos2dx::ext_unzip)

To use ffmpeg add the following to your CMake project:

    find_package(FFMPEG REQUIRED)
    target_include_directories(main PRIVATE ${FFMPEG_INCLUDE_DIRS})
    target_link_directories(main PRIVATE ${FFMPEG_LIBRARIES})

The package fmt provides CMake targets:

    find_package(fmt CONFIG REQUIRED)
    target_link_libraries(main PRIVATE fmt::fmt)

    # Or use the header-only version
    find_package(fmt CONFIG REQUIRED)
    target_link_libraries(main PRIVATE fmt::fmt-header-only)

The package jxrlib provides CMake integration:

    find_package(JXR REQUIRED)
    target_include_directories(main PRIVATE ${JXR_INCLUDE_DIRS})
    target_link_libraries(main PRIVATE ${JXR_LIBRARIES})

libarchive is compatible with the CMake Find Module:

  find_package(LibArchive REQUIRED)
  target_link_libraries(main PRIVATE LibArchive::LibArchive) # since CMake 3.17

libarchive provides pkg-config modules:

  # library that can create and read several streaming archive formats
  libarchive

To use libgdiplus add the following to your CMake project:

    find_package(libgdiplus CONFIG REQUIRED)
    target_include_directories(main PRIVATE libgdiplus::libgdiplus)

The package libvorbis provides CMake targets:

    # Vorbis reference encoder and decoder, low-level API
    find_package(Vorbis CONFIG REQUIRED)
    target_link_libraries(main PRIVATE Vorbis::vorbis)

    # Audio stream decoding and basic manipulation, high-level API
    find_package(Vorbis CONFIG REQUIRED)
    target_link_libraries(main PRIVATE Vorbis::vorbisfile)

    # Convenience API for setting up an encoding environment
    find_package(Vorbis CONFIG REQUIRED)
    target_link_libraries(main PRIVATE Vorbis::vorbisenc)

oniguruma provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(oniguruma CONFIG REQUIRED)
  target_link_libraries(main PRIVATE oniguruma::onig)

oniguruma provides pkg-config modules:

  # Regular expression library
  oniguruma

openal-soft provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(OpenAL CONFIG REQUIRED)
  target_link_libraries(main PRIVATE OpenAL::OpenAL)

openal-soft provides pkg-config modules:

  # OpenAL is a cross-platform 3D audio API
  openal

If you do not install the meta-port *opencv*, the package opencv4 is compatible with CMake
if you set the OpenCV_DIR *before* the find_package call

    set(OpenCV_DIR &quot;${VCPKG_INSTALLED_DIR}/x64-linux/share/opencv4&quot;)
    find_package(OpenCV REQUIRED)

The package opusfile provides CMake targets:

    find_package(OpusFile CONFIG REQUIRED)
    target_link_libraries(main PRIVATE OpusFile::opusfile)

    # To use the opusurl API
    target_link_libraries(main PRIVATE OpusFile::opusurl)

sdl2 provides CMake targets:

    find_package(SDL2 CONFIG REQUIRED)
    target_link_libraries(main
        PRIVATE
        $&lt;TARGET_NAME_IF_EXISTS:SDL2::SDL2main&gt;
        $&lt;IF:$&lt;TARGET_EXISTS:SDL2::SDL2&gt;,SDL2::SDL2,SDL2::SDL2-static&gt;
    )

The package spdlog provides CMake targets:

    find_package(spdlog CONFIG REQUIRED)
    target_link_libraries(main PRIVATE spdlog::spdlog)

    # Or use the header-only version
    find_package(spdlog CONFIG REQUIRED)
    target_link_libraries(main PRIVATE spdlog::spdlog_header_only)

uchardet provides CMake targets:

  # this is heuristically generated, and may not be correct
  find_package(uchardet CONFIG REQUIRED)
  target_link_libraries(main PRIVATE uchardet::libuchardet)

uchardet provides pkg-config modules:

  # An encoding detector library ported from Mozilla
  uchardet

unrar is compatible with the CMake Find Module:

  find_package(unrar CONFIG REQUIRED)
  target_link_libraries(main PRIVATE unrar::unrar)
All requested installations completed successfully in: 790 us
-- Running vcpkg install - done
&apos;/usr/bin/bison&apos; &apos;/home/zhangjc/Code/krkr2/cpp/core/tjs2/bison/tjs.y&apos;
&apos;/usr/bin/bison&apos; &apos;/home/zhangjc/Code/krkr2/cpp/core/tjs2/bison/tjsdate.y&apos;
&apos;/usr/bin/bison&apos; &apos;/home/zhangjc/Code/krkr2/cpp/core/tjs2/bison/tjspp.y&apos;
&apos;/usr/bin/python3&apos; &apos;create_world_map.py&apos; &apos;/home/zhangjc/Code/krkr2/out/linux/debug/cpp/core/tjs2/gen/tjsDateWordMap.inc&apos;
create file: /home/zhangjc/Code/krkr2/out/linux/debug/cpp/core/tjs2/gen/tjsDateWordMap.inc
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found version &quot;3.5.2&quot;)  
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found suitable version &quot;3.5.2&quot;, minimum required is &quot;3&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found suitable version &quot;1.3.1&quot;, minimum required is &quot;1&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found version &quot;1.3.1&quot;)  
-- The following ICU libraries were not found:
--   uc (required)
--   i18n (required)
-- Failed to find all ICU components (missing: ICU_INCLUDE_DIR ICU_LIBRARY _ICU_REQUIRED_LIBS_FOUND) 
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found version &quot;3.5.2&quot;)  
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found suitable version &quot;3.5.2&quot;, minimum required is &quot;3&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found suitable version &quot;1.3.1&quot;, minimum required is &quot;1&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found version &quot;1.3.1&quot;)  
-- The following ICU libraries were not found:
--   uc (required)
--   i18n (required)
-- Failed to find all ICU components (missing: ICU_INCLUDE_DIR ICU_LIBRARY _ICU_REQUIRED_LIBS_FOUND) 
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found version &quot;3.5.2&quot;)  
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found suitable version &quot;3.5.2&quot;, minimum required is &quot;3&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found suitable version &quot;1.3.1&quot;, minimum required is &quot;1&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found version &quot;1.3.1&quot;)  
-- The following ICU libraries were not found:
--   uc (required)
--   i18n (required)
-- Failed to find all ICU components (missing: ICU_INCLUDE_DIR ICU_LIBRARY _ICU_REQUIRED_LIBS_FOUND) 
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found version &quot;3.5.2&quot;)  
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found suitable version &quot;3.5.2&quot;, minimum required is &quot;3&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found suitable version &quot;1.3.1&quot;, minimum required is &quot;1&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found version &quot;1.3.1&quot;)  
-- The following ICU libraries were not found:
--   uc (required)
--   i18n (required)
-- Failed to find all ICU components (missing: ICU_INCLUDE_DIR ICU_LIBRARY _ICU_REQUIRED_LIBS_FOUND) 
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found version &quot;3.5.2&quot;)  
-- Found OpenSSL: /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libcrypto.a (found suitable version &quot;3.5.2&quot;, minimum required is &quot;3&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found suitable version &quot;1.3.1&quot;, minimum required is &quot;1&quot;)  
-- Found ZLIB: optimized;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/libz.a;debug;/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/debug/lib/libz.a (found version &quot;1.3.1&quot;)  
-- The following ICU libraries were not found:
--   uc (required)
--   i18n (required)
-- Failed to find all ICU components (missing: ICU_INCLUDE_DIR ICU_LIBRARY _ICU_REQUIRED_LIBS_FOUND) 
-- Configuring done (2.8s)
-- Generating done (0.1s)
-- Build files have been written to: /home/zhangjc/Code/krkr2/out/linux/debug
[1/72] cd /home/zhangjc/Code/krkr2/out/linux/debug &amp;&amp; /usr/bin/cmake -E echo Copying\ resources\ for\ krkr2\ ...
Copying resources for krkr2 ...
[2/72] Running utility command for SYNC_RESOURCE-krkr2
    copying to /home/zhangjc/Code/krkr2/out/linux/debug/bin/krkr2/Resources
[25/72] Building CXX object tests/unit-tests/plugins/CMakeFiles/psbfile-dll.dir/__/__/__/cpp/plugins/win32dialog.cpp.o
In file included from /home/zhangjc/Code/krkr2/cpp/plugins/win32dialog.cpp:2:
/home/zhangjc/Code/krkr2/cpp/core/plugin/ncbind.hpp: In static member function ‘static ncbTypeConvertor::Conversion&lt;FROM, TO&gt;::OK ncbTypeConvertor::Conversion&lt;FROM, TO&gt;::check(TO)’:
/home/zhangjc/Code/krkr2/cpp/core/plugin/ncbind.hpp:244:38: warning: no return statement in function returning non-void [-Wreturn-type]
  244 |                 static OK check(TO) {};
      |                                      ^
[27/72] Linking CXX executable tests/unit-tests/core/movie/ffmpeg
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/debug/lib/libjpegxrd.a(strenc.c.o): in function `StrIOEncInit&apos;:
/home/zhangjc/Code/vcpkg/buildtrees/jxrlib/src/0dd9dbbdb4-ff67a15ca3.clean/image/encode/strenc.c:485:(.text+0x1540): 警告： the use of `tmpnam&apos; is dangerous, better use `mkstemp&apos;
[28/72] Linking CXX executable tests/unit-tests/core/tjs2/tjs
<font color="#CC0000">FAILED: </font>tests/unit-tests/core/tjs2/tjs tests/unit-tests/core/tjs2/tjs-b12d07c_tests.cmake /home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjs-b12d07c_tests.cmake 
: &amp;&amp; /usr/bin/c++ -g  tests/unit-tests/core/tjs2/CMakeFiles/tjs.dir/tjs.cpp.o tests/unit-tests/core/tjs2/CMakeFiles/tjs.dir/main.cpp.o -o tests/unit-tests/core/tjs2/tjs -L/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/pkgconfig/../../lib -Wl,-rpath,/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/pkgconfig/../../lib:/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit  vcpkg_installed/x64-linux/debug/lib/libCatch2d.a  cpp/core/base/libcore_base_module.a  cpp/core/environ/libcore_environ_module.a  cpp/core/plugin/libcore_plugin_module.a  cpp/core/movie/libcore_movie_module.a  cpp/core/sound/libcore_sound_module.a  cpp/core/visual/libcore_visual_module.a  cpp/core/utils/libcore_utils_module.a  cpp/core/base/libcore_base_module.a  cpp/core/environ/libcore_environ_module.a  cpp/core/plugin/libcore_plugin_module.a  cpp/core/movie/libcore_movie_module.a  cpp/core/sound/libcore_sound_module.a  cpp/core/visual/libcore_visual_module.a  cpp/core/utils/libcore_utils_module.a  cpp/core/extension/libcore_extension_module.a  vcpkg_installed/x64-linux/debug/lib/libuchardet.a  vcpkg_installed/x64-linux/debug/lib/libunrar.a  vcpkg_installed/x64-linux/debug/lib/libarchive.a  vcpkg_installed/x64-linux/debug/lib/libzstd.a  vcpkg_installed/x64-linux/debug/lib/libSDL2maind.a  vcpkg_installed/x64-linux/debug/lib/libSDL2d.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/lib7zip.a  cpp/external/minizip/libminizip.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libvorbisfile.a  vcpkg_installed/x64-linux/debug/lib/libvorbisenc.a  vcpkg_installed/x64-linux/debug/lib/libvorbis.a  vcpkg_installed/x64-linux/debug/lib/libopusfile.a  vcpkg_installed/x64-linux/debug/lib/libopus.a  vcpkg_installed/x64-linux/debug/lib/libogg.a  vcpkg_installed/x64-linux/debug/lib/libopenal.a  vcpkg_installed/x64-linux/debug/lib/libfmtd.a  cpp/external/libbpg/liblibbpg.a  vcpkg_installed/x64-linux/debug/lib/libavfilter.a  vcpkg_installed/x64-linux/debug/lib/libavformat.a  vcpkg_installed/x64-linux/debug/lib/libavcodec.a  vcpkg_installed/x64-linux/debug/lib/libswresample.a  vcpkg_installed/x64-linux/debug/lib/libswscale.a  vcpkg_installed/x64-linux/debug/lib/libavutil.a  /usr/lib/x86_64-linux-gnu/libxcb.so  /usr/lib/x86_64-linux-gnu/libXau.so  /usr/lib/x86_64-linux-gnu/libXdmcp.so  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/lib/libbz2.a  -pthread  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libjxrglued.a  vcpkg_installed/x64-linux/debug/lib/libjpegxrd.a  vcpkg_installed/x64-linux/debug/lib/libturbojpeg.a  vcpkg_installed/x64-linux/debug/lib/libopencv_imgproc4d.a  vcpkg_installed/x64-linux/debug/lib/libopencv_core4d.a  vcpkg_installed/x64-linux/debug/lib/liblz4d.a  cpp/core/tjs2/libtjs2.a  vcpkg_installed/x64-linux/debug/lib/libboost_locale.a  vcpkg_installed/x64-linux/debug/lib/libboost_charconv.a  -lquadmath  vcpkg_installed/x64-linux/debug/lib/libboost_thread.a  vcpkg_installed/x64-linux/debug/lib/libboost_atomic.a  vcpkg_installed/x64-linux/debug/lib/libboost_chrono.a  vcpkg_installed/x64-linux/debug/lib/libboost_date_time.a  vcpkg_installed/x64-linux/debug/lib/libboost_container.a  vcpkg_installed/x64-linux/debug/lib/libboost_system.a  vcpkg_installed/x64-linux/debug/lib/libspdlogd.a  vcpkg_installed/x64-linux/debug/lib/libfmtd.a  vcpkg_installed/x64-linux/debug/lib/libonig.a  /usr/lib/gcc/x86_64-linux-gnu/13/libgomp.so  /usr/lib/x86_64-linux-gnu/libpthread.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  -lpthread  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  /usr/lib/x86_64-linux-gnu/librt.a  -lm  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  -lX11  -lXi  -lXrandr  -lXxf86vm  -lXinerama  -lXcursor  -lgtk-3  -lgdk-3  -lpangocairo-1.0  -lXfixes  -lcairo-gobject  -lgdk_pixbuf-2.0  -ljpeg  -llzma  -latk-bridge-2.0  -latspi  -ldbus-1  -lXtst  -latk-1.0  -lgmodule-2.0  -lepoxy  -lpangoft2-1.0  -lpango-1.0  -lfribidi  -lharfbuzz  -lstdc++  -lcairo  -lfontconfig  -lexpat  -lbrotlidec  -lbrotlicommon  -lXext  -lXrender  -lpixman-1  -lgio-2.0  -lgobject-2.0  -lffi  -lX11  -lXi  -lXrandr  -lXxf86vm  -lXinerama  -lXcursor  -lgtk-3  -lgdk-3  -lpangocairo-1.0  -lXfixes  -lcairo-gobject  -lgdk_pixbuf-2.0  -ljpeg  -llzma  -latk-bridge-2.0  -latspi  -ldbus-1  -lXtst  -latk-1.0  -lgmodule-2.0  -lepoxy  -lpangoft2-1.0  -lpango-1.0  -lfribidi  -lharfbuzz  -lstdc++  -lcairo  -lfontconfig  -lexpat  -lbrotlidec  -lbrotlicommon  -lXext  -lXrender  -lpixman-1  -lgio-2.0  -lgobject-2.0  -lffi  -lrt  -lglib-2.0  -latomic  -lpcre2-8  -lz  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libbrotlidec.a  vcpkg_installed/x64-linux/debug/lib/libbrotlicommon.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  -lm  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGL.so  /usr/lib/x86_64-linux-gnu/libGLU.so  /usr/lib/x86_64-linux-gnu/libX11.so  /usr/lib/x86_64-linux-gnu/libXext.so  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  -ldl &amp;&amp; cd /home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2 &amp;&amp; /usr/bin/cmake -D TEST_TARGET=tjs -D TEST_EXECUTABLE=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjs -D TEST_EXECUTOR= -D TEST_WORKING_DIR=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2 -D TEST_SPEC= -D TEST_EXTRA_ARGS= -D &quot;TEST_PROPERTIES=SKIP_RETURN_CODE;4&quot; -D TEST_PREFIX= -D TEST_SUFFIX= -D TEST_LIST=tjs_TESTS -D TEST_REPORTER= -D TEST_OUTPUT_DIR= -D TEST_OUTPUT_PREFIX= -D TEST_OUTPUT_SUFFIX= -D TEST_DL_PATHS= -D TEST_DL_FRAMEWORK_PATHS= -D CTEST_FILE=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjs-b12d07c_tests.cmake -D ADD_TAGS_AS_LABELS=FALSE -P /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/share/catch2/CatchAddTests.cmake
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/debug/lib/libjpegxrd.a(strenc.c.o): in function `StrIOEncInit&apos;:
/home/zhangjc/Code/vcpkg/buildtrees/jxrlib/src/0dd9dbbdb4-ff67a15ca3.clean/image/encode/strenc.c:485:(.text+0x1540): 警告： the use of `tmpnam&apos; is dangerous, better use `mkstemp&apos;
/usr/bin/ld: cpp/core/movie/libcore_movie_module.a(KRMoviePlayer.cpp.o): in function `KRMovie::VideoPresentOverlay::PresentPicture(float)&apos;:
/home/zhangjc/Code/krkr2/cpp/core/movie/ffmpeg/KRMoviePlayer.cpp:275:(.text+0x1bb0): undefined reference to `TVPYUVSprite::create()&apos;
/usr/bin/ld: /home/zhangjc/Code/krkr2/cpp/core/movie/ffmpeg/KRMoviePlayer.cpp:280:(.text+0x1ceb): undefined reference to `TVPYUVSprite::updateTextureData(void const*, int, int, void const*, int, int, void const*, int, int)&apos;
collect2: error: ld returned 1 exit status
[29/72] Linking CXX executable tests/unit-tests/core/tjs2/tjsString
<font color="#CC0000">FAILED: </font>tests/unit-tests/core/tjs2/tjsString tests/unit-tests/core/tjs2/tjsString-b12d07c_tests.cmake /home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjsString-b12d07c_tests.cmake 
: &amp;&amp; /usr/bin/c++ -g  tests/unit-tests/core/tjs2/CMakeFiles/tjsString.dir/tjsString.cpp.o tests/unit-tests/core/tjs2/CMakeFiles/tjsString.dir/main.cpp.o -o tests/unit-tests/core/tjs2/tjsString -L/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/pkgconfig/../../lib -Wl,-rpath,/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/lib/pkgconfig/../../lib:/home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit  vcpkg_installed/x64-linux/debug/lib/libCatch2d.a  cpp/core/base/libcore_base_module.a  cpp/core/environ/libcore_environ_module.a  cpp/core/plugin/libcore_plugin_module.a  cpp/core/movie/libcore_movie_module.a  cpp/core/sound/libcore_sound_module.a  cpp/core/visual/libcore_visual_module.a  cpp/core/utils/libcore_utils_module.a  cpp/core/base/libcore_base_module.a  cpp/core/environ/libcore_environ_module.a  cpp/core/plugin/libcore_plugin_module.a  cpp/core/movie/libcore_movie_module.a  cpp/core/sound/libcore_sound_module.a  cpp/core/visual/libcore_visual_module.a  cpp/core/utils/libcore_utils_module.a  cpp/core/extension/libcore_extension_module.a  vcpkg_installed/x64-linux/debug/lib/libuchardet.a  vcpkg_installed/x64-linux/debug/lib/libunrar.a  vcpkg_installed/x64-linux/debug/lib/libarchive.a  vcpkg_installed/x64-linux/debug/lib/libzstd.a  vcpkg_installed/x64-linux/debug/lib/libSDL2maind.a  vcpkg_installed/x64-linux/debug/lib/libSDL2d.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/lib7zip.a  cpp/external/minizip/libminizip.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libvorbisfile.a  vcpkg_installed/x64-linux/debug/lib/libvorbisenc.a  vcpkg_installed/x64-linux/debug/lib/libvorbis.a  vcpkg_installed/x64-linux/debug/lib/libopusfile.a  vcpkg_installed/x64-linux/debug/lib/libopus.a  vcpkg_installed/x64-linux/debug/lib/libogg.a  vcpkg_installed/x64-linux/debug/lib/libopenal.a  vcpkg_installed/x64-linux/debug/lib/libfmtd.a  cpp/external/libbpg/liblibbpg.a  vcpkg_installed/x64-linux/debug/lib/libavfilter.a  vcpkg_installed/x64-linux/debug/lib/libavformat.a  vcpkg_installed/x64-linux/debug/lib/libavcodec.a  vcpkg_installed/x64-linux/debug/lib/libswresample.a  vcpkg_installed/x64-linux/debug/lib/libswscale.a  vcpkg_installed/x64-linux/debug/lib/libavutil.a  /usr/lib/x86_64-linux-gnu/libxcb.so  /usr/lib/x86_64-linux-gnu/libXau.so  /usr/lib/x86_64-linux-gnu/libXdmcp.so  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/lib/libbz2.a  -pthread  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  vcpkg_installed/x64-linux/debug/lib/libjxrglued.a  vcpkg_installed/x64-linux/debug/lib/libjpegxrd.a  vcpkg_installed/x64-linux/debug/lib/libturbojpeg.a  vcpkg_installed/x64-linux/debug/lib/libopencv_imgproc4d.a  vcpkg_installed/x64-linux/debug/lib/libopencv_core4d.a  vcpkg_installed/x64-linux/debug/lib/liblz4d.a  cpp/core/tjs2/libtjs2.a  vcpkg_installed/x64-linux/debug/lib/libboost_locale.a  vcpkg_installed/x64-linux/debug/lib/libboost_charconv.a  -lquadmath  vcpkg_installed/x64-linux/debug/lib/libboost_thread.a  vcpkg_installed/x64-linux/debug/lib/libboost_atomic.a  vcpkg_installed/x64-linux/debug/lib/libboost_chrono.a  vcpkg_installed/x64-linux/debug/lib/libboost_date_time.a  vcpkg_installed/x64-linux/debug/lib/libboost_container.a  vcpkg_installed/x64-linux/debug/lib/libboost_system.a  vcpkg_installed/x64-linux/debug/lib/libspdlogd.a  vcpkg_installed/x64-linux/debug/lib/libfmtd.a  vcpkg_installed/x64-linux/debug/lib/libonig.a  /usr/lib/gcc/x86_64-linux-gnu/13/libgomp.so  /usr/lib/x86_64-linux-gnu/libpthread.a  vcpkg_installed/x64-linux/debug/lib/libcocos2d.a  vcpkg_installed/x64-linux/debug/lib/libbox2dd.a  vcpkg_installed/x64-linux/debug/lib/libchipmunk.a  vcpkg_installed/x64-linux/debug/lib/libext_recast.a  vcpkg_installed/x64-linux/debug/lib/libBulletDynamics.a  vcpkg_installed/x64-linux/debug/lib/libBulletCollision.a  vcpkg_installed/x64-linux/debug/lib/libLinearMath.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  -lpthread  vcpkg_installed/x64-linux/debug/lib/libwebpdecoder.a  vcpkg_installed/x64-linux/debug/lib/libwebpdemux.a  vcpkg_installed/x64-linux/debug/lib/libwebp.a  vcpkg_installed/x64-linux/debug/lib/libsharpyuv.a  vcpkg_installed/x64-linux/debug/lib/libwebsockets.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/debug/lib/libuv.a  vcpkg_installed/x64-linux/debug/lib/libext_tinyxml2.a  vcpkg_installed/x64-linux/debug/lib/libext_xxhash.a  vcpkg_installed/x64-linux/debug/lib/libext_xxtea.a  vcpkg_installed/x64-linux/debug/lib/libext_clipper.a  vcpkg_installed/x64-linux/debug/lib/libext_edtaa3func.a  vcpkg_installed/x64-linux/debug/lib/libext_convertUTF.a  vcpkg_installed/x64-linux/debug/lib/libext_poly2tri.a  vcpkg_installed/x64-linux/debug/lib/libext_md5.a  vcpkg_installed/x64-linux/debug/lib/libcurl-d.a  vcpkg_installed/x64-linux/debug/lib/libssl.a  vcpkg_installed/x64-linux/debug/lib/libcrypto.a  vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so  vcpkg_installed/x64-linux/debug/lib/libglfw3.a  /usr/lib/x86_64-linux-gnu/librt.a  -lm  vcpkg_installed/x64-linux/debug/lib/libext_unzip.a  vcpkg_installed/x64-linux/debug/lib/libfontconfig.a  vcpkg_installed/x64-linux/debug/lib/libexpat.a  -lX11  -lXi  -lXrandr  -lXxf86vm  -lXinerama  -lXcursor  -lgtk-3  -lgdk-3  -lpangocairo-1.0  -lXfixes  -lcairo-gobject  -lgdk_pixbuf-2.0  -ljpeg  -llzma  -latk-bridge-2.0  -latspi  -ldbus-1  -lXtst  -latk-1.0  -lgmodule-2.0  -lepoxy  -lpangoft2-1.0  -lpango-1.0  -lfribidi  -lharfbuzz  -lstdc++  -lcairo  -lfontconfig  -lexpat  -lbrotlidec  -lbrotlicommon  -lXext  -lXrender  -lpixman-1  -lgio-2.0  -lgobject-2.0  -lffi  -lX11  -lXi  -lXrandr  -lXxf86vm  -lXinerama  -lXcursor  -lgtk-3  -lgdk-3  -lpangocairo-1.0  -lXfixes  -lcairo-gobject  -lgdk_pixbuf-2.0  -ljpeg  -llzma  -latk-bridge-2.0  -latspi  -ldbus-1  -lXtst  -latk-1.0  -lgmodule-2.0  -lepoxy  -lpangoft2-1.0  -lpango-1.0  -lfribidi  -lharfbuzz  -lstdc++  -lcairo  -lfontconfig  -lexpat  -lbrotlidec  -lbrotlicommon  -lXext  -lXrender  -lpixman-1  -lgio-2.0  -lgobject-2.0  -lffi  -lrt  -lglib-2.0  -latomic  -lpcre2-8  -lz  vcpkg_installed/x64-linux/debug/lib/libtiffd.a  vcpkg_installed/x64-linux/debug/lib/libjpeg.a  vcpkg_installed/x64-linux/debug/lib/liblzma.a  vcpkg_installed/x64-linux/debug/lib/libfreetyped.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libbrotlidec.a  vcpkg_installed/x64-linux/debug/lib/libbrotlicommon.a  vcpkg_installed/x64-linux/debug/lib/libbz2d.a  vcpkg_installed/x64-linux/debug/lib/libpng16d.a  -lm  vcpkg_installed/x64-linux/debug/lib/libz.a  vcpkg_installed/x64-linux/debug/lib/libGLEWd.a  /usr/lib/x86_64-linux-gnu/libGL.so  /usr/lib/x86_64-linux-gnu/libGLU.so  /usr/lib/x86_64-linux-gnu/libX11.so  /usr/lib/x86_64-linux-gnu/libXext.so  /usr/lib/x86_64-linux-gnu/libGLX.so  /usr/lib/x86_64-linux-gnu/libOpenGL.so  vcpkg_installed/x64-linux/debug/lib/libsqlite3.a  -ldl &amp;&amp; cd /home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2 &amp;&amp; /usr/bin/cmake -D TEST_TARGET=tjsString -D TEST_EXECUTABLE=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjsString -D TEST_EXECUTOR= -D TEST_WORKING_DIR=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2 -D TEST_SPEC= -D TEST_EXTRA_ARGS= -D &quot;TEST_PROPERTIES=SKIP_RETURN_CODE;4&quot; -D TEST_PREFIX= -D TEST_SUFFIX= -D TEST_LIST=tjsString_TESTS -D TEST_REPORTER= -D TEST_OUTPUT_DIR= -D TEST_OUTPUT_PREFIX= -D TEST_OUTPUT_SUFFIX= -D TEST_DL_PATHS= -D TEST_DL_FRAMEWORK_PATHS= -D CTEST_FILE=/home/zhangjc/Code/krkr2/out/linux/debug/tests/unit-tests/core/tjs2/tjsString-b12d07c_tests.cmake -D ADD_TAGS_AS_LABELS=FALSE -P /home/zhangjc/Code/krkr2/out/linux/debug/vcpkg_installed/x64-linux/share/catch2/CatchAddTests.cmake
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: cpp/core/tjs2/libtjs2.a(tjs.cpp.o): in function `TJS::tTJSBinaryStream::ReadBuffer(void*, unsigned int)&apos;:
/home/zhangjc/Code/krkr2/cpp/core/tjs2/tjs.cpp:667:(.text+0x2d5e): undefined reference to `TVPGetMessageByLocale(std::__cxx11::basic_string&lt;char, std::char_traits&lt;char&gt;, std::allocator&lt;char&gt; &gt; const&amp;)&apos;
collect2: error: ld returned 1 exit status
[30/72] Linking CXX executable bin/krkr2/krkr2
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 2 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 3 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/share/cocos2dx/linux-specific/fmod/prebuilt/64-bit/libfmod.so: .dynsym local symbol at index 4 (&gt;= sh_info of 2)
/usr/bin/ld: vcpkg_installed/x64-linux/debug/lib/libjpegxrd.a(strenc.c.o): in function `StrIOEncInit&apos;:
/home/zhangjc/Code/vcpkg/buildtrees/jxrlib/src/0dd9dbbdb4-ff67a15ca3.clean/image/encode/strenc.c:485:(.text+0x1540): 警告： the use of `tmpnam&apos; is dangerous, better use `mkstemp&apos;
ninja: build stopped: subcommand failed.
</pre>
