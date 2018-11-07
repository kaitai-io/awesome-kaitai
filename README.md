# Awesome Kaitai [![Link Status](https://api.travis-ci.org/kaitai-io/awesome-kaitai.svg?branch=master)](https://travis-ci.org/kaitai-io/awesome-kaitai)

A curated list of Kaitai Struct tools and resources

- [Main Website](http://kaitai.io) ([Umbrella Repository](https://github.com/kaitai-io/kaitai_struct), [Github Pages](https://github.com/kaitai-io/kaitai-io.github.io), [Issues](https://github.com/kaitai-io/kaitai_struct/issues))

## Compiler

- Kaitai Struct: compiler to translate .ksy => .cpp / .cs / .dot / .java / .js / .php / .pm / .py / .rb ([Repository](https://github.com/kaitai-io/kaitai_struct_compiler), [Issues](https://github.com/kaitai-io/kaitai_struct_compiler/issues))
- [Online compiler](https://kaitai.io/repl/)

## Tools

- [Kaitai Web IDE](https://ide.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_webide), [Github Page](https://github.com/kaitai-io/ide-kaitai-io.github.io), [Wiki Documentation](https://github.com/kaitai-io/kaitai_struct_webide/wiki/Features))
  - [Web IDE Docs](https://github.com/kaitai-io/kaitai_struct_webide_docs) - Images for the documentation
  - [webide-usercontent.kaitai.io](https://github.com/kaitai-io/webide-usercontent.kaitai.io) - Used in sandboxing for the WebIDE
- [Development version of the IDE](https://ide.kaitai.io/devel/) ([Github Page](https://github.com/kaitai-io/ide-devel-kaitai-io.github.io))
- Kaitai Struct: visualizer and hex viewer tool ([Repository](https://github.com/kaitai-io/kaitai_struct_visualizer))
- kaitaiStructCompile.py - Automate ksy compilation into python files ([Repository](https://gitlab.com/KOLANICH/kaitaiStructCompile.py))
- Kaitai Struct: visualizer and hex viewer tool GUI in Java ([Repository](https://github.com/kaitai-io/kaitai_struct_gui), [Issues](https://github.com/kaitai-io/kaitai_struct_gui/issues)) - *deprecated?*

## Converter

- Convert C to ksy file ([Snippet](https://gist.github.com/GreyCat/9dba530b0d2cb8ccec4e1d6e90a0b565))
- Convert Synalyze It! Grammars to ksy files ([Repository](https://gitlab.com/KOLANICH/synalysis2kaitai))
- Converting Kaitai structs to wireshark LUA plugins ([Repository](https://github.com/joushx/kaitai-to-wireshark)) - *deprecated*

## Formats

- [Kaitai Struct library of binary file formats](http://formats.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_formats), [Github Pages](https://github.com/kaitai-io/formats-kaitai-io.github.io))
- APFS (apple file system) format ([Repository](https://github.com/cugu/apfs.ksy), [Issues](https://github.com/cugu/apfs.ksy/issues))
- DICOM (Digital Imaging and Communications in Medicine) file format spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/dicom.ksy), [Issues](https://github.com/kaitai-io/dicom.ksy/issues))
- EDID (VESA Enhanced Extended Display Identification Data) structure for Kaitai Struct ([Repository](https://github.com/kaitai-io/edid.ksy))
- Java bytecode spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/java_bytecode.ksy), [Issues](https://github.com/kaitai-io/java_bytecode.ksy/issues))
- Windows resource file spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/windows_resource_file.ksy), [Issues](https://github.com/kaitai-io/windows_resource_file.ksy/issues))

## Help, Documentation & Community

- [Kaitai Struct Documentation](http://doc.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_doc), [Github Pages](https://github.com/kaitai-io/doc-kaitai-io.github.io))
- [Stackoverflow](https://stackoverflow.com/questions/tagged/kaitai-struct)
- [Gitter channel](https://gitter.im/kaitai_struct/)
- [Official Twitter account](https://twitter.com/kaitai_io)

## Runtimes

- C++ using STL ([Repository](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime/issues))
- C#/.NET ([Repository](https://github.com/kaitai-io/kaitai_struct_csharp_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_csharp_runtime/issues))
- Go ([Repository](https://github.com/kaitai-io/kaitai_struct_go_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_go_runtime/issues))
- JavaScript ([Repository](https://github.com/kaitai-io/kaitai_struct_javascript_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_javascript_runtime/issues))
  - Examples ([Repository](https://github.com/kaitai-io/kaitai_struct_examples))
  - Webpack loader for kaitai-struct .ksy definitions ([Repository](https://github.com/kaitai-io/kaitai-struct-loader), [Issues](https://github.com/kaitai-io/kaitai-struct-loader/issues))
- Java ([Repository](https://github.com/kaitai-io/kaitai_struct_java_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_java_runtime/issues))
- Lua ([Repository](https://github.com/kaitai-io/kaitai_struct_lua_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_lua_runtime/issues))
- Perl ([Repository](https://github.com/kaitai-io/kaitai_struct_perl_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_perl_runtime/issues))
- PHP ([Repository](https://github.com/kaitai-io/kaitai_struct_php_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_php_runtime/issues))
- Python ([Repository](https://github.com/kaitai-io/kaitai_struct_python_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_python_runtime/issues))
  - [PIP packet](https://pypi.org/project/kaitaistruct/)
- Ruby ([Repository](https://github.com/kaitai-io/kaitai_struct_ruby_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_ruby_runtime/issues))
- Rust ([Repository](https://github.com/kaitai-io/kaitai_struct_rust_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_rust_runtime/issues))
- Swift ([Repository](https://github.com/kaitai-io/kaitai_struct_swift_runtime), [Issues](https://github.com/kaitai-io/kaitai_struct_swift_runtime/issues))

## Testing

- Tests for all languages ([Repository](https://github.com/kaitai-io/kaitai_struct_tests))
- Compiled test files ([Repository](https://github.com/kaitai-io/ci_targets))
- [Test results](http://kaitai.io/ci/) ([Test Artifacts Repository](https://github.com/kaitai-io/ci_artifacts))
- Benchmarking suite ([Repository](https://github.com/kaitai-io/kaitai_struct_benchmarks))
- Settings for shippable.com ([Repository](https://github.com/kaitai-io/kaitai_struct_shippable)) - *test?*

## Misc

- [bintray](https://bintray.com/kaitai-io) - Binary repository
- KaitaiFS: mount any filesystem specified with a .ksy as a real file system ([Repository](https://github.com/kaitai-io/kaitai_fs), [Issues](https://github.com/kaitai-io/kaitai_fs/issues))
- Compression processing libraries ([Repository](https://github.com/kaitai-io/kaitai_compress))

## Other Resources

- http://kaitai.io/workshop/
- https://platform.avatao.com/paths/6c78ce93-657a-4cb2-b4c0-25ed3d103beb
- https://archive.fosdem.org/2017/schedule/event/om_kaitai/ - Presentation on Kaitai from Mikhail Yakshin (GreyCat)
- http://vaughanhilts.me/blog/2016/11/16/reverse-engineering-trails-in-the-sky-ed-6-game-engine.html - Blog post on game reverse engineering
- https://pythonistac.wordpress.com/2017/03/09/python-network-packet-dissection-frameworks-shootout-scapy-vs-construct-vs-hachoir-vs-kaitai-struct/ - Blog post comparing different network packet dissection frameworks
- https://medium.com/@MorteNoir/database-reverse-engineering-part-2-main-approaches-ae9355b2d429 - A blog post about reverse-engineering unknown file formats with a proprietary car parts database as an example.

## Similar projects / tools

- https://github.com/renyxa/re-lab/tree/master/oletoy
- https://github.com/0xdabbad00/icebuddha
- https://github.com/padsproj/pads
- https://github.com/fox-it/dissect.cstruct
- [dtfabric](https://github.com/libyal/dtfabric)
- [construct](https://github.com/construct/construct) - Python library to create declarative parsers
- [vstruct2](https://github.com/vivisect/vstruct2) - Python structure definition and parsing library

### Hex Editors

- [0xED](http://www.suavetech.com/0xed/) - Native hex editor for OS X
- [hecate](https://github.com/evanmiller/hecate) - Terminal hex editor
- [Hexinator](https://hexinator.com) - Windows Version of Synalyze It!
- [HxD](https://mh-nexus.de/de/hxd/) - Small, fast hex editor for Windows
- [iBored](http://apps.tempel.org/iBored/) - Cross platform, sektor based hex editor
- [Synalyze It!](http://www.synalysis.net) - Hex editor with templates for binary analysis
- [wxHex Editor](http://www.wxhexeditor.org) - Cross platform editor with file comparison

### File Grammars

- [010 Editor Templates](http://www.sweetscape.com/010editor/templates/) - Templates for the 010 Editor
- [Contruct formats](https://github.com/construct/construct/tree/master/deprecated_gallery) - Parser for different file formats for the python construct package
- [HFSPlus Grammars](https://github.com/mac4n6/HFSPlus_Resources/tree/master/HFSPlus_Grammars) - HFS+ grammars for Synalysis
- [iBored Templates](http://apps.tempel.org/iBored/#) - Templates are packed inside the .app
- [Sleuth Kit file system grammars](https://github.com/sleuthkit/sleuthkit/tree/develop/tsk/fs) - Grammars for different file systems
- [Synalyse It! Grammars](https://www.synalysis.net/formats.xml) - File type grammars for the Synalyze It! editor
- [TestDisk grammars](https://github.com/cgsecurity/testdisk/tree/master/src) - Grammars used by TestDisk and PhotoRec
- [WinHex Templates](https://www.x-ways.net/winhex/templates/) - Grammars for the WinHex editor and X-Ways
- [Wireshark dissectors](https://github.com/wireshark/wireshark/tree/master/epan/dissectors) - Parsers for Wireshark
