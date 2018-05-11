# Chapter Systemd Security

# Content
1. seccomp
    * reference:
        * man seccomp
        * Linux Kernel: Documentation/networking/filter.txt
        * Linux Kernel: Documentation/prctl/seccomp_filter.txt
    * library:
        * https://github.com/seccomp

2. capabilities
    * reference: man capabilities

3. NameSpace
    * Network
    * IPC
    * ...

4. Directory or File permission limited
    * ReadWrite
        * ReadWriteDirectories
    * ReadOnly
        * ReadOnlyDirectories=, for directory, it means "r-x"
    * Inaccessible
        * InaccessibleDirectories=, no Invasible

5. Others

