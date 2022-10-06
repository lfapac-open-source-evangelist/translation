# Meet Hyperledger Solang, a portable Solidity compiler
By Sean Young, Lucas Steuernagel, Cyrill Leutwiler September 12, 2022 Blog, Hyperledger Solang 
# 让我们来认识一下超级账本Solang，一个可移植的Solidity编译器 
作者：Sean Young、Lucas Steuernagel、Cyrill Leutwiler | 2022年9月12日 | 博客，超级账本Solang

We are excited to announce that Solang has been accepted as the latest Hyperledger® project and has been renamed as Hyperledger Solang™. The project is now formally being incubated as a top-level project by the Hyperledger Foundation™, hosted by the Linux Foundation, and has support from multiple sponsors. 

我们很高兴地宣布，Solang已被接受成为最新的超级账本®项目，并已更名为超级账本Solang™。该项目现在正式成为Linux基金会旗下的超级账本基金会™孵化的顶级项目，并且已经得到多个赞助商的支持。

Solang started in the Hyperledger Labs since we always wanted to work together with other Hyperledger projects. The very first ledger we supported was Hyperledger Burrow. Being part of Hyperledger Labs was a great way to give the project more visibility and ensure we could make use of the great tooling provided by Hyperledger. After tapping into those resources, Hyperledger Solang, a tool that enables smart contract portability, is now the newest Hyperledger project. 

Solang项目是在超级账本实验室中成立的，因为我们一直想与其他超级账本项目合作。我们支持的第一个账本是超级账本Burrow。成为超级账本实验室的一员是提高项目知名度的好方法，确保我们可以使用超级账本提供的出色工具。在利用了这些资源之后，超级账本Solang——一种支持智能合约可移植性的工具，成了目前最新的超级账本项目。

## What is Hyperledger Solang
Hyperledger Solang is a compiler for Solidity source code and targets different blockchains.

## 什么是超级账本Solang？
超级账本Solang是Solidity源代码的编译器，面向不同的区块链。

The idea for Solang arose from early work on Hyperledger Burrow. We were trying to do things with Solidity that were not possible with the existing Ethereum Solidity compiler. Since that compiler is specific for Ethereum, there was no interest in supporting features for Hyperledger Burrow. From that problem, a portable Solidity compiler that could support many blockchains was born, making it possible to have different features depending on which blockchain is being targeted. 

Solang的想法来自早期超级账本Burrow的工作。我们试图用Solidity做一些现有以太坊Solidity编译器无法做到的事情。由于该编译器是针对以太坊的，因而不支持超级账本Burrow的特性。从这个问题出发，一个可以支持许多区块链的可移植Solidity编译器诞生了，它可以根据不同目标区块链而具备不同的功能。

The Solidity programming language is the most popular language for smart contracts, and there is clear interest from many blockchains to have support for it. Although some blockchains emulate an EVM environment to maintain compatibility with Solidity built with Solc, they cannot access missing features from Ethereum that an emulated EVM environment cannot provide, such as cryptographic functions, like blake2, zero-knowledge proof and the ability to call native contracts or be called by them. Hyperledger Solang offers the ability to compile Solidity to native execution environments other than the EVM, allowing the language many new possibilities and innovations. 

Solidity编程语言是最流行的智能合约语言，许多区块链显然对支持它都很感兴趣。尽管一些区块链通过模拟EVM环境来保持与Solc构建的Solidity的兼容性，但它们无法访问以太坊来获取那些因模拟EVM环境无法提供而缺失的特性，例如加密函数（blake2）、零知识证明和调用本地合约或被本地合约调用的能力。超级账本Solang提供将Solidity编译到本地执行环境(而不是EVM)的能力，为该语言提供了许多新的可能性和创新。

Currently, Hyperledger Solang supports Solana and Polkadot (Substrate). 

目前，超级账本Solang支持Solana协议和Polkadot（Substrate开发框架）协议。

## How to use Hyperledger Solang
Hyperledger Solang compiles Solidity into a native contract and a corresponding metadata file. Deploying a compiled contract needs tooling from the corresponding target blockchain. 

## 如何使用超级账本Solang
超级账本Solang将Solidity编译为一个本地合约和一个相应的元数据文件。部署一个编译好的合约需要对应目标区块链的工具。

First follow the installation guide for installing Solang: https://solang.readthedocs.io/en/latest/installing.html and then follow the steps for Solana https://solang.readthedocs.io/en/latest/targets/solana.html or Substrate https://solang.readthedocs.io/en/latest/targets/substrate.html 

首先按照安装指南安装Solang：https://solang.readthedocs.io/en/latest/installing.html，然后按照步骤安装Solana（https://solang.readthedocs.io/en/latest/targets/solana.html）或Substrate（https://solang.readthedocs.io/en/latest/targets/substrate.html）

For Solana, we have the @solana/solidity npm package for deploying and interacting with Solang compiled contracts. To compile Solidity for Solana, use: 

对于Solana，我们有@solana/solidity npm包，用于部署Solang编译的合约并与之交互。要为Solana编译Solidity，请使用:

