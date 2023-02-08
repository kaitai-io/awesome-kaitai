# Awesome Kaitai [![Link Status](https://api.travis-ci.com/kaitai-io/awesome-kaitai.svg?branch=master)](https://app.travis-ci.com/github/kaitai-io/awesome-kaitai)

A curated list of Kaitai Struct tools and resources

- [Main Website](https://kaitai.io/) ([Umbrella Repository](https://github.com/kaitai-io/kaitai_struct), [Github Pages](https://github.com/kaitai-io/kaitai-io.github.io), [Issues](https://github.com/kaitai-io/kaitai_struct/issues))

## Compiler

- Kaitai Struct: compiler to translate .ksy => .cpp / .cs / .dot / .java / .js / .php / .pm / .py / .rb ([Repository](https://github.com/kaitai-io/kaitai_struct_compiler), [Releases](https://github.com/kaitai-io/kaitai_struct_compiler/releases))
- [kaitaigo](https://github.com/cugu/kaitaigo): alternative compiler to translate .ksy => .go, written in Golang
- [nimitai](https://github.com/sealmove/nimitai): The compiler implemented as macro in Nimlang (.ksy => Nim AST)

## Visualizers, IDEs, hex editors

### Arbitrary file formats

These tools allow to develop your own Kaitai Struct specifications in
iterative fashion by visualizing data locations in hex dump as one
develops .ksy.

- [Kaitai Web IDE](https://ide.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_webide), [Github Page](https://github.com/kaitai-io/ide-kaitai-io.github.io), [Wiki Documentation](https://github.com/kaitai-io/kaitai_struct_webide/wiki/Features))
  - [Web IDE Docs](https://github.com/kaitai-io/kaitai_struct_webide_docs) - Images for the documentation
  - [webide-usercontent.kaitai.io](https://github.com/kaitai-io/webide-usercontent.kaitai.io) - Used in sandboxing for the WebIDE
- [Development version of the IDE](https://ide.kaitai.io/devel/) ([Github Page](https://github.com/kaitai-io/ide-devel-kaitai-io.github.io))
- Kaitai Struct: visualizer and hex viewer tool ([Repository](https://github.com/kaitai-io/kaitai_struct_visualizer))
- Kaitai Struct: visualizer and hex viewer tool GUI in Java ([Repository](https://github.com/kaitai-io/kaitai_struct_gui), [Issues](https://github.com/kaitai-io/kaitai_struct_gui/issues))
- Kaitai Struct extension for VSCode ([Marketplace](https://marketplace.visualstudio.com/items?itemName=fudgepops.kaitai-struct-vscode), [Overview video](https://www.youtube.com/watch?v=4c7UuZ33JYE), [Repository](https://github.com/fudgepop01/fudgedit))
- Hobbits ([Repository](https://github.com/Mahlet-Inc/hobbits))

### Fixed set of file formats

These visualizers / hex editors allow only fixed set of precompiled file
format specifications to be used.

- Veles ([Homepage](https://codisec.com/veles/), [Repository](https://github.com/codilime/veles))
- Kaitai Struct plugin for Binary Ninja ([Repository](https://github.com/Vector35/kaitai))
- pytai ([Repository](https://github.com/Dvd848/pytai))

## Tools

- kaitaiStructCompile.py - Automate ksy compilation into python files ([Repository](https://gitlab.com/kaitaiStructCompile.py/kaitaiStructCompile.py))
- [ksylint](https://github.com/kaitai-io/ksylint) - A linter for .ksy files
- [ksy-dl](https://github.com/tins2831/ksy-dl) - Downloads .ksy files and their dependencies straight from the official kaitai-struct format gallery.

### CI

#### Docker images

- [`registry.gitlab.com/kaitaistructcompile.py/kaitai_struct_python_docker:latest`](https://gitlab.com/kaitaiStructCompile.py/kaitai_struct_python_docker) - an image with [CPython](https://www.python.org/downloads/), [GraalVM](https://github.com/oracle/graal/releases), [GraalPython](https://github.com/oracle/graalpython), KSC, python runtime, `kaitaiStructCompile.py`, and its CLI backend. Unstable versions of the software are used. Currently Debian-based, but sometimes this will be migrated to Alpine.
- [`blacktop/kaitai`](https://hub.docker.com/r/blacktop/kaitai/)
- [`librespace/kaitai`](https://hub.docker.com/r/librespace/kaitai) — docker image of the kaitaistruct-compiler used in the Libre Space Foundation Database
- [`davefr/kaitai-ksc`](https://hub.docker.com/r/davefr/kaitai-ksc) — Kaitai Struct compiler in a container ([Repository](https://github.com/anonymousatc/kaitai-ksc))

## Converter

- Convert C to ksy file ([Snippet](https://gist.github.com/GreyCat/9dba530b0d2cb8ccec4e1d6e90a0b565))
- Convert Synalyze It! Grammars to ksy files ([Repository](https://gitlab.com/KOLANICH/synalysis2kaitai))
- Converting Kaitai structs to wireshark LUA plugins ([Repository](https://github.com/joushx/kaitai-to-wireshark)) - *deprecated*

## Formats

- [Kaitai Struct library of binary file formats](https://formats.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_formats), [Github Pages](https://github.com/kaitai-io/formats-kaitai-io.github.io))
- APFS (apple file system) format ([Repository](https://github.com/cugu/apfs.ksy), [Issues](https://github.com/cugu/apfs.ksy/issues))
- DICOM (Digital Imaging and Communications in Medicine) file format spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/dicom.ksy), [Issues](https://github.com/kaitai-io/dicom.ksy/issues))
- EDID (VESA Enhanced Extended Display Identification Data) structure for Kaitai Struct ([Repository](https://github.com/kaitai-io/edid.ksy))
- Java bytecode spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/java_bytecode.ksy), [Issues](https://github.com/kaitai-io/java_bytecode.ksy/issues))
- Windows resource file spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/windows_resource_file.ksy), [Issues](https://github.com/kaitai-io/windows_resource_file.ksy/issues))

## Help, Documentation & Community

- [Kaitai Struct Documentation](https://doc.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_doc), [Github Pages](https://github.com/kaitai-io/doc-kaitai-io.github.io))
- [Stackoverflow](https://stackoverflow.com/questions/tagged/kaitai-struct)
- [Gitter channel](https://gitter.im/kaitai_struct/Lobby)
- [Official Twitter account](https://twitter.com/kaitai_io)

## Runtimes

- C++ using STL ([Repository](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime/issues))
- C#/.NET ([Repository](https://github.com/kaitai-io/kaitai_struct_csharp_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_csharp_runtime/issues))
  - [NuGet package](https://www.nuget.org/packages/KaitaiStruct.Runtime.CSharp/)
- Go ([Repository](https://github.com/kaitai-io/kaitai_struct_go_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_go_runtime/issues))
- JavaScript ([Repository](https://github.com/kaitai-io/kaitai_struct_javascript_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_javascript_runtime/issues))
  - [npm package](https://www.npmjs.com/package/kaitai-struct)
  - Examples ([Repository](https://github.com/kaitai-io/kaitai_struct_examples))
  - Webpack loader for kaitai-struct .ksy definitions ([Repository](https://github.com/kaitai-io/kaitai_struct_loader), [Issues](https://github.com/kaitai-io/kaitai_struct_loader/issues))
- Java ([Repository](https://github.com/kaitai-io/kaitai_struct_java_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_java_runtime/issues))
  - [Java .jar package at Maven Central](https://search.maven.org/artifact/io.kaitai/kaitai-struct-runtime)
- Lua ([Repository](https://github.com/kaitai-io/kaitai_struct_lua_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_lua_runtime/issues))
- Nim ([Repository](https://github.com/kaitai-io/kaitai_struct_nim_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_nim_runtime/issues))
- Perl ([Repository](https://github.com/kaitai-io/kaitai_struct_perl_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_perl_runtime/issues))
- PHP ([Repository](https://github.com/kaitai-io/kaitai_struct_php_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_php_runtime/issues))
- Python ([Repository](https://github.com/kaitai-io/kaitai_struct_python_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_python_runtime/issues))
  - [PyPI package](https://pypi.org/project/kaitaistruct/)
- Ruby ([Repository](https://github.com/kaitai-io/kaitai_struct_ruby_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_ruby_runtime/issues))
  - [Ruby gem](https://rubygems.org/gems/kaitai-struct)
- Rust ([Repository](https://github.com/kaitai-io/kaitai_struct_rust_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_rust_runtime/issues))
- Swift ([Repository](https://github.com/kaitai-io/kaitai_struct_swift_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_swift_runtime/issues))

## Testing

- Tests for all languages ([Repository](https://github.com/kaitai-io/kaitai_struct_tests))
- Compiled test files ([Repository](https://github.com/kaitai-io/ci_targets))
- [Test results](https://ci.kaitai.io/) ([Test Artifacts Repository](https://github.com/kaitai-io/ci_artifacts))
- Benchmarking suite ([Repository](https://github.com/kaitai-io/kaitai_struct_benchmarks))

## Misc

- KaitaiFS: mount any filesystem specified with a .ksy as a real file system ([Repository](https://github.com/kaitai-io/kaitai_fs), [Issues](https://github.com/kaitai-io/kaitai_fs/issues))
- Compression processing libraries ([Repository](https://github.com/kaitai-io/kaitai_compress))

## Other Resources

- https://kaitai.io/workshop/
- https://avatao.com/blog-kaitai/
- https://archive.fosdem.org/2017/schedule/event/om_kaitai/ - Presentation on Kaitai from Mikhail Yakshin (GreyCat)
- https://vaughanhilts.me/blog/2016/11/16/reverse-engineering-trails-in-the-sky-ed-6-game-engine.html  - Blog post on game reverse engineering
- https://pythonistac.wordpress.com/2017/03/09/python-network-packet-dissection-frameworks-shootout-scapy-vs-construct-vs-hachoir-vs-kaitai-struct/ - Blog post comparing different network packet dissection frameworks
- https://medium.com/@MorteNoir/database-reverse-engineering-part-2-main-approaches-ae9355b2d429 - A blog post about reverse-engineering unknown file formats with a proprietary car parts database as an example.

## Similar projects / tools

- [3D Model Researcher](http://mr.game-viewer.org/) - Studying binary files of 3D models
- [BeeSchema](https://github.com/Michael-Kelley/BeeSchema) - Binary Schema Library for C#
- [bindata](https://github.com/dmendel/bindata) - Binary data parsing for Ruby
- [construct](https://github.com/construct/construct) - Python library to create declarative parsers
- [dtfabric](https://github.com/libyal/dtfabric)
- [vstruct2](https://github.com/vivisect/vstruct2) - Python structure definition and parsing library
- https://github.com/0xdabbad00/icebuddha
- https://github.com/fox-it/dissect.cstruct
- https://github.com/frodef/binary-types - Read and write binary records for Common Lisp
- https://github.com/j3pic/lisp-binary - A library to easily read and write complex binary formats (Common Lisp)
- https://github.com/padsproj/pads
- https://github.com/renyxa/re-lab/tree/master/oletoy

### Hex Editors

- [hecate](https://github.com/evanmiller/hecate) - Terminal hex editor
- [Hexinator](https://hexinator.com/) - Windows Version of Synalyze It!
- [HxD](https://mh-nexus.de/de/hxd/) - Small, fast hex editor for Windows
- [iBored](https://apps.tempel.org/iBored/) - Cross-platform, sector based hex editor
- [Synalyze It!](https://www.synalysis.net/) - Hex editor with templates for binary analysis
- [wxHex Editor](https://www.wxhexeditor.org/) - Cross-platform editor with file comparison
- [hexalepis](https://github.com/sealmove/hexalepis) - Win/Unix gui+terminal, [tweak](https://www.chiark.greenend.org.uk/~sgtatham/tweak/btree.html) engine, .ksy visualization
- [Hex Editor Neo](https://www.hhdsoftware.com/hex-editor) - fast binary file editor for Windows (supports Kaitai Struct [in its Structure Viewer](https://hhdsoftwaredocs.online/hex/definitive-guide/structure-viewer/kaitai.html))

### File Grammars

- [010 Editor Templates](https://www.sweetscape.com/010editor/templates/) - Templates for the 010 Editor
- [Construct formats](https://github.com/construct/construct/tree/master/deprecated_gallery) - Parser for different file formats for the python construct package
- [HFSPlus Grammars](https://github.com/mac4n6/HFSPlus_Resources/tree/master/HFSPlus_Grammars) - HFS+ grammars for Synalysis
- [iBored Templates](https://apps.tempel.org/iBored/#:~:text=fix%20them%20ASAP.%29-,Templates,-Some%20data%20is) - Templates are packed inside the .app
- [Sleuth Kit file system grammars](https://github.com/sleuthkit/sleuthkit/tree/develop/tsk/fs) - Grammars for different file systems
- [Synalyse It! Grammars](https://www.synalysis.net/formats.xml) - File type grammars for the Synalyze It! editor
- [TestDisk grammars](https://github.com/cgsecurity/testdisk/tree/master/src) - Grammars used by TestDisk and PhotoRec
- [WinHex Templates](https://www.x-ways.net/winhex/templates/) - Grammars for the WinHex editor and X-Ways
- [Wireshark dissectors](https://github.com/wireshark/wireshark/tree/master/epan/dissectors) - Parsers for Wireshark
