Nintendo GameCube Gekko CPU Extension plug-in for IDA Pro 9.1

*  (C) Copyright 2007 by HyperIris <fsstudio@263.net>
*  (C) Copyright 2025 by luxploit <laura@luxploit.net>

This is a Gekko CPU Paired Single extension instructions plug-in for IDA Pro 9.1

------------------------------------------------------------------------------------

This plug-in is for reverse engineering and homebrew debugging.
Use it as your wish.

Certainly, it's free for use, but if you distribute it please keep this readme file.

------------------------------------------------------------------------------------

Installation

Copy gekkoPS.dll to $IDA_ROOT\plugins

That's all, but you need of course PPC support in your version of IDA, hehe.

------------------------------------------------------------------------------------

Usage

It's simple: open .dol or .elf file, they work.

Hint: In IDA Menu Options->General->Disassembly, 
check <Auto comments> will show Paired Single instructions explain.

------------------------------------------------------------------------------------

Build

You need Visual Studio 2022 (edition does not matter) 
and a copy of the IDA 9.1 Pro SDK.

The SDK location needs to be set via an environment variable called IDASDK_DIR, for
example as "A:\idasdk91"

------------------------------------------------------------------------------------

Contact

HyperIris:
  You can find me at <fsstudio@263.net> or sometimes in irc channel: 
  #pcsx2 | #dolphin-emu | #gcdev | #wiidev at efnet

luxploit:
  E-Mail me at <laura@luxploit.net> or message me on Discord <@luxploit.net>

------------------------------------------------------------------------------------