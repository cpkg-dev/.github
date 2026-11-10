<p align="center">
<img src="icon/cpkg.png" alt="Project Icon" width="105" height="92">
</p>

# cpkg

The C package manager, build system and dependency manager.<br />Written for C in C. No LLM/Ai/Code agents. Written for humans by a human.

### Installing cpkg
First of all, the dependencies for cpkg.<br />Here is all the things
currently you need to run cpkg, and or use to install cpkg.

You need:
- clang (specifically clang and not gcc)
- make (and or just)
- A Linux System (Other UNIX or UNIX like systems havent been tested currently)

### Building from source:


#### Building and installing using Make:
```bash
# Clone the repository
git clone https://github.com/cpkg-dev/cpkg.git
cd cpkg

# Build cpkg with make
make gather # Gets all dependencies
make cpkg # Makes cpkg

# Install cpkg on your system
# Run as superuser with sudo, su, doas, etc
sudo make install
```

#### Building and installing using Just:
```bash
# Clone the repository
git clone https://github.com/cpkg-dev/cpkg.git
cd cpkg

# Build cpkg with make
just gather # Gets all dependencies
just make-cpkg # Makes cpkg

# Install cpkg on your system
# Run as superuser with sudo, su, doas, etc
sudo just install
```
