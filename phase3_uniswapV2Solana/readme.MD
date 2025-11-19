## Phase 3: Uniswap v2 on Solana (10 days)

### Implementing Uniswap v2 on Solana

1. **Project Plan** (2 days)

   - Define project scope and deliverables
   - Create a timeline with milestones
   - Deploy v2-core and v2-periphery on EVM testnet(e.g., sepolia testnet)
   - Hands on Uniswap v2-peripheral contract
   - Identify key components: AMM core, pair contracts, router, factory
   - Risk assessment and mitigation strategies

2. **Technical Design** (First week)

   - Analysis of Uniswap v2-core and v2-periphery
   - Design Solana program architecture for AMM functionality
   - Define account structures and PDA derivation paths
   - Determine token swap mechanics in Solana's model
   - Design liquidity pool token implementation
   - Map out price oracle functionality

3. **Smart Contract Development** (2 weeks in middle)

   - Implement factory program for creating token pairs
   - Develop core swap functionality
   - Implement liquidity provision/removal logic
   - Develop price oracle functionality
   - Build router program for optimal trading paths

4. **Comprehensive Testing** (2 weeks in middle)

   - Develop unit tests for all program functions with AI assistance (Cursor/ChatGPT) (100% coverage)
   - Create integration tests for cross-program interactions
   - Implement invariant testing for constant product formula
   - Create test suite for edge cases and attack vectors
   - Performance testing under various network conditions
   - Direct testing against devnet (no mocks)

5. **Deployment and Infrastructure** (Last week)

   - Create deployment scripts for Solana devnet
   - Set up monitoring infrastructure
   - Implement analytics collection pipeline
   - Document deployment procedures
   - Create environment configuration for various networks

6. **User Interface** (Last week)

   - Develop a simple web interface a script for interacting with the protocol

7. **Analytics Dashboard** (Last week)

   - Set up analytics infrastructure by using Dune
   - Create dashboards for:
     - Trading volume and liquidity
     - Fee generation and distribution
     - Price impacts and slippage
     - User adoption metrics
     - Protocol performance indicators

8. **Fork Mainnet Validation** (Plus)

   - Set up Solana mainnet fork
   - Validate protocol against real-world conditions
   - Simulate high-volume trading scenarios
   - Measure performance against existing Solana AMMs

## Acceptance Criteria

Upon completion of Phase 3, participants must organize a meeting to demonstrate their achievements through the following:

1. **Technical Understanding**

   - Ability to explain the differences between EVM and Solana program models
   - Understanding of AMM mechanics across different blockchains

2. **Code Quality**

   - Clean, readable, and well-documented code
   - Proper error handling and security considerations
   - Optimization for Solana's parallel execution model

3. **Functional Implementation**

   - Protocol should match Uniswap v2 core functionality
   - Performance should be optimized for Solana's runtime

4. **Documentation and Usability**
   - Comprehensive technical documentation
   - Clear user guides and examples
   - Intuitive interface for protocol interaction

## Useful Document List
1. [Uniswap v2-periphery](https://github.com/Uniswap/v2-periphery)  
2. [Uniswap v2-core](https://github.com/Uniswap/v2-core)  
3. [Uniswap doc](https://docs.uniswap.org/contracts/v2/overview)
4. [Solana](https://solana.com/zh/docs/intro/installation)  
5. [Anchor](https://www.anchor-lang.com/docs)  
6. [LiteSvm](https://github.com/LiteSVM/litesvm)  
7. [Surfpool](https://docs.surfpool.run/)  
8. [Hardhat](https://hardhat.org/)
