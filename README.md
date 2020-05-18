# clink-profile

A clink profile to activate all sub-modoles in [clink-completions](https://github.com/fktpp/clink-completions) 

# installation
clink installation comes with two flavor, embedded or system.

## Embeded clink
For this kind of installation clink will be installed into **a subdirectory of its bundled software**. The clink profile will be named as `clink/profile`.
e.g. conemu

```bash
cd /c/Program Files/ConEmu/ConEmu/clink
git clone --recurse-submodules -j8 https://github.com/fktpp/clink-profile.git profile
```

## System clink
For this kind of installation clink will be installed into **Program Files** directory.  in this mode, clink will want to find its profile in User's AppData directory.

```bash
cd /c/Users/<UserName>/AppData/Local/
git clone --recurse-submodules -j8 https://github.com/fktpp/clink-profile.git clink
```

# Usage
This package will active automatically in new cmd session. clink will be extended to support more tab completetions such as `choco`, `git`, `conda`, etc.


# referencen
* https://github.com/mridgers/clink
* https://stackoverflow.com/questions/3796927/how-to-git-clone-including-submodules
* Clink document clink.html#configuring-clink and look for "File Location"
