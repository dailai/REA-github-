# REA-github-

The author of REA dropped 20 GitHub repositories all at once, enough to directly set up a full reverse engineering environment:

[01] Kernel Analysis
> REA: An MCP interface fully connected http://github.com/morluto/rea
> Ghidra: Free decompiler https://github.com/NationalSecurityAgency/ghidra.git
> GhidraMCP: Lets your agent directly operate Ghidra https://github.com/LaurieWired/GhidraMCP.git
> ida-pro-mcp: Hooks your agent up to IDA Pro https://github.com/mrexodia/ida-pro-mcp.git

[02] Mobile and Apps
> jadx: Decompiles Android APK back to Java http://github.com/skylot/jadx
> Apktool: Unpacks APK and repacks it https://github.com/iBotPeaches/Apktool.git
> Frida: Hooks into apps at runtime http://github.com/frida/frida
> ILSpy: Decompiles .NET https://github.com/icsharpcode/ILSpy.git

[03] Binaries and Low-Level
> radare2: Reverse engineering framework in the terminal https://github.com/radareorg/radare2.git
> x64dbg: Windows debugger http://github.com/x64dbg/x64dbg
> ImHex: Hex editor with pattern language http://github.com/WerWolv/ImHex
> angr: Symbolic execution engine http://github.com/angr/angr

[04] Network and Runtime
> mitmproxy: Intercepts and reads traffic in the middle https://github.com/mitmproxy/mitmproxy.git
> dnSpy: Debugs and modifies .NET apps http://github.com/dnSpyEx/dnSpy
> rizin: Fork of radare2 http://github.com/rizinorg/rizin
> raddebugger: Debugger from Epic Games https://github.com/EpicGames/raddebugger.git

[05] Reconstruction and Verification
> awesome-ai-reverse-engineering: 122 repositories, all rated https://github.com/zhuyansen/awesome-ai-reverse-engineering.git
> awesome-reverse-engineering: Handpicked by the REA author https://github.com/morluto/awesome-reverse-engineering.git
> REA Workflow: Ready-made research prompts, provided with REA
> Cleanroom Cycle: SPEC.md, criteria plus checks, iterate until it matches

The process goes like this: Binary -> REA -> SPEC.md -> Reconstruction -> Evaluation -> If it doesn't work, loop back

Save this for later, point it at any random app, and see how it explains itself.
