# cunoFS

Welcome to `cunoFS`'s public repository.
   
## Quickstart Guide

[Our quickstart guide](https://cuno-cunofs.readthedocs-hosted.com/en/stable/getting-started-introduction.html) is here to assist you if you have any further questions.

## Download and Installation
   
All installer files are available in the latest `Release` which can be found [here](https://github.com/cunoFS/cunoFS/releases).

### Single User Installation

You can install `cunoFS` for a single user by running the installer:
```bash
sh ./cuno-glibc-installer.run
# Accept the EULA
```
`cuno` will be installed at `$HOME/.local/bin` for local installs, so add:
```bash
PATH="$HOME/.local/bin:$PATH"
```
to your shell's `.rc` file to be able to call `cuno`.

### System-Wide Installation

You can run the previous script as the `root` user for a system-wide installation:
```bash
sudo sh ./cuno-glibc-installer.run
```
but we also provide `.deb.run` and `.rpm.run` scripts which bundle `.deb` and `.rpm` packages for your convenience:
```bash
sh ./cuno_amd64_glibc_deb.run
# Accept the EULA
cd cuno_amd64_glibc_deb
# The cunoFS documentation is available here as a pdf
# The .deb installer is also available here
sudo apt install -y ./cuno_*.deb
```
or:
```bash
sh ./cuno_x86_64_glibc_rpm.run
# Accept the EULA
cd cuno_x86_64_glibc_rpm
# The cunoFS documentation is available here as a pdf
# The .rpm installer is also available here
sudo yum install -y ./cuno_*.rpm
# or
sudo dnf install -y ./cuno_*.rpm
```


## Activation

You can get a free license for personal use on [cuno.io/activate](https://cuno.io/activate).

Complete the form and you'll receive the license through email.

You can then activate cuno with:
```bash
cuno creds activate
# Provide your license from the email
```

You can also download the license from the email attachment and run:
```bash
cat <path/to/license> | cuno creds activate
```


## Object Storage Credentials

https://cuno-cunofs.readthedocs-hosted.com/en/stable/getting-started-configuring-credentials.html#getting-your-credentials

   
## Help

You can access `cunoFS` documentation through different means:
- By reading [our quickstart guide](https://cuno-cunofs.readthedocs-hosted.com/en/stable/getting-started-introduction.html), which provides more detail at every stage.
- Through our manpage with:
```bash
cuno --help
```
They are also accessible `man` in `$CUNO_ROOT/share/man/`.
- By reading your user guide in `$CUNO_ROOT/CUNO-Installation-and-Usage-Guide.pdf`

If you have any further questions, feel free to ask a question on [our discourse page](https://discourse.cuno.io/), or [contact us](https://cuno.io/contact-us/).
