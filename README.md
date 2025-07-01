# ZigStrike
ZigStrike is a robust shellcode loader developed in Zig, offering a variety of injection techniques and anti-sandbox features. It leverages compile-time capabilities for efficient shellcode allocation, demonstrating proven success in bypassing advanced security solutions
<img src="https://raw.githubusercontent.com/harryhaxor/ZigStrike/main/image.png" alt="ZigStrike Image" width="600">
ZigStrike includes a custom payload builder, allowing users to easily select and construct payloads via a web application built with Python.
Features ( release 2.0 )

    Multiple Injection Techniques:
        Local Thread
        Local Mapping
        Remote Mapping
        Remote Thread hijacking
        EarlyCascade injection

    Anti-Sandbox Protection:
        TPM Presence Check.
        Domain Join Check.
        Run-Time protection.

    Output Formats:
        XLL (Excel Add-in)
        DLL
        CPL

    Advanced Features:
        Shellcode advanced allocation.
        Payload Runtime protection; preventing emulation and sandbox dynamic anaylsis.
        Bypass common detection rules.

    Front-end enhancement:
        Added new page to view generated payloads.
        Detailed information for each created payload.
        Fix flask issue to support uploading large shellcode.

Prerequisites

    Zig 0.14.0
    Ubuntu / Debian
    Python 3.x (for the web interface)
    Flask

