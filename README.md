# c-lab

C-keele õppelabor ja projektide kogum (Debian VM).

## Eesmärk
- Süsteemne C-keele õppimine ülikooli tasemel
- Seos Linuxi, süsteemide, võrgu ja turvalisusega
- Väikesed, iseseisvad projektid + jagatud utiliidid

## Kaustastruktuur

### 00-notes
Teooria, märkmed ja konspektid (Markdown).

### 01-basics
C-keele põhialused:
- syntax, types, control flow
- memory basics
- build (gcc, make)

### 02-systems
Süsteemilähedane C:
- protsessid, signaalid
- ELF, syscallid
- mälu ja jõudlus

### 03-networking
Võrguprogrammeerimine C-s:
- socketid
- TCP/UDP
- pcap, lihtsad tööriistad

### 04-quality-security
Kvaliteet ja turvalisus:
- compiler warnings
- sanitizers
- basic hardening

### lib/common
Jagatud C-utiliidid, mida kasutavad mitmed projektid.

### projects/
Eraldi mini-projektid, igaüks oma kaustas:
- auditpack
- lab-agent
- logknife
- netwatch

Iga projekt sisaldab:
- oma `README.md`
- iseseisvat build’i
- selget eesmärki

## Keskkond
- OS: Debian (VM)
- Compiler: gcc / clang
- Tools: make, gdb, strace, ltrace

