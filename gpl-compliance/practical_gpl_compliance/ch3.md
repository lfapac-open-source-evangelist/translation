[]{#_bookmark17 .anchor}CHAPTER 3:

# Scenarios for Releasing Software

## "'Did I do anything wrong today,' he said, 'or has the world always been like this and I've been too wrapped up in myself to notice?'"

DOUGLAS ADAMS

## Scenario #1: Software On A Device/Offline Distribution

Software is distributed onto a device, for example, flashed onto a device. There are two ways to comply with the license:

1. Deliver the complete and corresponding source code with the device, for example on a CD, DVD, or other medium. In some cases it might also be possible to include it on the device itself (given enough flash or storage space), but what is important is that the user should be able to retrieve the source code as well.

2. Add a written offer, valid for at least three years (for GPLv2; for GPLv3 this period might be longer, depending on how long the device is supported), to any third party for the source code.

The benefit of the first method is that there are no further obligations, as all the necessary information (license texts, copyright information, and so on) are included in the source code archive, as long as it is complete and corresponding. The drawback is that often the source is not complete and corresponding, and it is difficult to correct any mistakes discovered after creating the CD, DVD, or image. One situation that often arises is that just before shipping, a new firmware is flashed onto the device, but the CD/DVD distributed alongside it contains the GPL source code for a prior firmware revision. This happens because there was not enough time to create a new CD/DVD. Issues like this can potentially be addressed with a good Over- The-Air update process. [See Flowchart #4 on page 61](#_bookmark32) for one high-level example.

With the written offer it is easier to correct any mistakes later on, but there are a few drawbacks: It is necessary to keep an []{#_bookmark19 .anchor}infrastructure to fulfill the written offer (someone has to be responsible to create a source code CD/DVD and ship it) and there are also some legal gray areas pertaining to whether or not license statements and copyright statements should be delivered with the binary. Not everyone agrees on this, but there are increasingly more copyright holders who insist on having the copyright notices from the source code delivered with the binary. As previously stated, when delivering source code with the product this requirement has already been fulfilled, but when shipping a written offer, this is not the case. Extracting copyright notices from source code is awkward. FOSSology is one tool that can help, but additional checking may be required.

It might be best to choose shipping the source code with the device, with an extra optional written offer with information on how to ask for the source code. This way, it can be argued (if there is an error with the source code shipped) that the preferred way always has been the written offer and that the source code was mainly to provide license texts and copyright statements. If the source code is not complete and corresponding it might be incorrect, but not materially incorrect.

Please note that this scenario is independent of how firmware on a device is updated, which the next scenarios will dig into.

## Scenario #2: Manual Download From Website

When providing a firmware update on a website (independent of how the compliance for an initial device delivery is done --- see the previous scenario for that) there are often three possible choices to make:

1. []{#_bookmark20 .anchor}Provide the source code with the firmware update in a single archive. This would fulfill the requirements of GPLv2, section 3a.8

2. Include a written offer, as per GPLv2, section 3b.9

3. Provide a separate download next to the firmware, which would count as "equivalent access."

The same benefits and drawbacks apply as in Scenario #1, although it is much easier to correct mistakes (in choices 1 and 3) than when shipping a physical device, as it is easier to change the download.

Keep in mind that when offering source code online for download, there is always the possibility that a new website will be created later. If the web team is not aware that source code downloads were a requirement, a company may fall out of compliance after a new website is rolled out. It is important to note this download- requirement in the website change procedures and process.

## Scenario #3: Automatic/Over The Air Updates

For automatic updates and "over the air" (OTA) updates, shipping source code is almost impossible. This scenario for delivering binaries was likely not available when the GPLv2 was drafted in 1991. Automatic updates surgically update a few programs or files, and the size of the source code delivered to a device would dwarf the size of the executable (for example, the Linux kernel). Also, on many devices that can receive OTA updates it would be hard to access the downloaded source code or do anything with

8. See [**https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html**](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

9. Ibid.

[]{#_bookmark21 .anchor}it. Another problem is that there might simply not be enough space available on the device, and distribution of the source code might fail.

For OTA updates, the practical solution is to include a written offer. Please note that this is independent of how the device was originally shipped (source code, or written offer).

How and where copyright notices and license texts should be delivered can be a real challenge, especially if the device does not offer any way to interact with the user (display, web interface, and so on). If that is the case it might be best to point the user to a website and offer the information there instead of on the device (which would be futile as the user has no access to it) and point out that the license text is from 1991 and that OTA delivery models were not available then.

## Scenario #4: Field Engineer Applied Updates

In some cases (for example, industrial automation) it is common that a firmware update is applied by a field engineer of the manufacturer, or by a support firm. It is recommended to have the field engineer bring a CD/DVD with the source code and hand it over after the firmware update has been completed.
