AnonCreds, the most commonly used Verifiable Credential (VC) format in the world*, is now a Hyperledger project. Ledger agnostic and with a formal open specification, AnonCreds continues to evolve as a mature verifiable credential format with unique privacy-protecting capabilities. As a Hyperledger project, AnonCreds will have support to grow its code base and community on a global level with technical governance that fosters best open development and security practices.
As the Internet transitions to allowing people, organizations, and things to have greater control over the sharing of their credentials, protecting privacy is of paramount concern.
Hyperledger AnonCreds—short for “Anonymous Credentials”—is a type of VC that adds important privacy-protecting ZKP (zero-knowledge proof) capabilities to the core VC assurances. A core element of the Hyperledger Indy project for more than five years, AnonCreds is a mature, complete model and interactions set, with extensive support across Hyperledger Aries frameworks.
The creation of this project signifies the continued healthy evolution of an open source software project that was once monolithic and is now a set of well-defined independent components. 
Hyperledger AnonCreds is ledger-agnostic and client-agnostic. It is not tied to Hyperledger Indy or Aries. This makes it usable with other verifiable data registries/ledgers and verifiable credential client stacks. As a result, important  privacy-protecting capabilities become available to a much broader audience, and the underlying cryptography can evolve without affecting the features above it.
Additional benefits of using Hyperledger AnonCreds include:
Avoidance of identifiers: No correlatable identifiers are required in presenting data to a verifier. Correlatable identifiers may be applied in a use case specific manner.
Verifier assurances: Credentials are bound to the holder, so verifiers know that credentials presented together were all issued to the holder providing the presentation.
Minimal data sharing: Data to be shared by a holder to a verifier is minimized through the use of selective disclosure and ZKP predicates
Flexible formatting: Credentials and presentations can be formatted in the W3C VC Data Model standard format.
AnonCreds has joined the Hyperledger ecosystem with over 25 sponsors. The project consists of:
The AnonCreds Specification, managed by the Hyperledger AnonCreds Specification Working Group and with the potential of being submitted to an appropriate Standards organization
Ledger/Verifiable Data Registry-agnostic, open source code implementations of the AnonCreds specification, suitable for use with Hyperledger Aries and non-Aries agents
Guidance for creating ledger-specific AnonCreds Methods to write and resolve AnonCreds objects for specific ledgers
Documentation on AnonCreds suitable for all audiences, from business audiences to cryptographers
A test suite to verify adherence to the AnonCreds specification and the interoperability of AnonCreds implementations.
Next steps include evolving the existing AnonCreds Rust implementation to be friendlier to VDRs/ledgers other than Indy, wrapping up the v1.0 specification, and gaining compliance with the W3C Verifiable Credentials Data Model Standard.
If you’re interested in learning more about AnonCreds start with the Hyperledger AnonCreds project page. From there you can find how to join project discussions on Discord, add yourself to the project mailing list, find the AnonCreds repositories on GitHub, and join the AnonCreds Working Groups.
We welcome interest from all groups and organizations, including enterprises and standards organizations. We look forward to hearing from you!
*Source: godiddy.com combined “sov” (Indy) network volume
