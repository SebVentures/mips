# MIP40: Budget Framework

## Preamble
```
MIP#: 58
Title: RWA Foundation
Author(s): @SebVentures
Contributors: N/A
Type: General
Status: Draft
Date Proposed: 2021-07-21
Date Ratified: n/a
Dependencies: n/a
Replaces: n/a
```

## References

MIP58c3-SP-Template
MIP58c4-SP-Template
MIP58c5-SP-Template
MIP58c6-SP-Template
MIP58c7-SP-Template

## Sentence Summary

MIP58: RWA Foundation MIP define the RWA Foundation, its scope and formalize how MakerDAO can guide the RWA Foundation

## Paragraph Summary

MIP58: The RWA Foundation is a legal entity whose purpose is to manage Real-World Assets investments from MakerDAO. The Foundation is administered by one or more supervisors and one or more directors. This MIP defines how MakerDAO can communicate with the supervisors and the directors.

## Component Summary

**MIP58c1: The RWA Foundation**
Describe the legal structure of the RWA Foundation

**MIP58c2: The DAO Resolution**
Describe the DAO Resolution with which MakerDAO can instruct the RWA Foundation to take action.

**MIP58c3: Generic DAO Resolution**
Describes the process of issuing a generic DAO Resolution.

**MIP58c4: Adding a Supervisor Process**
Describes the process of adding a supervisor at the RWA Foundation.

**MIP58c5: Removing a Supervisor Process**
Describes the process of removing a supervisor at the RWA Foundation.

**MIP58c6: Addition of a Director Process**
Describes the process of adding a director at the RWA Foundation.

**MIP58c7: Removal of a Director Process**
Describes the process of removing a director at the RWA Foundation.


## Motivation

MakerDAO has a strategy to diversify its assets by investing in Real-World Assets (RWA). For this MIP, RWA are defined broadly as any kind of security, bonds, shares, tokens, loans, notes, mortgage, security interests (the list is not exhaustive).

This MIP aims at solving two issues limiting the ability of MakerDAO to implement its strategy:
- holding of traditional RWA need to enforce KYC/AML rules (Know Your Customer/Anti-Money Laundering) that MakerDAO can't satisfy in its current shape and with the current regulatory framework;
- enforcing RWA holding rights like suing in a court of law. MakerDAO can't defend its right in its current shape and with the current regulatory framework

## Specification / Proposal Details

### MIP58c1: The RWA Foundation

The RWA Foundation legal structure is based on the Cayman Islands Foundation Companies Law, 2017. The Foundation Company is a very flexible structure that allows being tweaked for specific needs. In regard to the RWA Foundation, this flexibility is used to balance the needs of rigidity in the Foundation management and the need of getting things done.

The RWA Foundation itself is not intended to hold any RWA but to have SPV (Special Purpose Vehicle) that are subsidiaries. There could be a SPV per collateral type. This allows to select the right jurisdiction for each SPV and define a set of rules (e.g. Articles of Association) for each. As an example, investments in the U.S. will generally be carried through a member-managed Delaware LLC. MakerDAO wil lend (or contribute) DAI to the RWA Foundation which with lend (or contribute) the proceeds to the SPV for investment.

In case this MIP conflicts with the Cayman Islands laws, the Articles of Association or the Memorandum of Association of the RWA Foundation, the latter should be used. The RWA Foundation MIP applies to any compatible Cayman Foundation regardless of the name of such Foundation.

The parties involved in a Cayman Foundation are the following:
- members and supervisors who are voting at the general meeting and whose main puspose is to appoint/remove directors;
- directors that are managing the Foundation and can also appoint/remove supervisors;
- the secretary which is a licensed service provider;
- the beneficiary, which, if set, is MakerDAO

While having a member at the creation, this membership is terminated and a special resolution is passed to irrevocably prohibit the appointment of a member in the future. The RWA Foundation has no members and is not expected to have one in the future. It is an orphaned entity.

The supervisors are voting at the general meeting. Their main job is to appoint and remove the directors. They can also change the Articles of Associations by issuing a Special Resolution. The supervisors can be appointed or removed by the directors with by MakerDAO (MIP58c4 and MIP58c5).

