## Overview ##

Lua for Windows is a 'batteries included environment' for the Lua scripting language on Windows.

Lua for Windows (LfW) combines Lua binaries, Lua libraries with a Lua-capable editor in a single install package for the Microsoft Windows operating system. LfW contains everything you need to write, run and debug Lua scripts on Windows. A wide variety of libraries and examples are included that are ready to use with Microsoft Windows. LfW runs on Windows 2000 and newer versions of Windows. Lua and its associated libraries are also available for other operating systems, so most scripts will be automatically cross-platform.


## Download ##

Download Lua For Windows installer from [GitHub](https://github.com/rjpcomputing/luaforwindows/releases)

## Install Notes ##

Lua for Windows installs Lua language, SciTE based Lua IDE and Lua modules to the directory of you choice at install time. Lua for Windows and it's modules all depend on the MSVC++ 2005 runtime library. Lua for Windows install will automatically download this runtime and install it for you if you don't have runtime installed on your computer. The runtime is contained in the file [vcredist\_x86.exe](https://github.com/rjpcomputing/luaforwindows/releases/download/vc-runtime/vcredist_x86.4053.exe), if you don't want the runtime to download during installation time (for offline instalation), just place the [vcredist\_86.exe](https://github.com/rjpcomputing/luaforwindows/releases/download/vc-runtime/vcredist_x86.4053.exe) in same directory as Lua for Windows install exe.


## LfW Components ##

Installer
Lua Interpreter,
Lua Reference Manual,
Quick Lua Tour Sample,
Examples directory,
Libraries with documentation.
Lua Compiler (luac)
Text Editors (SciTE and I think maybe wxLua editors too)
C header files/libraries/etc. for building C module


## Libraries included ##
|**Library**|**Version**|**Description**|
|:----------|:----------|:--------------|
|[Alien](https://github.com/mascarenhas/alien)|0.5.0|Provides access to functions in an unknown or new .dll.|
|[IUP](https://www.tecgraf.puc-rio.br/iup/)|3.5.0|Light Portable Graphical User Interface library.|
|[CD](https://www.tecgraf.puc-rio.br/cd/)|5.4.1|Canvas Draw: A platform-independent graphic library.|
|[IM](https://www.tecgraf.puc-rio.br/im/)|3.6.3|A toolkit for Digital Imaging.|
|Ex|Jan 07|Adds environment, file system, I/O (Locking and pipes), and process control.|
|[LPeg](https://www.inf.puc-rio.br/~roberto/lpeg/lpeg.html)|0.9|Pattern-matching library based on Parsing Expression Grammars (PEGs).|
|[Lua-GD](https://github.com/ittner/lua-gd)|2.9.33r2|Image manipulation library based on Thomas Boutell’s GD library.|
|[LuaCOM](https://web.tecgraf.puc-rio.br/~rcerq/luacom/)|1.4|Enable use & implementation of Microsoft’s Component Object Model.|
|[LuaCURL](https://github.com/Lua-cURL/Lua-cURLv3)|1.0|Interface to Internet browsing capabilities based on the cURL library.|
|[Date](https://github.com/Tieske/date)|2 |Date and Time library for Lua.|
|[LuaDoc](https://github.com/lunarmodules/luadoc)|3.01|Documentation tool for Lua source code.|
|[LuaExpat](https://github.com/lunarmodules/luaexpat)|1.1.0|Lua interface to XML Expat parsing library.|
|[LuaFileSystem](https://github.com/lunarmodules/luafilesystem)|1.4.2|Access the directory structure and file attributes.|
|[LuaLogging](https://github.com/lunarmodules/lualogging)|1.2.0|Logging features in Lua, based on log4j.|
|[LuaProfiler](https://github.com/lunarmodules/luaprofiler)|2.0.1|Time profiler designed to find bottlenecks in Lua programs.|
|[LuaSocket](https://github.com/lunarmodules/luasocket)|2.0.2|Lua interface to support HTTP,FTP,SMTP, MIME, URL & LTN12.|
|[LuaSQL](https://github.com/lunarmodules/luasql)|2.1.1|Lua interface for PostgreSQL, ODBC, MySQL, SQLite, Oracle, and ADO dbms.|
|[LuaUnit](https://github.com/luaforge/luaunit)|2.0|Testing framework for Lua.|
|[LuaZip](https://github.com/lunarmodules/luazip)|1.2.3|Read files from zip files.|
|[stdlib](https://github.com/lua-stdlib/lua-stdlib)|25|Library of modules for common programming tasks, including list, table and functional operations, regexps, objects, pretty-printing and getopt.|
|[lrexlib](https://github.com/rrthomas/lrexlib)|2.2|Regular expression library for Lua.|
|[MD5](https://github.com/lunarmodules/md5)|1.1.2|Basic cryptographic facilities for Lua.|
|[Copas](https://github.com/lunarmodules/copas)|1.1.5|Dispatcher based on coroutines that can be used by TCP/IP servers.|
|[Coxpcall](https://github.com/keplerproject/coxpcall)|1.13|Encapsulates the protected calls with a coroutine based loop, so errors can be dealed without the usual pcall/xpcall issues with coroutines.|
|[Rings](https://github.com/keplerproject/rings)|1.2.2|Provides a way to create new Lua states from within Lua. It also offers a simple way to communicate between the creator ([LOOP](https://github.com/renatomaia/loop)) and the created (slave) states.|
|[LOOP](https://github.com/renatomaia/loop)|2.3 Beta|LOOP stands for Lua Object-Oriented Programming and is a set of packages for supporting different models of object-oriented programming in the Lua language.|
|[LuaTask](https://github.com/LuaDist/luatask)|1.6.4|Implements a concurrent and independent Lua execution environment model.|
|[LuaInterface](https://github.com/LuaDist/luainterface)|1.5.3|	Integration between the Lua language and Microsoft .NET platform's Common Language Runtime (CLR).|
|[wxLua](https://github.com/pkulchenko/wxlua)|2.8.10| Lua binding to the wxWidgets library.|
|[lpack](https://web.tecgraf.puc-rio.br/~lhf/ftp/lua/#lpack)|29 Jun 2007 19:27:20|Lua library for packing and unpacking binary data.|
|[VStruct](https://github.com/ToxicFrog/vstruct)|1.0.2|Provides functions for manipulating binary data.|
|[LuaBitOps](https://bitop.luajit.org/)|1.0.1| Lua BitOp is a C extension module for Lua 5.1 which adds bitwise operations on numbers.|
|[LuaXML](https://github.com/LuaDist/luaxml)|1.3|A module that maps between Lua and XML without much ado.|
|[Lanes](https://github.com/LuaLanes/lanes)|2.0.4|Provides the possibility to run multiple Lua states in parallel.|
|[MetaLua](https://github.com/fab13n/metalua)|0.5-rc1|A complete macro system with full compatibility with Lua 5.1 sources and bytecode: clean, elegant semantics and syntax, amazing expressive power, good performances, near-universal portability.|
|[LuaGL](https://luagl.wikidot.com/)|1.3|Provides access to all of the OpenGL functionality from Lua 5.x .|
|[Penlight](https://github.com/lunarmodules/Penlight)|1.3.2|Common lua code patterns for tables, arrays, strings, paths and directories, data, and functional programming.|
|[lbase64](https://web.tecgraf.puc-rio.br/~lhf/ftp/lua/)|for Lua 5.1|A base64 library for Lua.|
|[gzio](https://github.com/jmaygarden/gzio)|0.9.0|The Lua gzip file I/O module emulates the standard I/O module, but operates on compressed gzip format files.|
|[LuaRS232](https://github.com/ynezz/librs232)|1.0.0| RS232 serial communications library|
|[LeMock](https://github.com/LuaDist/lemock)|0.6|  Mock creation module intended for use together with a unit test framework such as lunit or lunity.|
|[LuaRocks](https://luarocks.org)|2.0.2|  A deployment and management system for Lua modules.|
|[Oil](https://github.com/renatomaia/oil)|0.4-beta|  It is a simple, efficient and flexible object request broker written in the Lua language.|
|[LuaJSON](https://github.com/harningt/luajson)|1.2.2| JSON parser/encoder for Lua Parses JSON using LPEG for speed and flexibility. Depending on parser/encoder options, various values are preserved as best as possible.|
|[SubLua](https://sourceforge.net/projects/subcpp/)|1.8.10-35352|  Subversion binding.|
|[30Log](https://github.com/Yonaba/30log)|1.0.0|  30 lines library for object orientation in Lua.|
|[Moses](https://yonaba.github.io/Moses)|1.4.0|  Utility library for functional programming in Lua.|
|[Binary-Heaps](https://github.com/Yonaba/Binary-Heaps)|1.5.1|  Implementation of binary heaps data structure in pure Lua.|
|[strictness](https://yonaba.github.io/strictness)|0.2.0|  Tracks accesses and assignments of undefined variables in Lua.|
|[delaunay](https://yonaba.github.io/delaunay/)|0.1.0|  Delaunay triangulation for convex polygon.|

## History ##

**5.1.3.12** 9/July/2008 - First release

**5.1.3.13** 16/July/2008 - Second release
  * New libs LOOPS, LuaTask, LuaInterface.
  * Add Lua headers and Lua lib needed for embedding Lua.

**5.1.3.15** 7/August/2008 - Third release
  * Added an environment variable called "LUA\_DEV" to help C module developers configure their build files. This allows for the paths to be common and easily added to the project settings. (e.g. $(LUA\_DEV)/include; $(LUA\_DEV)/lib)
  * Added the ability to download the 'vcredist\_x86.exe'.
  * Fixed Visual C++ 8.0 run-time problems. There now has to be a run-time for every dll loaded.
  * Removed 'msvcr80.dll' from the root application directory.
  * Updated the Visual C++ 8.0 run-time to SP1.
  * Updated StdLib to version 6.
  * Fixed missing Scite install issue with 5.1.3.14 release.

**5.1.4.17** 9/September/2008 - Fourth release.
  * Fixed the readyiss.bat file to work with the new 'lua' directory.
  * Added wxLua support.
  * Updated to Lua v5.1.4.
  * Changed the 'lualibs' to 'lua' to support the default locations.
  * Updated SciTE property file to make the help show up correctly.
  * Removed setting the LUA\_PATH and LUA\_CPATH environment variables.

**5.1.4.18** 11/September/2008 - Fifth release.
  * Updated Stdlib to version 8.
  * Updated the quickluatour.lua.
  * Updated the luaforwindows document.
  * Fixed LuaInterface module.

**5.1.4.19** 08/October/2008 - 6th release.
  * Release on  http://luaforwindows.googlecode.com/ to cover when LuaForge site was unavailable.

**5.1.4.20**  26/November/2008 - 7th release.
  * Added lpack (29 Jun 2007 19:27:20) module.
  * Added VStruct v 1.0 beta2 Lua module.
  * Added BitLib release 25 module.
  * Added LuaXML v1.3 module.
  * Updated IUP to version 2.7.
  * Updated CD to version 5.1.
  * Updated IM to version 3.4.

**5.1.4.21** 5/December/2008 - 8th release.
  * Fixed a SciTE bug when opening the Lua manual.
  * Added lExecutor. This is a wxLua application that allows users to run console Lua scripts in a simple GUI. Look at the documentation (<lFW root>\docs\lexecutor) for more information.
  * Added 'wildcard'.lexe files to run using lExecutor.
  * Associated 'wildcard'.lexe files to a custom icon.

**5.1.4.22** 12/January/2009- 9th release.
  * Added LuaBitOp v1.0.1 library.
  * Fixed a bug in lExecutor to properly pass file loading error to the user.
  * Fixed LuaDoc templates a bit for 'tables' and 'functions'.
  * Fixed !LuaXML so it actually works. Opps.
  * Updated Copas to version 1.1.4.
  * Updated IUP to version 2.7.1.
  * Updated CD to version 5.1.1.
  * Updated IM to version 3.4.1.
  * Removed BitLib. Use LuaBitOp instead.

**5.1.4.23** 06/Febuary/2009 - 10th release.
  * Added MetaLua v0.5-rc1.
  * Added the 'strict.lua' file shipped in the Lua in the 'etc' directory.
  * Added Lanes v2.0.3 library.
  * Updated LuaFileSystem to version 1.4.2.

**5.1.4.24** **rc1** 14/April/2009 - 11th release
  * Updated LPeg to version 0.9.
  * Updated Copas to version 1.1.5.
  * Updated the Lua executables so they run on Windows 64

**5.1.4.25** **rc2** 15/April/2009 - 12th release
  * Updated lua51.dll manifest to allow running on Windows 64.

**5.1.4.26** **rc3** 23/April/2009 - 13th release
  * Added an option to start the quickluatour.lua after installation completes.
  * Added a link to the lExecutor documentation in the start menu.
  * Now you can launch quickluatour.lua at the end of the installer
  * Updated luaforwindows.html to be the right version in the example.
  * Updated the LuaQuickTour thanks to Dirk Feytons.
  * Fixed SciTE saving a debugger file to the current running scripts directory. Now it saves it to your local temp directory.
  * Fixed SciTE toolbar icons being incorrect.

**5.1.4-27** **rc4** 27/April/2009 -14th release
  * Fixed SciTE debugger looking for the temp file in the %TMP% location.
  * Fixed debugging files with spaces in the filename.
  * Updated the IM, CD, and IUP examples.
  * Made SciTE use the lua5.1.dll.
  * Changed the version number to use a '-' as a build number of the LfW package.
  * Changed the installer display name to 'Lua For Windows'.

**5.1.4-28** 29/June/2009 - 15th release
  * Fixed SciTE debugger to allow it to debug modules in the same directory  as the file using the module.
  * Updated Stdlib to version 11.

**5.1.4-29** 03/Sept/2009 - 16th release
  * Added Penlight v0.7.2 Lua module.
  * Updated LuaCOM to version 1.4.
  * Updated LuaGL to version 1.3.
  * Updated VStruct to version 1.0.2.

**5.1.4-30** 10/Sept/2009 - 17th release
  * Added lbase64 module.
  * Added gzio module
  * Updated stdlib to Release 12.

**5.1.4-31** 07/Dec/2009 -  Internal only, not released
  * Added markdown v0.32 Lua module.
  * Fixed C Runtime Error R 6034. Problem 3.
  * Fixed LuaInterface manifest loading issue.
  * Updated luanet.dll to CoInitialize and search in the LUA\_CPATH.

**5.1.4-32** 12/March/2010 - 18th release
  * Added LuaRS232 v1.0.0
  * Added iLua.cmd to easily launch iLua. Also added it to the start menu.
  * Fixed SciTE to properly run interactive Lua session.
  * Updated the clidebugger to take the same paramaters to allow for debug level.
  * Updated Penlight to version 0.8.0.
  * Updated IUP to version 3.0.0.
  * Updated CD to version 5.3.0.
  * Updated IM to version 3.6.0.

**5.1.4-33** 12/March/2010 - 19th release
  * Added LeMock v0.6

**5.1.4-34** 18/March/2010 - 20th release
  * Updated Penlight to version 0.8.1

**5.1.4-35** 07/April/2010 - 21th release
  * Updated lExecutor to version 1.01
  * Updated Penlight to version 0.8.2

**5.1.4-36** 09/April/2010 - 22th release
  * Updated Penlight to version 0.8.3

**5.1.4-37** 04/May/2010 - 23th release
  * Updated Penlight to version 0.8.4

**5.1.4-38** 18/May/2010 - 24th release
  * Fixed #10 - LuaDoc incomplete. Added luadoc\_start.bat.
  * Fixed #09  - luanet kill lua.exe
  * Updated the SciTE .api file. Now includes lfs, bit and pack.

**5.1.4-39** 17/June/2010 - 25th release
  * Added LuaRocks version 2.0.2.
  * Updated wxLua to version 2.8.10.
  * Updated stdlib to release 15.
  * Updated stdlib to release 14.
  * Updated stdlib to release 13.

**5.1.4-40** 26/July/2010 - 26th release
  * Fixes #14 - Just a simple mistake in the link to LuaEx.
  * Fixes #18 - Lua tutorial typo.
  * Reverted to wxLua version 2.8.7 because there are issues with the new versions stability. It will get updated later.
  * Fixed pplot examples that ship with IUP.
  * Closed #20 - Updated IUP to version 3.2.0.
  * Updated Lanes to version 2.0.4.
  * Added Oil version 0.4-beta.

**5.1.4-41** 11/Jan/2011  - 27th release
  * Fixes #34 - LuaXML clib delivered with LuaForWindows causes memory leaks.

**5.1.4-42** 01/June/2011 - 28th release
  * Updated LuaLogging to version 1.2.0.
  * Updated stdlib to release 20.
  * Updated Penlight to version 0.9.4.

**5.1.4-43** 06/June/2011 - 29th release
  * Fixes #1 - LuaSocket example not upto date - cddb.lua.
  * Fixes #24 - Commented-out visible whitespace acquires coment colour.
  * Closed #19 - Added LuaJSON v1.2.2 library.
  * Closed #41 - Updated Alien to version 0.5.0.
  * Updated LPeg to version 0.10-1.
  * Updated stdlib to release 21.

**5.1.4-44** 08/June/2011 - 30th release
  * Fixed pl.dir so you can use strict module

**5.1.4-45** 14/June/2011 - 31st release
  * Fixes #42 - Please update Tecgraf libs (CD, IM, IUP)
  * Updated IUP to version 3.5.0.
  * Updated CD to version 5.4.1.
  * Updated IM to version 3.6.3.

**5.1.4-46** 07/August/2012 - 32nd release
  * Fixes #43 - require('lpeg') -- system error 14001
  * Updated stdlib to release 25.
  * Updated the Visual C++ 8.0 run-time to SP1-4053.
  * Updated lpeg.dll manifest to allow running on older vcredist\_x86.
  * Updated alien/core.dll manifest to allow running on older vcredist\_x86.
  * Updated alien/struct.dll manifest to allow running on older vcredist\_x86.
  * Updated examples/alien/tests/alientest.dll manifest to allow running on older vcredist\_x86.
  * Updated LuaXML\_lib.dll manifest to allow running on older vcredist\_x86.
  * Updated w32.dll manifest to allow running on older vcredist\_x86.
  * Updated Penlight to version 1.0.3.
  * Updated LuaUnit to version 2.0.
  * Added SubLua version 1.7.4 - Subversion binding

**5.1.4-47** 18/March/2015 - 33rd release
  * Updated stdlib to release 28.
  * Updated Penlight to 1.3.2.
  * Updated SubLua to 1.8.10.
  * **WARNING**: Moved all downloads and code hosting to GitHub. Older releases will not function when Google Code is shut down. Make sure to upgrade.

**5.1.4-48** 16/September/2015 - 34rd release
  * Added 30Log v1.0.0 - 30 lines library for object orientation in Lua
  * Updated SubLua to 1.8.11.

**5.1.4-49** 23/September/2015 - 35th release
  * Added delaunay Lua module
  * Added Binary Heaps Lua module
  * Added Moses Lua module

**5.1.4-50** 22/October/2015 - 36th release
  * Fixes #98 - Lua For Windows Installer - 'h' is an invalid URL.
  * Changed app URL to point to GitHub.
  * Changed minimum version to reflect the GitHub version.

**5.1.5-51** 29/March/2016 - 37th release
  * Updated to Lua 5.1.5.
  * Updated SubLua to 1.8.10-35352
