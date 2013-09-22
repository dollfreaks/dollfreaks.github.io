---

---
## Download Java! (for arm...)
 - [Oracle][1]
  - Make sure it's soft float, otherwise you get errors [like][2] [this][3]
  - [Client vs Server][4]
    - Client (low memory, fast startup, less optimization)
    - Server (higher memory, slower startup, more optimization)
 - OpenJDK ?

## Installation
 - Untar to? (/usr/lib? /lib? other?)
 - update-alternatives (clean) or symlink (simple)?

[Oracle Java Download][1]


[1]: http://www.oracle.com/technetwork/java/embedded/downloads/javase/index.html "Oracle Download Page"
[2]: http://askubuntu.com/questions/165953/no-such-file-or-directory-not-64bits "Cannot exec java binary"
[3]: https://wiki.linaro.org/OfficeofCTO/HardFloat/LinkerPathCallApr2012 "Referred to by [2]"
[4]: http://stackoverflow.com/questions/198577/real-differences-between-java-server-and-java-client "Which jdk?"