The directors are managing the Foundation. They are appointed or removed by the supervisors with an ordinary resolution of the general meeting (MIP58c6 and MIP58c7). By default, all management actions need to be initiated and ratified by MakerDAO (MIP58c3).

There is two kinds of directors: service providers and Maker Representatives. The formers are expected to be reputable and respectable servicing companies from the Cayman Island. The laters can be RWA-related Core Units (legal entities or individuals) or community members (legal entities or individuals). The intent of this MIP is to favor service provider directors but to complement them with one or more Maker representatives if needed. Therefore, it is intended by this MIP to always have at least one service provider director. The presence of Maker Representatives directors is optional.

The objects for which the RWA Foundation is established are: 
- to act as a borrower of a decentralized autonomous organization; 
- to carry out the mandates of a decentralized autonomous organization;
- to act as a holding company and an investment company, with no restriction on the objects or operations of its subsidiaries or on the nature of its or their investments;
- to make capital contributions or loans to subsidiaries of the company; 
- to provide financial assistance or benefits to beneficiaries as designated or determined under the articles of association; and
- to do all such things as in the opinion of the directors are or may be incidental or conducive to the above objects or any of them.


### MIP58c2: DAO Resolution

The RWA Foundation recognizes the concept of DAO Resolutions by which MakerDAO can instruct the RWA Foundation to take action and ratify such decision when taken. The following components of this MIP formalize those DAO Resolutions. DAO Resolutions don't have to follow this MIP process, but DAO Resolutions not following this MIP should be avoided and are discouraged.

It is understood that the recipients of the DAO Resolution (supervisor or directors of the RWA Foundation) might alter the instructions in order to comply with law, regulations, and formal processes. They are not allowed to alter the representation of the intent.

MakerDAO can take the following type of instructions:
- Ordinary Resolution to be issued and approved at the next General Meeting of the RWA Foundation 
- Special Resolution to be issued and approved at the next General Meeting of the RWA Foundation
- Instruction to directors

### MIP58c3: Generic DAO Resolution

This subproposal is used to issue a DAO Resolution. Such subproposal has a validity of 30 days from the execution date.

MIP58c3 subproposals have the following parameters:

* Feedback Period: 2 weeks
* Frozen Period: 2 weeks

MIP58c3 subproposals must use the template located at [this link](MIP58c3-Subproposal-Template.md). This template is considered ratified once this MIP moves to Accepted status.

### MIP58c4: Adding a Supervisor Process

This subproposal is used to instruct the RWA Foundation directors to appoint a supervisor (and ratify such appointment). Such subproposal has a validity of 1 year (365 days) from the execution date.

MIP58c4 subproposals have the following parameters:

* Feedback Period: 2 weeks
* Frozen Period: 2 weeks

MIP58c4 subproposals must use the template located at [this link](MIP58c4-Subproposal-Template.md). This template is considered ratified once this MIP moves to Accepted status.

### MIP58c5: Removing a Supervisor Process

This subproposal is used to instruct the RWA Foundation directors to remove a supervisor (and ratify such removal). Such subproposal has a validity of 1 year (365 days) from the execution date.

MIP58c2 subproposals have the following parameters:

* Feedback Period: 2 weeks
* Frozen Period: 2 weeks

MIP58c5 subproposals must use the template located at [this link](MIP58c5-Subproposal-Template.md). This template is considered ratified once this MIP moves to Accepted status.


### MIP58c6: Adding a Director Process

This subproposal is used to instruct the RWA Foundation supervisors to appoint a director (and ratify such appointment). Such subproposal has a validity of 1 year (365 days) from the execution date.

MIP58c6 subproposals have the following parameters:

* Feedback Period: 2 weeks
* Frozen Period: 2 weeks

MIP58c6 subproposals must use the template located at [this link](MIP58c6-Subproposal-Template.md). This template is considered ratified once this MIP moves to Accepted status.

### MIP58c7: Removing a Director Process

This subproposal is used to instruct the RWA Foundation supervisors to remove a director (and ratify such removal). Such subproposal has a validity of 1 year (365 days) from the execution date.

MIP58c7 subproposals have the following parameters:

* Feedback Period: 2 weeks
* Frozen Period: 2 weeks

MIP58c7 subproposals must use the template located at [this link](MIP58c7-Subproposal-Template.md). This template is considered ratified once this MIP moves to Accepted status.

