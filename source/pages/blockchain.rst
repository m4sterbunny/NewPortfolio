Blockchain & Web3
=================

.. topic:: Contents

    :ref:`Developer Docs <developerdocs>`

    :ref:`Yellow Papers <yellowpaper>`

    :ref:`White Papers <whitepaper>`

    :ref:`Articles <web3Articles>`

    :ref:`Clients <clients>`


.. _novice: http://tomaltman.com/brave-new-blockchain-world/

.. _developer: https://www.talent.io/p/fr-blog/elliptic-curves-and-bitcoin

.. _StarkWareSite: https://starkware.co

.. # lite: https://ultron.foundation/static/media/ultron-light-paper.f3ca8a70f26766cb7c1e.pdf

.. # private repo https://github.com/starkware-libs/starkex-docs-v3/pull/42/files

.. _StarkExV3: https://docs.starkware.co/starkex/index.html

.. _Starknet: https://starkware.co/starknet/

.. _Cairo: https://cairo-lang.org/docs/hello_starknet/index.html

.. _TXLabs: https://www.txlabs.org/

.. _Fluidity: https://medium.com/@FluidityProtocol

.. _NeonEVM: https://neonevm.org/whitepaper.pdf

.. _Ultron: https://media.ultron.foundation/file/ultron-landing/ultron-foundation-whitepaper.pdf

.. _PiChain: https://pichain-global.gitbook.io/whitepaper-pcm-ecosystem 

.. # YCLUB: https://docs.yclub.io/``

.. # Gone Legends: https://www.meta-legends.com/``

.. toctree::
   :maxdepth: 3
   :caption: Contents:

.. _developerdocs:

Web3 Developer Docs
-------------------

I was the lead or sole technical writer working with Product to build out the following developer documentation:

- `Neon EVM <https://neonevm.org/docs/quick_start>`_: Docusaurus
- `Qredo <https://developers.qredo.com>`_: MkDocs
- `Panther Protocol <https://docs.pantherprotocol.io/docs>`_: GitBook 

I also worked as part of a larger tech writing team at Consensys.

.. _consensys:

Consensys
*********

In my role as a Senior technical writer at Consensys I was part of the global technical writing team providing 24 hour support to Product. 

**Main initiative**

I was assigned responsibility to transition the MetaMask services to support interactive API docs, allowing users to make calls from directly from the docs, for example `eth_call <https://docs.metamask.io/services/reference/linea/json-rpc-methods/eth_call>`_.

To achieve this, I built out yaml-to-JSON-based Open RPC CICD for Linea as a proof of concept. I then expanded this to include Unichain, and began Solana for MetaMask::Infura.

This required me to: 
   * Leverage GPT to hack an extension to the Ethereum (open source) builder to accommodate multichain support (and, later, negotiate that DevOps fix this tech debt)
   * Collaborate with frontend team building out the JSON parser required to support these interactive docs: providing feedback on Figma, and reviewing their PRs
   * Move docs from markdown/mdx to yaml and replace boilerplate examples with working examples that run successfully onchain
   * Collaborate with QA to integrate CICD tests for the examples used: negotiated widening the testing scope to the entire JSON
   * Negotiate a reduced method set to remove illogical methods from the Linea "supported" methods

**Developer Portals**

My team of technical writers in the Office of the CTO worked across multiple product lines. In my role I:

- Conduced peer reviews for open source and internal contributions
- Supported the Linea team to open-source the `Linea zkEVM <https://github.com/Consensys/linea-sequencer>`_
- Supported the Infura team to release new DIN network docs and duplicate that work on `MetaMask <https://docs.metamask.io/services/>`_
- Created and fixed Infura tutorials e.g. this `JWT example <https://docs.infura.io/tutorials/ethereum/authenticate-with-jwt>`_
- Fixed MetaMask tutorials, e.g. this `PR <https://github.com/MetaMask/metamask-docs/pull/1470/files>`_ updating this `tutorial <https://docs.metamask.io/services/tutorials/ethereum/send-a-transaction/send-a-transaction-ethers/>`_
- Updated the Ethereum docs 
- Became accepted as a Hyperledger `Besu <https://besu.hyperledger.org/>`_ open source project maintainer 

**Implementing Standards**

Tech writers are the communication layer for Product. We are also the final QA layer. To improve QA, I `implemented Vale <https://github.com/Consensys/docs-gha/tree/main/spelling>`_ as a linting layer in place of the default c-spell in Docusaurus. This allowed open source projects to access the (otherwise internal) style guide.

Skills: Technical Documentation · Kanban Methodologies · Negotiation · CICD

I was laid off from Consensys after 6 months along with the other new technical writer when they made 20% cuts to the employee base. 

.. _qredolink:

Qredo
*****

Qredo provided a multi-party computation Web3 wallet and vault enabling human::bot threshold signing for large institutions and banks. I led the Documentation Chapter, streamlined the existing, verbose, dev docs portal, applied clean-first and automate principles alongside a strong single-source-of-truth philosophy.

**Implementing Standards**