### $ solang compile –target solana source.sol

### $ solang compile –target solana source.sol

This will produce an ABI file for each contract, and a single binary contract called `bundle.so`. 

这将为每个合约生成一个ABI文件，以及一个名为`bundle.so`的二进制合约。

For Polkadot or Substrate, the native @polkadot/api-contract npm package can be used. The command line for compiling Solidity for Substrate is: 

对于Polkadot或Substrate，可以使用本地的@polkadot/api-contract npm包。编译Solidity for Substrate的命令行是:

### $ solang compile –target substrate source.sol

### $ solang compile –target substrate source.sol

For each contract found in the file a `.contract` file is produced. 

对于在文件中发现的每个合约，都会产生一个`.contract`文件。

There are examples in the documentation and in the integration tests of how to run these contracts. 

在文档和集成测试中有关于如何运行这些合约的例子。

We also have a visual studio code extension, which provides real-time compiler warnings and errors as well as type information when you hover over variables and functions. 

我们还有一个visual studio代码扩展功能，当你把鼠标悬停在变量和函数上时，它会提供实时的编译器警告和错误以及类型信息。

## What's next

## 下一步是什么

1.Language support: Hyperledger Solang already supports nearly all the syntax that Ethereum Solidity 0.8 supports. There are a few minor exceptions like slices. We intend to keep up with the latest Solidity developments as they are released. 

1.语言支持：超级账本Solang已经支持以太坊Solidity 0.8所支持的几乎所有语法。也有一些小的例外，比如切片。我们打算在Solidity开发的最新动态发布后，及时了解它们。

2.Stabilized targets: Both the Solana and Substrate targets are undergoing stabilization and are expected to be finished by the end of the year. Once this happens, we expect many more users. We are aware of blockchain development teams wanting to use Hyperledger Solang in production, which makes this point a priority. 

2.稳定的目标：Solana和Substrate这两项目标都在稳定中，预计将于今年年底完成。一旦稳定，我们预计会有更多的用户。我们知道区块链开发团队希望在生产中使用超级账本Solang，所以这一点是头等大事。

3.EVM support: Hyperledger Solang used to have an ewasm target. However, since ewasm is no longer going to happen on Ethereum, this target has been dropped. In fact, we have bigger plans: we renamed most of the ewasm target to EVM, and hope to have EVM support in the future. An EVM target would be an interesting development because it would bring Solang to Ethereum and any other EVM based chain. Many projects that are already developing for Ethereum are interested in running their contracts in multiple environments, using a single tool that compiles for EVM and other blockchains. We are considering running a Hyperledger mentorship for this difficult but rewarding task next year. 

3.EVM支持：超级账本Solang过去有一个ewasm目标。然而，由于以太坊不再使用ewasm，这个目标已经被放弃了。事实上，我们有更大的计划：我们将大部分ewasm对象重命名为EVM，并希望未来获得EVM支持。EVM对象将是一个有趣的变化，因为它会把Solang引入以太坊和任何其他基于EVM的链中。许多已经在为以太坊做开发的项目都有兴趣在多个环境中运行他们的合约，这要通过利用为EVM和其他区块链编译的单独工具来完成。我们正在考虑明年为这一困难但有意义的任务举办一次超级账本导师培训活动。

4.Hyperledger projects: We have had conversations with Hyperledger Sawtooth, Hyperledger Fabric, and Private Data Objects, which expressed interest in having Solidity support, but there is still work to be done to implement a new target in Solang for these projects. 

4.超级账本项目：我们已经与超级账本Sawtooth、超级账本Fabric和私有数据对象进行了对话，它们表示有兴趣使用Solidity支持，但在Solang中实施这些项目的新目标尚需时日。

## Where to get more information and how to get involved
Please head to the github documenation page https://github.com/hyperledger-labs/solang documentation page https://solang.readthedocs.io/en/latest/

## 从哪里获得更多信息以及如何参与其中？
请前往github文档页面查看https://github.com/hyperledger-labs/solang文档页面https://solang.readthedocs.io/en/latest/

If you want to get involved, we have a curated list of good first issues to work on in our github issue tracker: https://github.com/hyperledger/solang/labels/good%20first%20issue. 

如果你想参与其中，我们在github问题追踪器中有一个仔细挑选的初级问题清单供你研究：https://github.com/hyperledger/solang/labels/good%20first%20issue。

We are always available on the #solang channel on the hyperledger discord, and we run a daily discord meeting at 13:30 UTC in #solang-meetup.  For more details, see the Hyperledger calendar of public meetings: https://wiki.hyperledger.org/display/HYP/Calendar+of+Public+Meetings. We look forward to welcoming you. 

你随时可以在超级账本discord的#solang频道中找到我们，我们每天13:30（UTC时间）会在#solang-meetup中开争端解决会议。如果你想要了解更多细节，请查看超级账本日历中的公开会议：https://wiki.hyperledger.org/display/HYP/Calendar+of+Public+Meetings。我们期待你的光临。
