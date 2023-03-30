
[]{#_bookmark22 .anchor}CHAPTER 4:

# Scenarios for Buying Software

## "Everything starts somewhere, although many physicists disagree."

TERRY PRATCHETT

## Context

When procuring devices or components from a third party to sell as part of your product, it is important to understand that the company offering the product in the market is responsible for the license compliance of the product. Often when a compliance problem arises, there is a conflict about who is responsible and who should bear the costs. This can lead to suppliers and downstream OEMs pointing fingers and blaming the other party. However, in the end, the company delivering the product to the market will likely be found responsible for ensuring compliance with the license.

It is also true that *fixing* compliance issues will be more expensive than *preventing* compliance issues. If the whole supply chain works together from the start to prevent these issues, costs for fixing issues can generally be kept low.

That being said, changing how current supply chains work is a multi-year effort. In this section, we will explore a few solutions that look into lowering risks for all parties in the supply chain.

## Scenario #1: Supply Chain Solutions For SoC Vendors

In most supply chains, the System on Chip (SoC) vendors have the biggest impact: They choose or build the software development kit and build a reference implementation that ODMs subsequently modify. If the SoC vendors get compliance right, then it is much easier for downstream recipients to comply with the license as well. Here are a few solutions that are worth considering:

1.  Pick a standard SDK instead of building your own SDK.

2.  Actively participate in the upstream software projects, and try to use as much "vanilla" software as possible.

3.  Have a third party check/audit license compliance.

#### Pick a Standard SDK

It is highly recommended that SoC vendors use a standard SDK instead of creating their own. From a license compliance perspective, the most compelling reason for this is that these standard SDKs often have mechanisms for easier license compliance built directly into the system. Plus, they have been reviewed by many people already and are supported by a much larger group of people than an in-house developed solution would be. Examples of standard SDKs are:

-   OpenWrt (and its offshoot LEDE)

-   Yocto

-   buildroot

-   Android

The additional benefit is that the so-called "scripts to control compilation and installation" are all available in the SDK.

#### Actively Participate in Upstream Projects

Many people are triggered to complain about license compliance status if they cannot make things work using standard software. Actively participating in upstream projects and supporting hardware in "vanilla" projects has two benefits:

1.  People will be less likely to complain, since they can simply work around any issues. Of course, this is not an excuse to not take any other measures for license compliance.

2.  People will be more inclined to send a "friendly ping" to point out any issues than to complain loudly. Of course, participating

[]{#_bookmark24 .anchor}engineers should know what to answer, and how to interact with communities at large, and be in sync with other departments and players (for example, the legal department).

Some organizations are more than willing to help SoC vendors to merge their code upstream and help them become effective open source citizens. For the Linux kernel, there is, for example, the Long Term Support Initiative (LTSI) run by The Linux Foundation. For vendors in the ARM ecosystem, there is also Linaro.

#### Third Party Audits

It might be useful to let a third party check for any issues in new SDKs before they are shipped downstream, and to incorporate any findings into the work process. The OpenChain Project (**[http://](http://openchainproject.org/) [openchainproject.org](http://openchainproject.org/)**) is a good start. Another hands-on, practical approach to consider is the OSADL License Compliance Audit ([**http://www.osadl.org**](http://www.osadl.org/)).

## Scenario #2: Supply Chain Solutions for ODMs

The Original Design Manufacturers (ODMs) are often in between the System on Chip (SoC) vendors and the companies that deliver products into the market. They are also the first point of contact for companies if something is wrong. As referenced earlier in this book, the technical choices made by the SoC vendor has one of the biggest impacts on any open source compliance situation. An ODM can help pick the right SoC vendor or make sure that any (possible) mistakes from SoC vendors do not impact them. Examples of actions that an ODM can take are:

1.  Work with SoC vendors that use standard SDKs or whose chipsets are well supported in standard SDKs (such as

[]{#_bookmark25 .anchor}OpenWrt) so the SDK you use is a standard SDK and not a SoC-specific SDK.

2.  Work with SoC vendors that use a SDK that has been certified by the OSADL license compliance audit or similar.

3.  Use contracts to push compliance damages to the SoC vendor.

4.  Actively participate in upstream projects.

5.  Let a third party audit a reference design.

## Scenario #3: Supply Chain Solutions for Others

When procuring devices, there are a few things that can be done to reduce compliance risk.

First and foremost, you can engage with other open source stakeholders who are addressing similar challenges. A great place to start is the OpenChain Project. OpenChain focuses on identifying common best practices in compliance programs that should be applied across a supply chain for efficient and effective compliance with open source licenses. It provides (free of charge) comprehensive specification, conformance, and curriculum material suitable for small, medium, and large enterprises. You can learn more at **[www.openchainproject.or](http://www.openchainproject.org/)g.**

Here are some direct measures you may wish to consider:

1.  Select only ODMs that use a solution from a chipset vendor that uses a standard SDK or have replaced the SoC SDK with a standard SDK.

2.  Explicitly ask for use of a certified/audited SDK.

3.  Use contracts to push damages upstream.

4.  Audit a sample before purchasing, or contract a third party to do this.

Doing an audit before a purchase is an interesting strategy to see how much risk a certain device will bring with it. This is, however, easier said than done. Very few ODMs are prepared to hand out samples; even when there are firm orders for tens of thousands of devices there are usually only a few samples (one or two) available for testing. Before a firm order has been placed, it will be very unlikely that an ODM will give out samples, fearing that the device will be taken to a cheaper competitor to be cloned.

One solution to this would be to let a third party do an audit and send a status report only to the purchaser, who can then use it to calculate its risk.

