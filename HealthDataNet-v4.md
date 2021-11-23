HealthDataNet-v4
================
ASG
11/22/2021

Work in progress, material towards end is from a previous unsubmitted
proposal

**HealthDataNet**

Part 1 - Proposal Submission Name of Project: **HealthDataNet**

Proposal in one sentence:

Allow a private dataset to be stored on Filecoin Plus, enclose it in an
additional privacy ‘bubble’, publish it on the Ocean marketplace, and
provide the output of a compute-to-data algorithm run on the dataset to
an Ocean marketplace customer.

Description of the project and what problem is it solving: Under US law
(HIPAA, Hitech Act), healthcare companies involved in direct patient
care are required to maintain data collected by them for every patient.

Problem to be solved: Storing certain kinds of medical data indefinitely
/ for long periods of time is expensive, especially if it generates no
returns for money spent on storage. Furthermore, this data is locked
within individual company data silos. These isolated data silos lack
statistical power, and the companies have no mechanism to cooperate on
combining and analyzing this data for different insights.

For example, this situation is true for several companies that are part
of the intra-operative surgical monitoring industry in which the primary
researcher (ASG) has worked for several years. Each individual company
has a dataset that is inadequate for machine learning algorithms to
provide insights, yet are unable to share data between themselves since
this might provide crucial business intelligence to their competitors.

Solution: We propose a data storage, analytics and monetization
**paradigm** for aggregated private healthcare data that focuses on
patient privacy, data provenance and traceable, controlled
compute-to-data. This paradigm will include an inexpensive,
decentralized storage solution (e.g. Filecoin), absolute control of data
in the hands of the data provider with fine-grained layers of privacy
provided by Ocean Protocol and Datona Labs, ability to publish dataset
with compute-to-data permissions on the Ocean Marketplace, running
compute-to-data on the dataset and providing the output to another Ocean
Marketplace customer authorized by the data provider.

Our long-term goal is to become a nationally accredited (Joint
Commission), specialized service providing healthcare companies with
storage, analytics and monetization of their data on the Ocean
Marketplace, while ensuring patient rights and privacy. Funds requested
in this proposal will allow us to develop a *proof-of-concept* of such a
service paradigm.

Grant Deliverables: (Provide us with a check-boxed list of deliverables
for the funding provided)

\[ \] upload example dataset to Filecoin Plus

\[ \] enclose dataset in an additional privacy bubble smart contract
controlled by data provider. The privacy bubble smart contract will be
provided by Datona Labs Ltd (UK).

\[ \] publish the dataset with discoverable metadata on the Ocean
Marketplace

\[ \] publish a relevant compute-to-data algorithm to the Ocean
marketplace

\[ \] enable the data provider to approve a third party customer through
the privacy bubble provided by Datona Labs Ltd. 

\[ \] run compute-to-data on the dataset and provide output to the
approved Ocean marketplace customer

Which category best describes your project? Pick one. Other / core tech
/ community

Which Fundamental Metric best describes your project? Pick one.

Other - Our end goal is to unlock value in US healthcare data silos with
Ocean Protocol based technology. As a first step, we wish to create a
proof-of-concept of a paradigm to store, analyze and monetize these
datasets for their aggregators and **ultimately provide control to each
patient over their own data** going forward.

Core tech: We will demonstrate how the Ocean Marketplace can be
integrated with decentralized data providers like Filecoin.

Community: By establishing this paradigm for private, regulated,
healthcare data storage and monetization via the Ocean Marketplace, we
will enable the Ocean community to develop similar solutions in other
areas of healthcare as well as other regulated and privacy sensitive
industries (e.g. legal).

What is the final product?: A proof-of-concept of a storage and
monetization paradigm using compute-to-data on privately stored
aggregate healthcare datasets.

How does this project drive value to the “fundamental metric” (listed
above) and the overall Ocean ecosystem? This is best expressed as
Expected ROI

Expected ROI: Anecdotal reports from a health data company CEO (the
Health Unchained podcast, episode 7, Jul 2, 2018) suggest a single
health PHR (personal health record) was being sold for \~ 1200 USD in
data marketplaces. The legality of these transactions are unclear, but
indicates the value of such data. The largest neurophysiology companies
can provide services in \~ 100,000 cases a year, and the combined case
coverage for major companies based in the US Northeast is at least
200,000 cases. If a CMO / CIO decides to use Ocean technology, they will
bring their entire database of several thousand patients to Ocean.
Although the total case volume is large, the types of cases (e.g. neck,
thorax, low back, brain aneurysms, tumors etc) being covered are many
and the patient population is varied. Hence an individual company lacks
the ability to collect sufficient data for machine learning.

Funding Requested: TBD