- Negotiated & agreed a JSON naming convention with engineering, FE, and BE teams
- Implemented linting using Vale (Spelling, Grammar, Term variants) and tools to validate API 3.0 spec
- Supported each API product with a downloadable, human-readable API spec (fka Swagger) compliant to OpenAPI 3.0

**Developer Portal**

- Negotiated & agreed on a tech stack with Marketing, Customer care, and Product for the new Documentation and Help Center site
- Contributed to porting existing content to new wire frame and populating new dev portal (1 month)
- Prioritized content production pipeline (6 months)
- Contributed to content: supported the release of 3 services as developer-facing documentation (3 months)
- Rendered & released API specs via dev portal
- Worked with DevOps to pipe API specs from master repos to communication portal
- First-pass iterate over 60% of existing dev portal content

**General Responsibilities**

- Supporting a developer audience with docs-as-code (in Markdown/static site)
- Developing thorough RESTful API specifications for Open API 3.0 with supporting documentation
- Managing Documentation Chapter as service desk liaising with Branding, Marketing, InfoSec, DevOps, and Product Managers
- Attending standup, creating and consuming tickets in Jira
- Recruitment of technical writers

Skills: Technical Documentation · Agile Methodologies · Negotiation · Scrum

I was laid off from Qredo after 6 months; they cut all bar 4 employees and sold the business. 

.. _neonlink:

Neon EVM
********

Neon EVM released the first EVM on Solana. As the sole technical writer, I led developer documentation: supporting mainnet launch. I built out their API documentation in Docusaurus with OpenRPC support for Neon EVM’s RPC API.

**General Responsibilities**

- Supporting a developer audience with docs-as-code (in Markdown/Docusaurus static site)
- Developing thorough Open RPC API specifications
- Managing docs as service desk to Dev Rels and Product Managers
- Producing :ref:`Video Documentation <Videos>` to encourage use of the product

**Marketing Responsibilities**

My dual role included supporting Marketing: I was the main editor and writer supporting launch, collaborating with the Marketing team to create content for various platforms (Blog, Medium, Twitter, etc.). Per our Brand24 data, total unique views 870 mil via Hokku PR, organic TUV at 1.8 billion. Examples of my writing are available in :ref:`Articles <web3Articles>`.

.. _ pantherlink:

Panther Protocol
****************

Panther Protocol is working toward zero-knowledge, compliant DeFi transactions. Similarly to Neon EVM, I supported Product with developer documentation and Marketing with a retail-accessible component to the same docs and retail-level articles.

**General Responsibilities**

- Updating GitBook docs using GitHub sync/Markdown, e.g. restructure and rewrite to provide a `single entry-point <https://docs.pantherprotocol.io/docs/panther-core/testnet#testnet-rewards>`_ for dApp community testers 
- :ref:`How-to videos <Videos>`: working with branding team for high-production Get Started for retail test dApp users (note, I have shared the pre-production version, not the music tracked and branded version).

**Marketing Responsibilities**

Examples of my writing are available in :ref:`Articles <web3Articles>`.

.. topic:: Note

  See my general portfolio for more :ref:`API-related developer docs <APIDocumentation>`

Docs Editor
***********

For StarkWare, I edited large components of the StarkExV3_ documentation. Writing in Markdown; building in GitBook.

I have also refactored the Cairo_ docs for Starknet_; now, if only the devs would actually merge the PR! Writing in rST; building with Sphinx/Read the Docs.

For `TX Labs`_, I introduced how to request and assign service nodes. Writing in Markdown; building in GitBook.

For Ethereum's docs, I improved several pages, e.g. the description around reorgs (see `PR <https://github.com/ethereum/ethereum-org-website/pull/3267>`_).

.. _yellowpaper:

Yellow Paper
-------------

- StarkWare's Cairo Language `yellow paper <https://eprint.iacr.org/2021/1063.pdf>`_: Editor

In stealth or already down:

- Blockless_ Network: Writer (draft 0)

.. _whitepaper:

White Paper
-----------

Available online:

- Ultron_ Foundation: Writer (up to final draft)
- NeonEVM_ Major overhaul: Writer/Editor (took V1 to V1.5)
- PiChain_ Global: Writer (up to final draft)


In stealth or already down:

- `Blockless`_ Network: Edit (draft 0)
- `MetaLegends`_ : Writer (draft 0)
- Lite paper: Ultron_ Foundation: Editor
- `YCLUB`_: Writer (draft 0 and first version)



.. _web3Articles:

Articles
--------

Written
*******

- Novice introduction for `Tom Altman`_: `A Brave New Blockchain World <http://tomaltman.com/brave-new-blockchain-world/>`_.
- Developer introduction to the `crypto behind Bitcoin <https://www.talent.io/p/fr-blog/elliptic-curves-and-bitcoin>`_ for `Talent`_.

Neon EVM
########

Product advocacy; examples include:

