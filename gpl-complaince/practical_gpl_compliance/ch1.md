[]{#_bookmark0 .anchor}CHAPTER 1:

# Approach

## "In theory there is no difference between theory and practice. In practice there is."

YOGI BERRA

## Context

Compliance engineering consists of a good approach, a good toolbox,
and a good process. First things first: What are our goals in
compliance engineering?

This book focuses on GPL Compliance Engineering. The GPL is a
copyright license with terms that trigger when we distribute the code.
The most famous and widely used version of the license is the GPL
Version 2 (GPLv2). Software such as the Linux kernel or many
commonly-used versions of GNU userland tools fall under this license.
There are other licenses, such as the Library or Lesser GPL (LGPL) or
Affero GPL (AGPL), which are regarded as being in the same "family"
but which have different terms. We address key aspects of the LGPL in
Flowchart #52 later in this text, but we do not specifically address
the terms of the AGPL in this book.

The focus in this book will be on GPL Version 2. This is formally
referred to as the GPLv2. However, throughout this book we will refer
to it as the GPL to keep things simple. This means that unless
explicitly stated otherwise, we mean "GPL Version 2" when we say
"GPL." You can review this license and all the other GPL family
licenses on the Free Software Foundation website.3

GPL compliance engineers are concerned about software products that
are electronically or physically distributed. Sometimes this means
scanning source code to confirm it has the expected licensing.
Sometimes this means scanning binary code or cross-checking binary
code with source code to confirm that they match. In practice, most
compliance work is focused on physical products sent to market or
firmware downloads.

2.  [See page 62](#_bookmark33)

3.  See
    [**https://www.gnu.org/licenses/licenses.html**](https://www.gnu.org/licenses/licenses.html)

[]{#_bookmark2 .anchor}This book explains the process of confirming
whether the binary code on a physical device contains GPL code and
then taking action to ensure compliance if it does.

## Compliance Requirements

The GPLv2 (hereafter the GPL) has a couple of important requirements.
One is ensuring that a copy of the license is provided along with the
distributed binary or source code. The other is providing access to
source code when distributing binary code either as a stand-alone
software application or as part of a physical product.

The GPL describes two ways to comply with the source code access
requirement:

1.  Accompany a product with the "complete and corresponding source
    code" (section 3a)

2.  Include a written offer to supply the "complete and corresponding
    source code" (section 3b)

These two methods differ in **how** the source code is delivered
(either with the binary code or later if requested), but they do not
differ in **what** needs to be delivered: complete and corresponding
source code.

## Compliance Goals

Now that we understand the GPL compliance requirements, we can
understand our overarching compliance goals:

1.  Make sure a copy of the license accompanies the distributed binary
    or source code .

2.  Make sure that the "complete and corresponding" source code is
    available.

#### Copy of the License

When you distribute GPL code as binary or source code, you need to
ensure it is accompanied by a copy of the GPL license. This is the
easiest and quickest part of any GPL compliance engineering process.

You can include a copy of the GPL license as physical or digital media
along with a product. Some examples are:

-   Smart televisions that come with a copy of the GPL physically
    printed at the back of the instruction manual along with other legal
    notices.

-   Smartphones that come with a copy of the GPL under the Settings \
    Legal menu or similar location.

The important objective is to ensure that the license is easily
discoverable by an interested party.

#### "Complete and Corresponding" Source Code

This is a challenging part of GPL compliance and the situation that
the majority of this book helps to explore, explain, and solve. As
mentioned above, our focus is primarily on physical products
distributed with GPL software contained inside, because this is the
most common and most problematic use case for compliance engineers.
Typical examples include firmware flashed onto a device or firmware
updates downloadable from a website.

##### Two Key Considerations

There are two primary checks you need to focus on to ensure
compliance:

1.  The source code does not contain any license violations.

2.  The source code is "complete and corresponding" for the binary code
    distributed.

##### The Ideal Situation

In an ideal world, there is a binary package or a collection of binary
packages, such as a firmware and a corresponding source code archive.
The corresponding source code archive contains only open source
components and perhaps some object files to relink binaries that
contain Library or Lessor GPL (LGPL) software, along with instructions
for rebuilding the binary or firmware. After performing the rebuild,
the original binary file is an exact match to the rebuilt binary file.

##### The Reality

Source code is often not "complete and corresponding." When you
rebuild a binary, you may find different file sizes or even completely
different versions or types of binary code compared to the expected
original. This is the first major challenge we face when seeking to
ensure GPL compliance.

Another challenge comes as a consequence of the above. The source code
for a device often contains license violations that are unrelated to
the binary code it is meant to support. For example, source code
archives sometimes contain prebuilt binaries that have no relevance to
being "complete and corresponding," and instead serve only to put a
company out of compliance when it makes source code available in good
faith.

This is where the bulk of GPL compliance engineering takes place.
Compliance engineers live on the intersection between source code and
binary code. Our challenge is to ensure that a physical product ships
with the expected code, with a copy of the correct licenses, and with
the "complete and corresponding" source code or a written offer to
provide that "complete and corresponding" source code on demand.

## Toolbox

Now that our challenge is clear, it is time to talk about the type of
tools we need to get things done. This discussion is not intended to
be exhaustive, but rather to provide a starting point. If you have
access to the tools we talk about below, you can do everything
contained in this guide. In turn, that will allow you to address the
vast majority of GPL compliance engineering challenges out there.

#### Default Tools

The primary tool for any open source compliance engineer is Linux.
This means that every active engineer needs to download, install, and
set up a standard Linux distribution such as Fedora, CentOS, openSUSE,
Debian, or Ubuntu. They all come with default tools pre-installed that
act as the backbone of our work. Examples include *file, readelf,
find, xargs, grep, dd,* and *modinfo.*

Here are free installations you can get, and where you can get them:

-   Fedora: [**https://getfedora.org/**](https://getfedora.org/)

-   openSUSE: [**http://opensuse.org/**](http://opensuse.org/)

-   Debian: [**https://www.debian.org/**](https://www.debian.org/)

-   Ubuntu: [**https://www.ubuntu.com/**](https://www.ubuntu.com/)

-   CentOS: [**https://www.centos.org/**](https://www.centos.org/)

Armijn Hemel's default installation for compliance engineering is
Fedora. However, the choice of distribution matters less than the
engineer being comfortable with that choice.

#### Binary Analysis

There are some specialized tools to help with analysis of binaries.

We mainly use the Binary Analysis Tool (BAT), but you have options,
and can select the one you're most comfortable using.

##### The Binary Analysis Tool (BAT)

The Binary Analysis Tool makes it easy to look inside binary code,
find compliance issues, and reduce uncertainty when deploying Free and
Open Source Software. It is a modular framework that assists
compliance and due diligence activities by using the same type of
approach applied by copyright holders to discover issues in consumer
electronics. BAT can open more than 30 types of compressed files, file
systems, and media files; search for Linux kernel and BusyBox issues;
identify dynamically linked libraries; and scan arbitrary ELF, Android
Dalvik, and Java class files using a database with information
extracted from source code to find out what software is inside. BAT is
available for free under the Apache license so that everyone can use,
study, share, and improve it.

-   BAT direct download:
    **[https://github.com/](https://github.com/armijnhemel/binaryanalysis)
    [armijnhemel/binaryanalysis](https://github.com/armijnhemel/binaryanalysis)**

-   BAT user guide:
    **[https://github.com/armijnhemel/](https://github.com/armijnhemel/binaryanalysis/blob/master/doc/bat-manual.pdf)
    [binaryanalysis/blob/master/doc/bat-manual.pdf](https://github.com/armijnhemel/binaryanalysis/blob/master/doc/bat-manual.pdf)**

##### binwalk

Another tool for analysing firmware is binwalk --- an easy to use tool
for analyzing, reverse engineering, and extracting firmware images.

-   binwalk download:
    [**https://github.com/devttys0/binwalk**](https://github.com/devttys0/binwalk)

-   binwalk user guide:
    **[https://github.com/devttys0/](https://github.com/devttys0/binwalk/wiki)
    [binwalk/wiki](https://github.com/devttys0/binwalk/wiki)**

#### Source Code Analysis

Our focus is on how to address binary code and the distribution of
physical devices. This does not mean that tools to address

[]{#_bookmark4 .anchor}source code are unavailable. Indeed, every good
compliance engineer has at least one such tool on hand to assist with
confirming that source code licenses are what they expect. The best
place to get started is usually with FOSSology, a free license scanner
that examines source code archives and lets you know what licenses
they appear to be under.

##### FOSSology

FOSSology
([**https://www.fossology.org**](https://www.fossology.org/)) is both
a compliance software system and a toolkit. As a toolkit, it allows
you to run license, copyright, and export control scans from the
command line. As a system, it provides a database and web UI to give
you a compliance workflow. With one click, you can generate an SPDX
file or a README with the copyright notices from your software.
FOSSology deduplication means that you can scan an entire distro,
submit a new version, and only the changed files will get rescanned.
This can be a huge timesaving tool for large projects.

-   Learn more about the project here:

[**https://www.fossology.org**](https://www.fossology.org/)

-   Find a simple 'Get Started' guide to FOSSology here:

[**https://www.fossology.org/get-started**](https://www.fossology.org/get-started)

## Analysis of Binary Files

#### A Word about Binaries

In this book, the word "binary" can mean different things. Sometimes
it means a single executable, sometimes it means an object file,
sometimes it means an archive of binaries, sometimes a firmware; other
times it means an unknown blob of data.

Here is what these different types of binary uses all have in common:

1.  They are not source code.

2.  They could be built from open source code.

3.  They should be analysed.

#### Tools for Analyzing Binaries

##### General Approach

Analysis of a binary can be performed using a number of methods and
tools. It is generally recommended to use the Binary Analysis Tool4 or
*binwalk*5 where possible, to quickly and simply look inside binary
code without reverse analysis. You can also manually dissect a binary
file, blob, or package such as firmware, but this tends to take more
time, and provides little advantage in exchange for the increased
complexity.

##### Limitations

Not every binary can be unpacked for analysis. For example, firmware
might have been obfuscated through file system modifications, or it
may have been encrypted. Sometimes it is possible to identify the file
system modifications or to reverse the encryption, but in other cases,
it is impossible.

##### Advanced Methods

Advanced methods of getting around obfuscation include grabbing code
from a "live" or running device through soldering connections or
breaking into it over a network. These techniques are out of scope of
this book. In the real world, most of the time, you will not face
these challenges.

4.  [**http://www.binaryanalysis.org**](http://www.binaryanalysis.org/)

5.  [**https://github.com/devttys0/binwalk**](https://github.com/devttys0/binwalk)

## Source Code Analysis and Rebuild

A source code archive should be inspected to do the following tasks:

1.  Find possibly problematic binaries in source code archives

2.  Perform a rebuild of the source code and comparing it to the
    original binary

3.  Find incorrectly licensed code

#### Finding Possibly Problematic Binaries

Source code archives from chipset manufacturers and ODMs (original
design manufacturer) often contain more than just source code. Inside
these archives you will often find:

-   Object files leftover from a previous build

-   "Out of tree" Linux kernel modules in binary form

-   Libraries/executables such as a root file system from a previous
    build

-   File system images

-   Linux kernel images with initial embedded ramdisks/ initramfs file
    systems

-   Other firmware images

Each of these files will be explored in more detail later.

You can easily find possibly problematic files using the *"find"*
command in combination with the *"file"* and *"xargs"* commands. One
easy way to do this is to run *"file"* for every file and redirect the
output to a result file. You can then inspect this result file at your
convenience. Here is an example command to get you started:

\$ find /path/to/source/code -type f -print0 \| xargs \--null file \
/path/to/result/file

You should search for:

-   ##### ELF files

Pay attention to the architecture. If an unexpected architecture is
shown, such as MIPS, but your deployed device is ARM, then the binary
can probably be removed.

-   ##### PE32 and PE32+ files

These are Windows binaries and usually have no place in a source code
release related to an embedded Linux system. The exception is if they
are related to ActiveX plugins.

-   ##### Linux kernel boot images

If these are present either as a compressed file or as part of a
U-Boot boot image, they can almost always be removed, because they
were almost certainly compiled using a different configuration file.
Including them would lead to potentially introducing licensing
requirements unrelated to the target device. If such images cannot be
removed because they are needed by the build process, it indicates
that the source code is not complete. The shortcut is to search for
"vmlinux," "vmlinuz," or similar files.

-   ##### MacOS X files

Like Windows files, these have no place in a source code release of an
embedded Linux system, except if they are related to software that
would be served to Apple MacOS X machines by the device. The shortcut
to search for is "Mach-O." These files are often present in the
prebuilt toolchain sources from Android as distributed by Google.

##### Object Files

Object files (extension ".o") can frequently be found in source code
releases. They are usually not problematic from a compliance

perspective, because the corresponding source code is typically also
present. However, they make analysis more complex, because they mean
more files to look at. You can address this quickly and cleanly by
checking if the corresponding extension ".c" or ".cc" files are
present and, if so, using "make clean" to remove the object files.

If there is no source code, you may have a compliance challenge. There
are situations where the object files are needed to complete the build
process and should not be removed. One example is object files that
are part of a proprietary program that is statically linked with LGPL
licensed code and which need to be relinked. Another example is when
object files are part of a proprietary program that is statically
linked with GPL licensed code and where compliance may be difficult or
impossible depending on your legal jurisdiction and your legal
counsel's interpretation of the GPL license.

##### "Out of tree" Linux Kernel Modules

Some devices contain components unsupported by the default Linux
kernel. These need extra drivers to function correctly, and such
drivers are often implemented as Linux kernel modules. A few examples
include WiFi drivers, camera drivers, or firewalling modules. These
extensions provide two common challenges:

1.  Many drivers are provided prebuilt by vendors to ease integration
    issues. The license of these drivers should be carefully checked to
    ensure they are compatible with the license of the Linux kernel
    source.

2.  When extra driver source code is available, it may not be integrated
    correctly in the source code tree. Incorrect integration in the
    build system often leads to missing source code in the final
    delivery.

##### Libraries/Executables

There are often library or executable binaries in the source code
tree. This occurs when:

1.  The source code tree was not properly cleaned up after building.
    This often occurs because someone forgot to run "make clean" after
    building binaries from the source code.

2.  The binaries are in a "template" or "skeleton" directory used as the
    blueprint to build a firmware. The directory structure and the
    binaries in the template directory are copied first, and other files
    are added to it during the build.

If these binaries contain any open source licensed code and do not
match the source code prepared for distribution, they should be
removed. A wrong version number, a different configuration, or any
other alteration from the source code could introduce unintended
violations.

The key question when considering this matter is: "Is the source code
'complete and corresponding' to the built binary code and free of any
extra binary or source code elements?"

##### File System Images

Sometimes entire file system images are included in the source code
tree. For example, many Android source code trees contain file system
images called "boot.img" and "system.img." If these contain any open
source software without corresponding source code, this could lead to
unwanted violations. These images can typically be removed without any
problem.

##### Other Firmware Images

There have been instances where complete firmware for devices
unrelated to the device being brought to market have been found in the
source code archive. These often contain different software versions,
packages, and sometimes even architectures to the current device. As
such, these firmware are an unwanted and unnecessary source of license
violations, and can typically be removed without any problem.

#### Performing a Rebuild

The most effective way to see if the source code is complete and
corresponding is to rebuild the software and compare it to the
original (binary) software. If they are identical --- or nearly
identical

-   then it is a good indication the source code is likely correct.

##### Perfect(ish) Rebuilds

In some cases, paths and time stamps are incorporated into a binary
file. This makes it very difficult, if not impossible, to do an exact
rebuild. Therefore, "close enough" means that the only differences
should be in timestamps, filename paths recorded in the binary, and
similar items.

##### Requirements

For a rebuild, it is important to have the following information:

1.  A description of the build environment.

2.  Full build instructions.

##### Goals

A rebuild has two key goals:

1.  Verify that the build works.

2.  Verify the results.

##### Describing the Build Environment

To successfully compare rebuilt binaries with original binaries, the
build environment has to be described as accurately as possible. This
description should include:

-   The name and version of the Linux distribution or operating system
    that needs to be installed (example: Fedora 7, 32 bit, or Ubuntu LTS
    12.04, 64 bit).

-   The name and version of any packages to install if they are not
    installed in a default installation.

-   Any modifications that need to be made to the default system, such
    as:

![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}Symbolic links that need to be
created. Directories that need to be created.

![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}Permissions that need to be changed.6
Files that need to exist.

![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}![](media/image6.png){width="7.305555555555555e-2in"
height="7.305446194225722e-2in"}Specific users that need to be
created. Environment variables that need to be set.7

If the build environment is different from the original, even to the

extent of using a different compiler or different compiler options, it
could have a big impact on the generated code. This in turn makes it a
lot more difficult to compare the binary files to verify whether the
source code appears to be "complete and corresponding" to the original
binary.

##### Supplier/Client Roles

The requirement for accurate re-creation of build environments leads
to a simple dynamic for providing information.

-   If you are a supplier needing to provide build environment
    information to a client, you should be as detailed as possible.

-   If you are a client needing to have build environment information,
    you should ask your supplier to be as detailed as possible.

6.  These include items like executable bits, read/write permission, and
    ownership permissions.

7.  These include PATH, CLASSPATH, and similar.

##### Rebuild Instructions

The build instructions should clearly explain the exact steps taken to
rebuild a binary. This includes:

-   The exact commands needed to rebuild the binary or firmware.

-   The expected results such as, for example, where binaries can be
    found after a rebuild.

In an ideal situation, you could give the instructions to a random
engineer, who would then be able to perform a nearly perfect rebuild
without any problems.

##### Verifying the Instructions

In the real world, you might expect that people doing a rebuild for
enforcement purposes will stop at the first hurdle they encounter. You
should not assume that people can (or want to) fix these issues;
therefore, the rebuild instructions should be complete, tested, and
foolproof.

It is best to perform a rebuild on a clean physical or virtual
machine, using the exact instructions that were provided. This is
because undocumented modifications frequently exist on development
machines such as the one on which the original build was completed. If
possible, task another engineer --- one without extensive knowledge of
the project --- to do the rebuild and to document any problems
encountered. Adjust the instructions as necessary to ensure clarity
and build success.

##### Verifying the Results

After the rebuild, you need to verify the results. Make sure that the
right results are being examined --- nothing cached from a previous
build. Two methods for accomplishing this are:

1.  The checksum of the binaries.

2.  The content of the binaries.

*The Checksum of the Binaries*

A cryptographic checksum or hash can be computed for the contents of
the file. If the file that was rebuilt has the same hash as the
original binary, then the files are identical. The tools for this are
*"md5sum"* for MD5 hashes and *"sha256sum"* for SHA256 hashes. The
following commands will compute the hashes for two binaries and print
the results. If the results are the same except for the path, then the
files are identical:

\$ md5sum /path/to/original/binary /path/to/new/ binary

\$ sha256sum /path/to/original/binary /path/to/ new/binary

It should be noted that it is best to run these commands on the
individual binaries in a firmware (like *"smbd"* or *"iptables"*) and
not on the whole freshly built firmware. This is because the checksums
for firmware might never be the same. Some binaries like BusyBox or
the Linux kernel will return a different checksum every time, because
by default they include timestamps internally.

*The Content of the Binaries*

In many cases, the checksums of an original binary and a rebuilt
binary will not be identical because the paths of source code files
and timestamps are included. These often differ with each build, even
if an environment is carefully set up.

Not to worry. The following steps can be taken to see if a rebuilt
binary is close enough to the original binary:

1.  Check the file size.

2.  Compare the contents of the file.

*Checking the File Size*

The file size of the rebuilt binary should be very close to the
original binary. If there is a big difference, first check if one of
the binaries is "stripped" (no debugging symbols present) and the
other is not stripped. If this is the case, strip the other binary
too, using the "strip" command (this tool should be included in the
toolchain). If the difference is still significant, then the binaries
are likely not the same.

*Comparing the Contents of the File*

The "strings" command can be used to extract human readable strings
from a binary. This can provide a lot of useful information.

The most important point is that the differences between binaries that
were built identically will be very minor. For the most part, you can
expect differences to be constrained to timestamps, filenames, and
directory names.

This means that you can compare the contents of a file with a simple
three-step process:

1.  Rebuild the binary.

2.  Extract contents using "strings."

3.  Compare the results to the original binary.

The following commands will help you extract the contents of the
files:

\$ strings /path/to/old/binary \

/tmp/strings.old

\$ strings /path/to/new/binary \

/tmp/strings.new

\$ diff -u /tmp/strings.old

/tmp/strings.new \| less

If the differences uncovered are limited to timestamps and path names,
then it is almost certain that the two binaries are in fact identical.

#### Finding Incorrectly Licensed Code

Modifications to open source licensed programs may not be licensed
correctly. One classic example is when changes to the Linux kernel
made by a chipset manufacturer either lack license statements or
contain a statement that is not compatible with the GPL.

There have been enforcement cases focused on relicensing Linux kernel
driver code added by chipset manufacturers. The following steps should
be taken to avoid such situations:

1.  Find incorrectly licensed files.

2.  Find out who introduced the incorrectly licensed files.

3.  Find out if the files are actually needed.

4.  Find a version under an acceptable license.

5.  Seek permission to change the licenses.

6.  Rewrite the software.

##### Finding Incorrectly Licensed Files

Using license scanners, it is possible to find out the license of
source code files. There are many license scanners. Some of them are
proprietary (e.g., Black Duck Protex, Palamida, Whitesource,
Protecode, FOSSID, and FOSSA); others are open source (FOSSology,
Scancode). None of the license scanners do a perfect job, because
license scanning is difficult to do correctly, and there are many
source code files that use non-standard license headers, or have no
license text in a header at all.

For code you wrote yourself, there are ways to make license
identification easier for license scanners. One example is to use SPDX
short identifiers. SPDX is a simple, standard way of describing
package contents and has seen adoption across the industry for its
management of licensing descriptions. You can learn more about SPDX at
**https://spdx.org/**.

##### Finding Who Introduced Incorrectly Licensed Files

After discovering incorrectly licensed files, it is important to
understand who introduced them. It usually boils down to one of two
sources:

1.  The upstream project.

2.  The ODM/chipset manufacturer.

If you identify a situation where open source code does not have a
correct license statement, many upstream projects will appreciate
having this pointed out. Fixing the issues at the source provides
better information for everyone. Please note that in the case of the
Linux kernel, there are many files that do not have a correct license
statement. However, existing files have been in the Linux kernel for
many years and are not considered a problem. Your concern is to find
new rather than known files. A method to quickly filter the known
files is described here: **https://lwn.net/Articles/552758**

Sometimes people or companies have a list of "trusted" upstream
projects. They regard all code originating from that project to be
ready for use without further review. What projects will be trusted
and for what reasons is a decision that will differ per person or
organization. An illustrative rule of thumb is that the Linux kernel
obtained directly from kernel.org may be trusted but a random kernel
fork on GitHub may not.

##### Finding Out If Files Are Actually Needed

If the problematic files were not introduced by the upstream project
(whether the upstream project is to be trusted is a separate topic for
discussion) then it might be wise to remove the files. As an example,
if a file for a Microsoft Windows driver is present in the Linux
kernel source code tree, it can be safely removed.

Similarly, if a file is not used in the final binary or during the
build process, it can be safely removed. One way to check is by
removing it from the source code tree and rebuilding the binary again
(after cleaning up build artifacts from previous builds, of course,
and

doing a fully clean build). If the resulting binary is identical (or
"close enough"), then the file can safely be removed.

**Finding a Version of a Driver Under an Acceptable License** In the
embedded Linux industry, many mistakes have been made in the past
regarding incorrectly licensed source code files, particularly for
drivers. Some vendors have already relicensed newer versions of the
driver under acceptable licenses. However, ODMs frequently still ship
old driver versions, either because they are unaware of the updates or
because they don't want to test if the new driver works properly with
their components.

##### Seeking Permission to Change the Licenses

Changing a license is usually the most difficult solution, but
sometimes the only option left, apart from rewriting the software. If
a file is used and does not have the correct license, you should ask
the copyright owner to relicense the file. Some copyright owners might
not be willing to, but other manufacturers or developers might not
object (see the previous section).


