# Simh Development Binaries

This repository contains binaries for the successful CI build activities produced each time one or more commits are pushed to the master branch of the https://github.com/simh/simh repository.

Each file in this repository is a zip file (or tarball) containing all of the simulator binaries built for one of the CI build platforms (Ubuntu 16.04, macOS BigSur, and Windows).    The Windows binaries will definitely run on any Windows systems since XP.  The Ubuntu and the macOS binaries are built on x86 system and may run on the current OS versions of these systems.

The latest binary build for [Windows is here](https://github.com/simh/Development-Binaries/blob/master/simh-2024-07-05_06-07-03-Windows-Win32-4.0-Current-670a3728.zip?raw=true), [Linux is here](https://github.com/simh/Development-Binaries/blob/master/simh-2024-07-05_05-47-25-Linux-x86_64-4.0-Current-670a3728.tgz?raw=true), and for [macOS is here](https://github.com/simh/Development-Binaries/blob/master/simh-2024-07-04_23-54-46-macOS-i386-4.0-Current-670a3728.tgz?raw=true).

To pickup a particular binary build for your platform, click on the interesting platform build results on the web UI above and on the right side of the resulting screen click on the  ![alt text](https://github.com/simh/Development-Binaries/blob/master/DownloadRawFile.png?raw=true) button which has the hover highlight text as "Download raw file".   Save the resulting downloaded file and extract the simulator binary(ies) you are interested in.

All versions of Windows on x86 systems back to XP including both 32bit and 64bit OS versions can run any of these simulators.

On macOS, when using any of the pre-built simulators, you will need to allow specific downloaded apps for the simulator(s) you want to use.  This is done in "System Preferences->Security & Privacy->General".  If you're not comfortable with this or you have a different OS version or a non x86 machine, you can readily build these simulators locally.

On Linux, you may have a different Linux distribution or an different architecture machine, you can easily build locally as well.

If issues are noticed with the behavior of any simulator, please create an issue at https://github.com/simh/simh/issues describing the problem, or send a note to the simh mailing list.  Please be sure to identify which binary demonstrates the issue and which commit introduced the problem.