- `Parallel processing with an EVM <https://neonevm.org/blog/Parallel-processing-EVM>`_
- `Blockchain performance <https://neonevm.org/blog/which-performance-metrics-matter>`_
- `Bridging between Solana and Ethereum <https://neonevm.org/blog/bridging-the-gap-between-solana-and-ethereum>`_

Partnerships, examples include:

- `Ledger and Neon EVM <https://neonevm.org/blog/Neon-EVM-announces-Ledger-live-support>`_
- `Ledger and Poolz <https://neonevm.org/blog/partnership-poolz-finance>`_

Panther Protocol
################

Product advocacy; examples include:

- `How zAssets confer privacy <https://blog.pantherprotocol.io/product-insights-how-panther-zassets-enhance-user-privacy-in-defi/>`_
- `On chain privacy <https://blog.pantherprotocol.io/lets-end-the-taboo-of-on-chain-privacy/>`_

Consensys
#########

Best practices: 

- `API key management <https://www.infura.io/blog/post/best-practises-for-infura-api-key-management>`_

.. _web3editor:

Edited
******

- Client `StarkWare`_; examples include:

`StarkGate Alpha <https://medium.com/starkware/starkgate-alpha-35d01d21e3af>`_

`Starknet Alpha <https://medium.com/starkware/starknet-alpha-0-8-0-16e046e0f94b>`_

`The Rise of L2 native dApps <https://medium.com/starkware/a-thundering-herd-the-rise-of-l2-native-dapps-290598f6477f>`_

`Starknet Alpha Now on Mainnet <https://medium.com/starkware/starknet-alpha-now-on-mainnet-4cf35efd1669>`_

`Fractal Scaling From L2 to L3 <https://medium.com/starkware/fractal-scaling-from-l2-to-l3-7fe238ecfb4f>`_

`Redefining Scalability <https://medium.com/starkware/redefining-scalability-5aa11ffc5880>`_

.. - Client `Fluidity Protocol`_

.. `Fluidity Introduction <https://medium.com/@FluidityProtocol/let-us-introduce-you-to-fluiditydao-619d5bde885f>`_

.. `The Fluidity Protocol <https://medium.com/@FluidityProtocol/fluidity-and-how-it-works-afbbcfa5ce9f/>`_

.. `Fluidity Launch and Tokenomics <https://medium.com/@FluidityProtocol/prepare-for-takeoff-4098763669aa>`_

.. _clients:

Clients
-------

I distinguish "clients" from permanent employers such as Qredo, Consensys, Neon EVM, and Panther Protocol based on the contract I sign. Client essentially indicates a non-exclusive arrangement.

Blockless
*********

`TX Labs <TXLabs_>`_ is launching `Blockless <https://blockless.medium.com/>`_. The project is still in stealth mode. For the public-facing content, I assisted before the rebranding from TX Mesh. Since the rebrand, I have only worked on the documentation (not yet public).

My tasks included:

- white paper -- edit
- yellow paper -- write (draft 0)
- pitch deck -- edit/proof
- website content -- edit/proof
- Twitter content -- write
- FAQ -- edit/proof
- User/Developer documentation edit/write (pre-existing (excellent) internal developer information as a source)

.. Fluidity Protocol
.. *****************

.. Fluidity_ Protocol is launching a DeFi farming mechanism via their lending and protocol revenue-sharing DAO.

.. _metalink:

BrightNode
**********

`BrightNode <https://brightnode.io/>`_ engaged me to support clients with their white paper development. A selection of these include:

MetaLegends
###########

MetaLegends is/was in stealth mode. They intended to create a AAA game with a unique application of NFTs.

PiChain Global
##############

BrightNode provided tokenomics and white paper support for PiChain Global which intends to revolutionize e-commerce with Web3.

YCLUB
#####

BrightNode provided tokenomics and white paper support for the YCLUB project. They intended to bring Real World Assets (RWAs), such as megayachts, into the NFT realm.

StarkWare
*********

`StarkWare <StarkWareSite_>`_ scales L1 blockchains by providing the tech behind Zero Knowledge validity proofs. StarkEx brings transaction affordability to dYdX, Sorare, iMMUTABLE, DeversiFi, and more. StarkNet will provide a highly competitive L2 layer on Ethereum.

My tasks include:

- yellow paper -- edit
- Medium articles -- edit/proof
- website content -- edit/proof
- FAQ -- edit/proof
- User/Developer documentation edit
- UX content -- edit/proof
- Client integration documentation edit/proof
- Bank of Israel call for proposals edit/proof
- Internal legal documentation edit/proof


Talent
*******

`Talent <https://www.talent.io/p/en-gb/home>`_ is a recruitment agency with a difference. They have built a developer community that comes to them by hosting events that people want to attend and speakers that people want to hear. My task was to write up some of these talks to market these events.

Tom Altman
**********

Tom is a developer and solutions designer who improves his site's SEO by keeping up with the zeitgeist.

Ultron Foundation
*****************

I was commissioned to edit the lite paper and create the white paper for Ultron's DeFi ecosystem. `BrightNode <https://brightnode.io/>`_ had created the lite paper and liked the improvements I made so much, they engaged me as a white paper writer.