Proposal Wallet Address: (must have minimum 500 OCEAN in wallet to be
eligible. This wallet is where you will receive the grant amount if
selected). 0x4fDCCF789B8631110A942AD1A8663cE054846e21

Have you previously received an OceanDAO Grant: No

-Discord Handle (if applicable): @mnkyntigr -Project lead Contact Email:
<nomesg2020+OceanDAO@gmail.com> -Country of Residence: United States

Part 2 - Team

Core Team

Ambarish S. Ghatpande, PhD, CNIM Role: researcher Relevant Credentials:
LinkedIn: <https://linkedin.com/in/ambarishghatpande> Github:
<https://github.com/aghatpande>

Experience and Background: Statistical analysis and machine learning
using R/RStudio 2013 - present Surgical neurophysiologist III with
SpecialtyCare 2016 - 2021 Surgical Neurophysiologist Sentient Medical
Systems 2015 - 2016 Research Associate University of Maryland 2011 -
2012 Senior Research Scientist Lupin Ltd 2011 Research Associate at
Monell Chemical Senses Center 2005-2011 Postdoctoral fellow at the
University of Colorado 2000 - 2005 PhD dissertation in ion channel
biophysics 1993 - 2000

Datona Labs Ltd / Principal: David N. Potter Role: consultant Relevant
Credentials: Senior software Engineer LinkedIn:
<https://www.linkedin.com/in/david-potter-2443332/>

Background/Experience:

Advisers TBD

Part 3 - Proposal Details

Allied health care providers range from anesthesiology service provider
companies all the way to environmental services provider companies in
the United States. A vast army of these companies provide services to
U.S. hospitals. Many different types of companies are involved in direct
patient care and are required to store PHI (protected health
information) data by law.

Surgical neurophysiology companies are an example of allied health
provider companies. Large neurophysiology companies are unique in having
nationwide coverage. Surgical neurophysiology companies provide their
services for surgeries involving the brain, spinal cord, peripheral
nerves and many types of vascular (involving heart, major blood vessels
including those in the brain) surgeries. There are approximately 200,000
such surgeries performed annually in the United States \[ref TBD\].

During surgery, the surgical neurophysiologist present in the operating
room records neurophysiological data from the patient and runs tests at
the request of the surgeon. This allows the surgeon to operate avoiding
injury to neural tissue. For example, during brain tumor surgeries, a
surgeon needs the neurophysiologist to guide him by identifying brain
areas involved in movement, sensation, vital bodily functions (breathing
etc). Large amounts of neurophysiological data are collected and needs
to be stored as PHI by the company that employs the neurophysiologist.

The outcome of these types of surgeries are dependent on several
features of the patient’s medical history as well as the intra-operative
course of the surgery. Potentially, this data when subject to machine
learning, will unlock new insights into surgical outcomes.
Unfortunately, machine learning models are data hungry, and no
individual company can generate sufficient data on the many different
types of surgeries performed. They need to collaborate amongst each
other but are wary of this due to competition. We hope to provide a
collaborative mechanism while simultaneously providing a new revenue
stream for each company in the marketplace. In addition, machine
learning developers and other entities (e.g. insurance companies) will
also benefit from compute-to-data access to real patient data.

Using their experience and connections in the surgical neurophysiology
field, the core team intends to network with large and small surgical
neurophysiology company executives. The US Northeast, where the core
team is based, is at the forefront of this field and sets the ‘standard
of service’ for other regions of the country.

Using these inputs and after consultation / collaboration with the Ocean
Protocol developer community, the team will outline legal and realistic
solution/s to these problems and propose possible analytic solutions in
subsequent one-on-one meetings with these executives. These solutions
will be based on the strengths of the Ocean Protocol and Datona Labs
tech stack, including immutability, access tracking and compute-to-data
capabilities that preserve patient privacy.

Project Deliverables - Roadmap

Any prior work completed thus far? The principal researcher has
published two test datasets (vital_signs_1 & 2) on the Ocean Marketplace
using the Rinkeby network. He is currently working on learning to
develop and publish an appropriate compute-to-data ML algorithm. To
achieve this, he is contributing to the Algovera AI hacking sessions
actively.

What is the project roadmap? That is: what are key milestones, and the
target date for each milestone.

Final report with analysis of the findings : February 2022

Please include the team’s future plans and intentions.

We believe a successful implementation of data solutions in the
neurophysiology field will kindle interest amongst other types of health
provider companies (e.g. anesthesia providers that typically work
closely with surgical neurophysiologists in the operating room) and
stimulate their adoption of Ocean technology.

Our end goal is to become an Ocean Protocol based b2b service provider
for healthcare data assets and analytic solutions while ensuring patient
rights and privacy.
