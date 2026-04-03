# Cheat-hunter
Advanced Windows forensic scanner for detecting cheats, and anti-forensic tools

##  Core Features

### YARA Scanning Engine
- Custom YARA rules for cheats, packers, wipers, injectors
- FiveM cheat detection
- Kernel bypass driver detection
- High-entropy PE detection (packed/encrypted)

### Forensic Analysis Modules (25+)

**Execution History**
- Amcache.hve analysis with SHA-1 hashes
- Shimcache/AppCompatCache loader records
- UserAssist GUI execution history 
- Prefetch extended timeline
- BAM/DAM background activity monitor

**Deleted File Forensics**
- $MFT Master File Table scan for deleted records
- Recycle Bin $I file analysis
- Ghost deletion detection via Prefetch

**Memory & Process Analysis**
- Loaded DLLs scan
- Process spoofing detection (fake system processes)
- Crash dump analysis (unstable cheats)

**Registry & Artifacts**
- PCA Store execution artifacts
- RunMRU / TypedPaths history
- Registry autoruns (Run, RunOnce)
- Scheduled tasks persistence scan

**Anti-Forensics Detection**
- Event log clearing detection
- USN journal mass deletion detection
- TestSigning / integrity checks bypass
- Kernel driver mapper detection
- Critical services disabled detection

**Network & Browser**
- SRUM database network usage analysis
- Browser download history

**File System**
- Fake extensions hunter
- Recent file modifications
- External drive execution detection
- FiveM directories scan

### Reporting
- CSV export compatible with Timeline Explorer
- Severity classification (CRITICAL/HIGH/MEDIUM/LOW)
- MD5 & SHA256 hashes for detected files

### Performance
- Auto-elevation to Administrator
