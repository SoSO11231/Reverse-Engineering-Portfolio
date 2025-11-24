Reverse-Engineering-Portfolio/
│
├── README.md
│
├── crackmes/
│   ├── crackme-01/
│   │   ├── README.md
│   │   ├── analysis.md
│   │   ├── patch_notes.md
│   │   ├── screenshots/
│   │   │   ├── ida.png
│   │   │   ├── x64dbg.png
│   │   └── scripts/
│   │       ├── patch.py
│   │       └── decrypt_xor.py
│   │
│   ├── crackme-02/  (نفس الهيكل)
│   └── crackme-03/
│
├── anti-debug/
│   ├── README.md
│   ├── IsDebuggerPresent.md
│   ├── NtQueryInformationProcess.md
│   ├── timing_tricks.md
│   └── patch_examples/
│       ├── bypass_IsDebuggerPresent.py
│       └── bypass_timing.py
│
├── tools/
│   ├── README.md
│   ├── ida_scripts/
│   │   └── string_xrefs.py
│   ├── python/
│   │   └── pe_header_parser.py
│   ├── decryptors/
│   │   └── xor_decryptor.py
│
└── docs/
    ├── ReverseEngineering-Cheatsheet.pdf
    ├── notes.md
    └── resources.md
