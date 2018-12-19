数据分析和可视化工具，它提供完整的数据来源基础设施来维护数据的详细历史和演化信息。数据跟踪模块记录数据的原产地，数据的计算过程，以及衍生数据和经历的执行过程。

区块链技术依赖哈希函数计算，哈希函数可以在任何长度的数字信息的基础之上产生一个固定长度的字符串代码。Blockchain technology relies on hashing,
which consists of generating a code of a fixed
length for a given piece of digital information,
regardless of its length. Hashing is important
because it permits someone to verify, by
recalculating the hash that a given piece of
digital information is identical to the digital
information that was originally hashed. This
permits document authentication – proof
that a given document is the same one as the
one that was originally hashed. This is an
important feature of many blockchain systems.
A hash cannot be reverse-engineered to
discover the original document. The process
only works in one direction, from the original
document to the hash. 

Hyperledger incubates and promotes a
range of business blockchain technologies,
including distributed ledger frameworks,
smart contract engines, client libraries,
graphical interfaces, utility libraries and
sample applications. One of the distributed
frameworks is called Hyperledger Fabric
(“HLF”), which is an open-source project
within the Hyperledger umbrella project. HLF
is a modular, general-purpose, permissioned
blockchain system, which can also be seen as a
distributed operating system for permissioned
blockchains. 


On each block of the blockchain there are
two types of data: 1) a header that includes a
date stamp, the identity of the source of the
data (an address), and the previous block’s
header hash, called ‘the pointer’; and 2) the
payload, which is the data to be stored.
The header is not encrypted, only the payload
is normally encrypted. The hash in the header
is of earlier blocks to create the immutable
chain of blocks. The payload is generally a
description of the document (metadata) and
the hash representing the actual document.
A smart contract would operate as follows: when
X wants to upload a new document description
to the blockchain, the smart contract will create
a transaction by combining a description of the
document and its hash to form a payload and
add a header. The header plus payload equals a
transaction and a validated transaction equals
a block. Upon validation of the block, the smart
contract would then send the document itself to
the Y database system for storage. We assume
that the Y database is off the blockchain and
has limited access through the use of passwords
which can be time sensitive. The blockchain
transaction will be proof that the document
was uploaded at a given time, and anyone will
be able to verify that the document held in the
off-chain database is the same document as the
one referred to in the blockchain transaction.

A distributed ledger is a replicated, shared,
and synchronised digital data structure
maintained by consensus algorithm and
spread across multiple sites, countries,
and/or institutions.
Blockchain is a type of distributed ledger,
comprised of digitally recorded data in
packages called blocks which are linked
together in chronological order in a manner
that makes the data very difficult to alter
once recorded, without the alteration of all
subsequent blocks and a majority of the
network colluding together.
Each node on the network (generally)
contains a complete copy of the entire ledger,
from the first block created—the genesis
block—to the most recent one. Each block
contains a hash pointer as a link to a previous
block, a timestamp and transaction data.

Smart contracts use blockchain
technology. The term is used to describe
computer program code, maintained
on the various “nodes” constituting a
blockchain network that is capable of
facilitating, executing, and enforcing
the negotiation or performance of an
agreement upon the occurrence of predefined conditions.
The smart contract code executes on each
node and the resulting output is stored on
the blockchain. Where “tokens” of value
are involved, the smart contract code can
also automatically transfer these tokens
(and underlying value), thus effectively
enforcing the outcome of the smart
contract code