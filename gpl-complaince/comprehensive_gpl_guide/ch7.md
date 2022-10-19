
[]{#_bookmark69 .anchor}**CHAPTER 7**

DEFENDING FREEDOM ON MANY FRONTS

Chapters [3](#_bookmark42) and [5](#_bookmark56) presented the core
freedom-defending provisions of GPLv2, which are in GPLv2 0--3. GPLv2
4--7 of the GPLv2 are designed to ensure that GPLv2 0--3 are not
infringed, are enforceable, are kept to the confines of copyright law
but also not trumped by other copyright agreements or components of
other entirely separate legal systems. In short, while GPLv2 *§§*0--3
are the parts of the license that defend the freedoms of users and
programmers, GPLv2 *§§*4--7 are the parts of the license that keep the
playing field clear so that *§§* 0--3 can do their jobs.

## GPLv2 §4: Termination on Violation

GPLv2 4 is GPLv2's termination clause. Upon first examination, it
seems strange that a license with the goal of defending users' and
programmers' freedoms for perpetuity in an irrevocable way would have
such a clause. However, upon further examination, the difference
between irrevocability and this termination clause becomes clear. (See
[7.4](#gplv2-irrevocability) for expanded discussion of GPLv2
irrevocability.)

The GPL is irrevocable in the sense that once a copyright holder
grants rights for someone to copy, modify and redistribute the
software under terms of the GPL, they cannot later revoke that grant.
Since the GPL has no provision allowing the copyright holder to take
such a prerogative, the license is granted as long as the copyright
remains in effect.[^1^](#_bookmark71) The copyright holders have the
right to relicense the same work under different licenses (see Section
[12.2](#business-models) of this tutorial), or to stop distributing
the GPLv2'd version (assuming GPLv2 3(b) was never used), but they may
not revoke the rights under GPLv2 already granted.

In fact, when an entity loses their right to copy, modify and
distribute GPL'd software, it is because of their *own actions*, not
that of the copyright holder. The copyright holder does not decide
when GPLv2 4 termination occurs (if ever); rather, the actions of the
licensee determine that.

Under copyright law, the GPL has granted various rights and freedoms
to the licensee to perform specific types of copying, modification,
and redistribution. By default, all other types of copying,
modification, and redistribution are prohibited. GPLv2 4 says that if
you undertake any of those other types (e.g., redistributing
binary-only in violation of GPLv2 3), then all rights under the
license --- even those otherwise permitted for those who have not
violated --- terminate automatically.

GPLv2 4 makes GPLv2 enforceable. If licensees fail to adhere to the
license, then they are stuck without any permission under to engage in
activities covered by copyright law. They must completely cease and
desist from all copying, modification and distribution of the GPL'd
software.

^1^[]{#_bookmark71 .anchor}In the USA, due to unfortunate legislation,
the length of copyright is nearly perpetual, even though the
Constitution forbids perpetual copyright.

At that point, violating licensees must gain the forgiveness of the
copyright holders to have their rights restored. Alternatively, the
violators could negotiate another agreement, separate from GPL, with
the copyright holder. Both are common practice, although Chapter
[13.3](#understanding-whos-enforcing) explains further key differences
between these two very different uses of GPL.

## GPLv2 §5: Acceptance, Copyright Style

GPLv2 5 brings us to perhaps the most fundamental misconception and
common confusion about GPLv2. Because of the prevalence of proprietary
software, most users, programmers, and lawyers alike tend to be more
familiar with EULAs. EULAs are believed by their authors to be
contracts, requiring formal agreement between the licensee and the
software distributor to be valid. This has led to mechanisms like
"shrink-wrap" and "click-wrap" as mechanisms to perform acceptance
ceremonies with EULAs.

The GPL does not need contract law to "transfer rights." Usually, no
rights are transferred between parties. By contrast, the GPL is
primarily a permission slip to undertake activities that would
otherwise have been prohibited by copyright law. As such, GPL needs no
acceptance ceremony; the licensee is not even required to accept the
license.

However, without the GPL, the activities of copying, modifying and
distributing the software would have otherwise been prohibited. So,
the GPL says that you only accepted the license by undertaking
activities that you would have otherwise been prohibited without your
license under GPL. This is a certainly subtle point, and requires a
mindset quite different from the contractual approach taken by EULA
authors.

An interesting side benefit to GPLv2 5 is that the bulk of users of
Free Software are not required to accept the license. Undertaking fair
and unregulated use of the work, for example, does not bind you to the
GPL, since you are not engaging in activity that is otherwise
controlled by copyright law. Only when you engage in those activities
that might have an impact on the freedom of others does license
acceptance occur, and the terms begin to bind you to fair and
equitable sharing of the software. In other words, the GPL only kicks
in when it needs to for the sake of freedom.

While GPL is by default a copyright license, it is certainly still
possible to consider GPL as a contract as well. For example, some
distributors chose to "wrap" their software in an acceptance ceremony
to the GPL, and nothing in the GPL prohibits that use. Furthermore,
the ruling in *Jacobsen v. Katzer, 535 F.3d 1373, 1380 (Fed.Cir.2008)*
indicates that **both** copyright and contractual remedies may be
sought by a copyright holder seeking to enforce a license designed to
uphold software freedom.

## GPLv2 §6: GPL, My One and Only

A point that was glossed over in Section
[7.1's](#gplv2-4-termination-on-violation) discussion of GPLv2 4 was
the irrevocable nature of the GPL. The GPLv2 is indeed irrevocable,
and it is made so formally by GPLv2 6.

The first sentence in GPLv2 6 ensures that as software propagates down
the distribution chain, that each licensor can pass along the license
to each new licensee. Under GPLv2 6, the act of distributing
automatically grants a license from the original licensor to the next
recipient. This creates a chain of grants that ensure that everyone in
the distribution has rights under the GPLv2. In a mathematical sense,
this bounds the bottom --- making sure that future licensees get no
fewer rights than the licensee before.

The second sentence of GPLv2 6 does the opposite; it bounds from the
top. It prohibits any licensor along the distribution chain from
placing additional restrictions on the user. In other words, no
additional requirements may trump the rights and freedoms given by
GPLv2.

The final sentence of GPLv2 6 makes it abundantly clear that no
individual entity in the distribution chain is responsible for the
compliance of any other. This is particularly important for
noncommercial users who have passed along a source offer under GPLv2
3(c), as they cannot be assured that the issuer of the offer will
honor their GPLv2 3 obligations.

In short, GPLv2 6 says that your license for the software is your one
and only copyright license allowing you to copy, modify and distribute
the software.

[GPLv2]{.underline} []{#_bookmark74 .anchor}[*§*6 is GPLv2's
"automatic down]{.underline}stream licensing"
provision[^2^](#_bookmark74). Each time you redistribute a GPL'd

2This section was substantially expanded for clarity and detail in
[GPLv3 *§*10.](#gplv3-10-explicit-downstream-license)

program, the recipient automatically receives a license from each
original licensor to copy, distribute or mod- ify the program subject
to the conditions of the license. The redistributor need not take any
to ensure the downstream recipient's acceptance of the license terms.
This places every copyright holder in the chain of descent of the code
in legal privity, or direct relationship, with every downstream
redistributor. Two legal effects follow. First, downstream parties who
remain in compliance have valid permissions for all actions (including
modification and redistribution) even if their immediate upstream
supplier of the software has been terminated for license
violation[^3^](#_bookmark77). Downstream's licensed rights are not
dependent on compliance of their upstream, because their licenses
issue directly from the copyright holder. Second, automatic termi-
nation cannot be cured by obtaining additional copies from an
alternate supplier: the license permissions emanate only from the
original licensors, and if they have automatically terminated
permission, no act by any intermediate license holder can restore
those terminated rights[^4^](#_bookmark78).

## GPLv2 Irrevocability

This section digresses briefly to examine the manner in which GPLv2
4--6 interact together to assure that the license grant is
irrevocable. There are two legal theories why a contributor cannot
terminate their license grant. First is an argument that the text of
the GPL prevents it; second is that a contributor would be estopped
from succeeding on an infringement claim for continued use of the code
even if it wasn't removed.

### The text of the GPLv2

The GPLv2 have several provisions that, when taken together, can be
construed as an irrevocable license from each contributor. First, the
GPLv2 says "by *modifying* or distributing the Program (or any work
based on the Program), you indicate your acceptance of this License to
do so, and all its terms and conditions for copying, distributing or
modifying the Program or works based on it" (GPLv2 5, emphasis added).
A contributor by definition is modifying the code and therefore has
agreed to all the terms in the GPLv2, which includes the web of
mechanisms in the GPLv2 that ensure the code can be used by all.

More specifically, the downstream license grant says "the recipient
automatically receives a license from the original licensor to copy,
distribute or modify the Program subject to these terms and
conditions." (GPLv2 6). So in this step, the contributor has granted a
license to the downstream, on the condition that the downstream
complies with the license terms.

That license granted to downstream is irrevocable, again provided that
the downstream user complies with the license terms: "\[P\]arties who
have received copies, or rights, from you under this License will not
have their licenses terminated so long as such parties remain in full
compliance" (GPLv2 4).

Thus, anyone downstream of the contributor (which is anyone using the
contributor's code), has an irrevocable license from the contributor.
A contributor may claim to revoke their grant, and subsequently sue
for copyright infringement, but a court would likely find the
revocation was ineffective and the downstream user had a valid license
defense to a claim of infringement.

Nevertheless, for purposes of argument, we will assume that for some
reason the GPLv2 is not enforceable against the
contributor[^5^](#_bookmark79), or that the irrevocable license can be
revoked[^6^](#_bookmark80). In that case, the application

^3^ []{#_bookmark77 .anchor}While this is legally true, as a practical
matter, a failure of "complete, corresponding source" (CCS)
provisioning by an upstream could make it effectively impossible for a
downstream party to engage in a commercial redistribution pursuant to
[]{#_bookmark78 .anchor}[GPLv2 3(a--b).](#gplv2-3-producing-binaries)
( [18.2](#upstream-providers) in the Compliance Guide portion of this
tutorial discussed related details.)

^4^While nearly all attorneys and copyleft theorists are in agreement
on this point, German copyleft legal expert [Till
Jaeger](http://www.jbb.de/en/attorneys/till-jaeger/) vehemently
disagrees. Jaeger's position is as follows: under German copyright
law, a new copy of GPL'd software is a "fresh" license under GPL, and
if compliance continues from that point further, the violator's
permissions under copyright law are automatically restored,
notwithstanding the strict termination provision in [GPLv2
4.](#gplv2-4-termination-on-violation) However, in practice, this
issue is only salient with regard to [proprietary
relicensing](#business-models) business models, since other copyright
holders typically formally restore distributions rights once the only
remaining compliance issue is "you lost copyright permission due to
GPLv2 4". Therefore, the heated debates, which have raged between
Jaeger and almost everyone else in the copyleft community for nearly a
decade, []{#_bookmark79 .anchor}regard an almost moot and wholly
esoteric legal detail.

^5^For example, the argument has been made that there may be a failure
of consideration on the part of the contributor. While *Jacobsen v.
Katzer*, 535 F.3d 1373 (Fed. Cir. 2008) is accepted as holding that
there is consideration received by the contributor in a FOSS license,
the posture of the case was one where the contributor advocated for
the theory, not against it. The author is not aware of any other
decisions that have analyzed the question in any depth, so it perhaps
could be challenged in []{#_bookmark80 .anchor}the right factual
situation.

^6^A contract without a definable duration can be terminated on
reasonable notice. *Great W. Distillery Prod. v. John A.*

of promissory estoppel will likely mean that the contributor still
cannot enforce their copyright against downstream users.

### Promissory estoppel

"Promissory estoppel" is a legal theory that says, under some
circumstances, a promise is enforceable against the promisee even
after the promisee tries to renege on the promise. The test for how
and when promissory estoppel applies differs from state to state, but
generally where there is a "promise which the promisor should
reasonably expect to induce action or forbearance on the part of the
promisee or a third person and which does induce such action or
forbearance is binding if injustice can be avoided only by enforcement
of the promise."[^7^](#_bookmark84) Breaking it down, it is:

1.  where there is a clear and definite promise;

2.  where the promisor has a reasonable expectation that the offer will
    > induce action or forbearance on the part of the promisee;

3.  which does induce actual and reasonable action or forbearance by the
    > promisee; and

4.  which causes a detriment which can only be avoided by the
    > enforcement of the promise.

In this case, the promisor is the contributor. This should be an easy
standard to meet in any widely used software.

1.  The promise is contained in the GPL, which is a promise that one can
    > continue to use the licensed software as long as the terms of the
    > license are met.

2.  A contributor knows that there is a broad user base and users
    > consume the software relying on the grant in the GPL as assuring
    > their continued ability to use the software (one might even say it
    > is the *sine qua non* of the intent of the GPL).

3.  Users do, in fact, rely on the promises in the GPL, as they ingest
    > the software and base their businesses on their continued ability
    > to use the software.

4.  Whether the user will suffer detriment is case-specific, but using
    > Linux, a software program that is often fundamental to the
    > operation of a business, as an example, the loss of its use would
    > have a significantly detrimental, perhaps even fatal, effect on
    > the continued operation of the business.

    1.  ### Conclusion

Whether as a matter of a straightforward contractual obligation, or as
a matter of promissory estoppel, a contributor's attempt to revoke a
copyright license grant and then enforce their copyright against a
user is highly unlikely to succeed.

## GPLv2 §7: "Give Software Liberty or Give It Death!"

In essence, GPLv2 7 is a verbosely worded way of saying for
non-copyright systems what GPLv2 6 says for copyright. If there exists
any reason that a distributor knows of that would prohibit later
licensees from exercising their full rights under GPL, then
distribution is prohibited.

Originally, this was designed as the title of this section suggests
--- as a last ditch effort to make sure that freedom was upheld.
However, in modern times, it has come to give much more. Now that the
body of GPL'd software is so large, patent holders who would want to
be distributors of GPL'd software have a tough choice. They must
choose between avoiding distribution of GPL'd software that exercises
the teachings of

*Wathen Distillery Co.*, 10 Cal. 2d 442, 447, 74 P.2d 745, 747 (1937).
The term nevertheless can be a term of indefinite length
[]{#_bookmark84 .anchor}where its continuing effect is tied to the
conduct of the parties. *Id*.

^7^*Kajima/Ray Wilson v. Los Angeles Cty. Metro. Transp. Auth.*, 23
Cal. 4th 305, 310, 1 P.3d 63, 66 (2000), *citing*

Restatement (Second) of Contracts *§*90(1) (1979).

their patents, or grant a royalty-free, irrevocable, non-exclusive
license to those patents. Many companies have chosen the latter.

Thus, GPLv2 7 rarely gives software death by stopping its
distribution. Instead, it is inspiring patent holders to share their
patents in the same freedom-defending way that they share their
copyrighted works.

## GPLv2 §8: Excluding Problematic Jurisdictions

GPLv2 8 is rarely used by copyright holders. Its intention is that if
a particular country, say Unfreedonia, grants particular patents or
allows copyrighted interfaces (no country to our knowledge even
permits those yet), that the GPLv2'd software can continue in free and
unabated distribution in the countries where such controls do not
exist.

As far as is currently known, GPLv2 8 has very rarely been formally
used by copyright holders. Ad- mittedly, some have used GPLv2 8 to
explain various odd special topics of distribution (usually related in
some way to GPLv2 7). However, generally speaking, this section is not
proven particularly useful in the more than two decades of GPLv2
history.

Meanwhile, despite many calls by the FSF (and others) for those
licensors who explicitly use this section to come forward and explain
their reasoning, no one ever did. Furthermore, research conducted
during the GPLv3 drafting process found exactly one licensor who had
invoked this section to add an explicit geographical distribution
limitation, and the reasoning for that one invocation was not fitting
with FSF's intended spirit of GPLv2 *§*8. As such, GPLv2 *§*8 was not
included at all in GPLv3.

