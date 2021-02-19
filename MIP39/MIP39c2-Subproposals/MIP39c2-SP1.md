# MIP39c2-SP1: Adding Core Unit (Real-World Finance)

## Preamble

```

MIP39c2-SP#: 1
Author(s): Sébastien Derivaux (@SebVentures)
Contributors: N/A
Status: RFC
Date Applied: 2021-01-26
Date Ratified: <yyyy-mm-dd>

```

## Specification

### Motivation

* This Core Unit is designed to pursue Real-World Asset work and more generally helps MakerDAO to take over the traditional finance world.

### Core Unit Name

**Name:** Real-World Finance
**ID:** RWF-001

### Core Unit Mandate

* **Context**: With TVL on DeFi is growing quickly, it’s still only $30B. The traditional financial system is over the quadrillion. Both systems will merge meaning we have to find ways to onboard all those assets (bonds, real estate, derivatives, …) and tools (yield curve, risk frameworks) in DeFi. Moreover, Maker is resurrecting the [Free Bank ](https://en.wikipedia.org/wiki/Free_banking) concept. With an expected competition in this field, MakerDAO should continue to innovate and should stay at the forefront of onboarding the real-world financial system into DeFi. Failure to do so might lead Maker to lose its leading position. 

* **The mandate of this Core Unit is to bring real-world finance concepts to MakerDAO**; Those concepts encompass but are not limited to:

  * Investing in Real-World Assets (loans, bonds, structured finance, …)
  * Yield curve implications in DeFi
  * Accounting, solvency, and potential regulatory reporting

* The mandate of the Core Unit is also to nurture competencies related to those challenges and find solutions for each problem in order for MakerDAO to be the leader in this space. The Core Unit is a toolbox at the service of Maker Governance.

* Use real-world finance to produce more yield while keeping our risk appetite low thanks to wider diversification and risk management tools.
* Be the interface that connects real-world finance with the MakerDAO
* To achieve this mandate the team will be composed of people from diversified backgrounds but with an emphasis on people having experience in traditional finance concepts.
* The Maker Governance can interact and prioritize work with the Core Unit by issuing a Signal Request, an informal poll, or any other means. In case of conflicting messages, the Signal Request will take precedence over any other means.

* **First targets**:
  * **Increase RWA loans to 300M DAI**. Currently, the amount of loans originated from RWA is zero. Considering collateral types that are quite advanced in the onboarding process (6S, New Silver and ConsolFreight), we might soon achieve $22M in loans (in Q1 2021). Once those first targets are hit, the processes ironed, and the Community finds itself more comfortable with these assets, those vaults can increase significantly (6S is targeting 100M after 12 months of operations, New Silver has room to grow as well). Moreover, we are already exploring new partnerships with various asset originators (PaperChain, BlockSquare, Uprets, Peoples Company, …). Therefore, $300M of loans seems like an ambitious but achievable target with the current deal flow momentum. At a 3% average SF, that would correspond to $9M revenues on an annual basis. The number of vault types should be between 5 and 10.
  * **Set up the monitoring infrastructure**: RWA collaterals are a portfolio of assets managed by a third party: the asset originator. Being outside of any regulation, for the most part, we need to ensure that our assets (DAIs lent to asset originators) are used soundly. We are currently working with asset originators to have access to their loan tape and building the infrastructure to monitor everything. We also expect to use third-party services to have independent updated valuation (real estate prices, credit ratings, …).
  * **Find the best investment conduit for RWA**: Currently, we are exploring the Centrifuge model and the Trust model. We also need to explore how we could set up [a legal subsidiary ](https://forum.makerdao.com/t/discussion-legal-structures-of-makerdao/4390). Finding the best way to invest in RWA is of prime importance to scale safely.
  * **Define a good solvency model for RWA**: Currently, MakerDAO uses risk models at the collateral level and doesn’t define solvency at the MakerDAO level. The uncorrelated nature of RWA makes it a strategic advantage to be able to define solvency at the MakerDAO level. Indeed, if we want to compete with real banks, we need to have the same tools (and exploit some of their limitations). This is also including [balance sheet manipulations ](https://forum.makerdao.com/t/makerdao-accounting-and-implications/5346). Having a good solvency model will be a wonderful tool to [earn more revenues while keeping the risk in line. ](https://forum.makerdao.com/t/makerdao-accounting-and-implications/5346/4)
  * **Diversify, diversify, diversify**: Corollary to the solvency model, RWA aims to enjoy a strong diversification. RWAs are naturally somewhat uncorrelated to crypto-assets but, within RWA, we should also aim for diversification. The best target might be new kinds of assets, unserved by banks, with good growth prospects (Paperchain, for instance, that use big data and machine learning to safely advance money on a future invoice). Nevertheless, established asset types are more likely to provide higher debt ceilings in the medium term. While it is likely that we will mainly work with small businesses/startups, we also need to work with more established players even if that means lower revenues.
