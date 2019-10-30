[Table of Contents](../African-Token-Lab_whitepaper.md#table-of-contents) | [Next Page: Proof-of-Concept ->](Proof-of-Concept.md)


# The Africa Token Lab
**<short definition>**
Michael 
Norbert @tokenlab
Frank
Désiré desire@tokenlab<br/>
_NOTE: If you can read this on GitHub, then we're still actively developing this
document. Please check regularly for updates!_
<div STYLE="page-break-after: always;"></div>
## Table of Contents ###########################################################
<!--* [Disclaimer](#disclaimer)
* [IRIS Overview](#iris-overview)
* [Cosmos and Tendermint](#cosmos-and-tendermint)
* [IRIS Innovations](#iris-innovations)
* [IRIS Network Design](#iris-network-design)
* [Network Actors](#network-actors)
* [IRIS Services](#iris-services)
* [IBC Enhancement](#ibc-enhancement)
* [Use Cases](#use-cases)
* [Token Economics](#token-economics)
* [Initial Token Distribution](#initial-token-distribution)
* [Roadmap](#roadmap)
* [The Team](#the-team)
* [Core Members](#core-members)
* [Advisors](#advisors)
* [References](#references)-->
<div STYLE="page-break-after: always;"></div>

## Disclaimer
This whitepaper and any other documents published in association with this whitepaper relate to
the intended development and use of the Africa Token Lab. They are information purposes only
and may be subject to change.

### This whitepaper describes a developing project
This whitepaper contains forward-looking statements that are based on the beliefs of Africa Token Lab Limited,
as well as certain assumptions made by and information available to Africa Token Lab Limited.
The Africa Token Lab as envisaged in this whitepaper is under development and is being constantly
updated, including but not limited to elements of governance and technical features offering.
If and when the African Token Lab is set up, it may differ significantly from the lab set out in
this whitepaper. No representation or warranty is given as to the achievement or
reasonableness of any plans, future projections or prospects and nothing in this document is or
should be relied upon as a promise or representation as to the future.

### No offer of regulated products
This document does not constitute an offer or solicitation of securities or any other regulated
product.
The Africa token Lab does not represent equity, shares, units, royalties or rights to capital, profit, returns or income in the platform or software or any other company or intellectual property associated with the platform or any other public or private enterprise, corporation, foundation or other entity in any jurisdiction.

### This whitepaper is not advice
This whitepaper does not constitute advice to purchase any named African Token Lab tokens, at this current stage of project development. It must not be relied upon in connection with any contract or purchasing decision.
If any changes moving forward, we'll keep you informed via this working repository.


### Risk warning

# Introduction

The objective of this whitepaper is to outline the drivers, benefits, risks, considerations, and governance taken into account when determining when and where to adopt [Traceability tools, methods and/or standards](2_Open_Standards.md) and [use](3_Open_Source_Software_Use.md) as well as [contribute](4_Open_Source_Software_Contribution.md) to Open Source Software (OSS). This whitepaper captures the Government of Canada's (GC) approach to move towards a more open environment which includes changes in how we work, purchase solutions, and provide information and services to Canadians.

## Scope

This whitepaper has for scope the following elements: Blockchain basics introduction; Beyond the technology, the Pain; The Pill; Traceability, Why - How - What; Open Standards; Open Markets; Open Culture; and some common Legal Considerations. Each concept will have the following structure: the benefits; the risks and drawbacks; and best practices.

We will complement the scope with: the Project history and background; Project status; Proof-of-Origin; SourceCoin; Incentivisation and Coin Distribution; End Users; Current investors/shareholders -- (a) the Team, (b) Crowd Sale Participants; Developers; Crowd Sale; The African Token Lab Foundation; The Annex.

The following concepts are not part of the whitepaper as they have their own dedicated documentation: (...). Their importance is nonetheless recognized as critical to an open and transparent venture.

## What do we want to achieve
<ul>
<li>Our Mission is to shift our current way of doing things to an incentives-based model
</li>
<li>Objective: Tokenize the economy
</li>
<li>Values: Efficiency, Optimization, Ethics, Integrity, Versatility, Decentralization
</li>
</ul>

## Who our customer is
<ul>Potential industry sectors to offer our services to:
<li>Digital payment / Fintech
</li>
<ol>Payment tokenisation
</ol>
<li>Supply chain, logistique
</li>
<li>Blockchain for administrative processes
efficiency</li>
<li>Agriculture / Agri Tech
</li>
<Blockchain for IoT security
</li>
<li>Food and beverage industry
</li>
<ol>Traceability; Proof-of-Origin
</ol>
<li>Environment; Renewability
</li>
<ol>CO2 footprint tokenisation
</ol>
<li>Energy / energy tech (smart grid)</li>
<ol>From consumer to prosumer
</ol>
</ul>

<ul>Our initial customers segment target are organizations.
<li>We work with public private organisations to finding innovative,
</li>
<li>user-centered approach to solve their problems in a time and cost
</li>
<li>efficient fashion, offering along the way transparence, immutability and
</li>
</li>trust to end-users by leveraging on distributed ledger technology, with
</li>
</li>a particular focus on the practical application to the 'real economy' of
</li>
<li>the concepts such as smart contracts, private keys or Token.
</li>
</ul>

## Communication

### Channels we use
Twitter, WhatsApp / Slack, YouTube, Medium, Vimeo, Signal, (Telegram?)

### We publish every
3x a week minimum

### Content do we create for each channel
<ul>
<ol>Twitter: (informative) tweets + images + videos / gif
</ol>
<ol>YouTube: demo videos + tutorials / 'webinar' / workshop + social sharing (from the community)
</ol>
<ol>WhatsApp: social messaging, automatic messaging, ads
</ol>
<ol>Vimeo: tutorial, webinar / workshop
</ol>
<ol>Slack: professional communication & document sharing over various channels
</ol>
<ol>Signal (or Telegram) : work communication
</ol>
<ol>Medium: blogging, tutorials
</ol>
</ul>

### Roles & Responsibilities
<ul>Who does what



<!--

## Strategic Environment

### Organizational Overview

Openness and transparency are fundamental to ensuring Canadians' trust in their government and in democracy overall. Citizens expect their government to be open, transparent, and accountable. They also expect their government to deliver real, meaningful results, in a fair, efficient, and responsible manner. The GC's commitment to openness is intended to foster greater transparency and accountability, and to help create a more cost-effective, efficient, and responsive government for all Canadians. ([Third Biennial Plan to the Open Government Partnership](https://open.canada.ca/en/content/third-biennial-plan-open-government-partnership))

The GC is committed to raising the bar on openness and transparency. The ministerial mandate letters sent to each of the Cabinet Ministers reinforces expectations that all federal departments and agencies will do their part to ensure an open, honest government that is accountable to Canadians, lives up to the highest ethical standards, and advances Canadians' priorities with a renewed sense of collaboration.

We are delivering on that with the [Open Government Portal](https://open.canada.ca/en) that enables searching GC open datasets and open information digital records. Canada has also been an active Open Government Partnership (OGP) member since 2012; In September, 2017, Canada came first in the election of the new OGP Steering Committee members, and assumed its seat on the Steering Committee. Canada will also be hosting the OGP Global Summit in Ottawa in May 2019.

In October 2017, Treasury Board of Canada Secretariat (TBS) reached a [Memorandum of Understanding (MOU) concerning Digital Government with the United Kingdom](https://www.canada.ca/en/treasury-board-secretariat/services/innovation/memorandum-understanding-concerning-digital-government.html) that includes open data and open government, but also add other principles of digital development such as open standards, OSS and open markets.

Soon after, the [GC Strategic Plan for IM and IT 2017-2021](https://www.canada.ca/en/treasury-board-secretariat/services/information-technology/strategic-plan-2017-2021.html) included a new planned action to introduce a strategy for use of OSS and open standards. TBS will lead the development of a strategy to set direction for the government on the use and release of OSS and open standards that will be ratified by GC EARB.

In December 2017 the [GC EARB members endorsed](http://www.gcpedia.gc.ca/gcwiki/images/9/98/GC_EARB_2017-12-14_Record_of_Discussion.pdf) that GC EARB supports the formalization of a common GC-wide approach to the adoption of open source within government, resulting in a more robust open community within the GC.

In February 2018, [Canada signs the Digital 7 (D7) charter](https://www.canada.ca/en/treasury-board-secretariat/news/2018/02/canada_joins_leadingdigitalnationsind7.html) and joins Estonia, Israel, South Korea, New Zealand, the UK and Uruguay committing to working towards core principles of digital development, with a focus on user needs, open government, and a commitment to share and learn from D7 member nations. The D7 charter, which also calls for commitments to open standards, OSS, open government and teaching children to code.

In May 2018, TBS reached a [MOU on cooperation in the field of digital government and economy with Estonia](https://www.canada.ca/en/treasury-board-secretariat/services/innovation/memorandum-understanding-can-estonia-digital-government-economy.html), a fellow member of the D7 and the OGP.

### Business Need

The GC's departments and agencies need to find effective ways to offer the best digital services possible to citizens and users. This implies working in the open by default, by releasing all non-sensitive data, information and source code under an open licence that enables sharing and reuse. There's a need for improved interoperability between systems; more independence from data formats, software, technologies and vendors; substitutability of solutions and service providers and; avoiding lock-in to enable greater flexibility in the management of IT solutions. The GC also needs to attract digital talent and increase job satisfaction by embracing leading practices and the latest technologies. Finally, the GC must provide public benefits to the public-at-large as well as support the Canadian economy and communities.

### Drivers for Change

#### Policy

In recent years, the GC has taken multiple steps towards being a more open organization, including commitments to open Government, use open standards and OSS as well as release source code under an open licence. These commitments are in Memorandums of Understanding around digital services, with D7 partners, the United Kingdom and Estonia. The ministerial mandate letters sent to each of the Cabinet Ministers reinforces expectations that all federal departments and agencies will work in the Open by default. These policy changes challenge the status quo and force the various organizations of the GC to adapt their technologies.

#### Technology and Efficiency

Leveraging technologies that are built on open standards mitigate against the risk of lock-in and offers the interoperability, independence and substitutability required to design enterprise level applications and services. OSS by default encourages the use of open standards and their inherent flexibility enables rapid response to changing missions and markets as well as swift provisioning of both known and unanticipated users.

Using OSS means you can benefit from solving common problems with readily available technology and you have more time and resource for customized solutions to solve the rare or unique problems. OSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and encourages the identification and elimination of defects not recognized by the original development team. For the public sector, like all organizations, cost is important, but other public benefits can also motivate public sector use of OSS.

From a support and maintenance perspective, OSS - as opposed to more burdensome usages of proprietary software and their users licences - provides a real cost advantage where multiple copies of software are required, or when the user base grows. Since there is no need to manage individual user licence, the focus is more on maintaining the application itself. Using OSS and service providers also helps avoid lock-in as it is possible to seek other service providers to support the maintenance and development of the solution.

#### Economy

Adopting and using open standards means it is possible to move between different technologies when needed, thus avoiding lock-in and opening up the range of companies that the organization can purchase from. Doing so would encourage more of them to use the same standards and encourage a wider range of both open source and closed-source software.

OSS provides an advantage in that it creates an open marketplace for providers of all types of support. Any support business with sufficient software development competencies can add new features and fix bugs in the software; OSS users can also switch to a different support provider whenever an existing company no longer meets their needs or timelines. Using OSS may better support local businesses in Canada as it would encourage [Open Markets](5_Open_Markets.md).

#### Community, Demography and Society

Citizens expect accessibility, official languages and continuous improvements of digital services provided by the GC. The flexibility of using OSS compel GC to meet user needs by modifying existing or creating new OSS.

Canada has set a very clear Open Government mandate to "create greater transparency and accountability, increase citizen engagement, and drive innovation and economic opportunities through open data, open information, and open dialogue". Sharing in-house software programs under an OSS licence naturally align with the role of public administrations in providing wide benefits to the public-at-large, such as in maintaining society's technological infrastructure and helping it evolve. OSS can also help maximize overall economic efficiency within society. Where software is freely available, and where anyone can add any new features needed, companies can make use of these existing resources rather than expend effort duplicating an existing project.

Releasing an in-house software code under an OSS licence can encourage external contributions and collaboration from governments, companies, students and citizens in the form of source code, bugs and documentation. The project can be a joint effort amongst multiple companies, public sector workers, and individual volunteers. Releasing software as OSS to encourage others to collaborate on it can also help ensure the viability of a project into the future. The release of OSS by public sector organizations can also help stimulate innovation in the private sector. It enables companies to create specialized offerings built on OSS, even where such software might otherwise be too expensive for the company to develop in-house.

### Business Outcomes

The expected results of the GC working in the open, using open standards and open source software are as follows:

* Canadians are able to find, use and contribute to GC software projects and source code as well as open source software used by the GC to support meaningful engagement with their government and communities.
* Enable greater flexibility in the management of information and communication technologies (ICT).
* Support and increase collaboration with other public administrations in Canada and around the world.
* Improve the overall availability of re-usable technology within government and society.

## Strategic Fit

The GC Digital Playbook includes principles on the [use of open standards](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/standards-normes/en/4-use-open-standards-solutions.html) to ensure your system works and communicates with other products or systems, and can easily be upgraded and expanded; the [use of OSS](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/standards-normes/en/4-use-open-standards-solutions.html) since, by their nature, they are publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable; and [working in the open](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/standards-normes/en/3-work-in-open-by-default.html) by making source code open and reusable under an appropriate OSS licence, so that other developers can benefit from your work and build on it.

There are great opportunities to learn and engage with our D7 partners, for example by aligning and collaborating with the [UK Open Standards Board](https://www.gov.uk/government/groups/open-standards-board) on selecting open standards for government.

## Detailed Description of the Business Need

### Problem/Opportunity Statement

Open standards and OSS are only slowly gaining traction in the GC, particularly when compared to the private sector and other public administrations (US, UK, France, Italy, Estonia, New Zealand, etc.). Relatively low levels of adoption have been attributed to a lack of understanding of the potential benefits, accompanied by a risk-averse technical and procurement culture, compounded by significant levels of misconceptions.

Open Standards are essential to ensure interoperability between systems and enables easier migration and transitions to different systems. More so, the use of OSS supports interoperability and information sharing and should be considered in the assessment of IM-IT solutions. Both help mitigate the risks of lock-in, enable the GC to support for the Canadian economy and open communities, provide lower total cost of ownership, attract top digital talent and lead to better job satisfaction.

If TBS wants the GC to become an open organization and shift to a more open culture especially around digital and technology, it should strongly endorse the adoption of open Standards for data, information and communications; the use of OSS in our technology stack; contributing to upstream development of OSS; releasing code developed internally under OSS licenses and collaborating more widely with other public administrations in Canada and around the world.

-->


### Projects

#### Traceability
Considering the inability to accurately and fully -- all along the value chain -- track goods or transactions from end-to-end cause citizens to demand for more transparency, traceability and fair processes applied to products they consume. We are here calling for  the community’s creativity to come up with innovative ways to check the proof of origin for procured products. In particular, solutions should prove, among other things, that food supply is safe, smallholder farmers have been fairly retributed, farm or agricultural products are meeting compliance standards, EH&S (Environment, Health and Safety) and quality requirements.
