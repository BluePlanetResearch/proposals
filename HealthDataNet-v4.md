Healthcare\_data\_guild
================
ASG
11/22/2021

### Name of Project

**Healthcare\_data\_guild** (Secure, private guild / bubble for
aggregate healthcare data stakeholders)

### Proposal in one sentence

Allow a private dataset, resembling **aggregated** healthcare data, to
be stored on Filecoin Plus, enclose it in a **privacy ‘bubble’**,
publish metadata on the Ocean marketplace, and provide the output of a
relevant compute-to-data algorithm run on this dataset to an
**authorized Ocean marketplace customer**.

### Description of the project and what problem is it solving

#### Problem to be solved

Under US law (HIPAA, Hitech Act), healthcare companies involved in
direct patient care are required to maintain data for every patient of
theirs. Storing certain kinds of medical data indefinitely / for long
periods of time is expensive, especially if it generates no returns for
money spent on storage. Furthermore, this data is locked within
individual company data silos. This is true for several companies that
are part of the intra-operative neuromonitoring (IONM) industry in which
the project lead (ASG) has worked for several years. Each individual
company has a dataset that by itself is inadequate for machine learning
algorithms, but several such private datasets together can provide
valuable insights. Yet these companies are unable to share data between
themselves since this might provide crucial business intelligence to
their competitors.

#### Solution

We propose an access-controlled guild or bubble, based on self-sovereign
IDs, of various stakeholders of aggregated healthcare data. Within the
bubble, fine grained permissions will allow private data storage,
analytics and monetization of individual company owned private datasets.
The datasets will remain private, yet be subject to ML algorithms
provided by authorized ML algorithm vendors and algorithm outputs will
be consumed by authorized consumers all of whom are part of the bubble.
This will allow a central focus on patient privacy, data provenance and
traceable, controlled compute-to-data within the Ocean marketplace. A
similar federated learning solution called
[Melloddy](https://www.melloddy.eu/), but based on centralized data
storage at AWS, is currently being piloted for large pharmaceutical
companies.

### Grant Deliverables

\[ \] upload example dataset (e.g. containing upto 14 features) to
Filecoin Plus

\[ \] enclose dataset in an additional privacy bubble smart contract
controlled by data provider. The privacy bubble smart contract will be
provided by Datona Labs Ltd (UK).

\[ \] publish the dataset’s discoverable metadata on the Ocean
Marketplace

\[ \] publish a relevant compute-to-data algorithm (e.g. a supervised
learning algorithm to predict insurance status of patient) to the Ocean
marketplace

\[ \] enable approval, by healthcare\_dataguild or the dataset provider,
of a third party customer / algorithm provider through the privacy
bubble.

\[ \] run compute-to-data on the dataset and provide output to the
approved Ocean marketplace customer

### Which category best describes your project?

Build / improve applications or integrations to Ocean

### What is the final product?

A proof-of-concept of a storage and monetization paradigm using
compute-to-data on private aggregate datasets within a specialized guild
/ bubble of healthcare data providers, analysts and consumers.

### Question on “value add” criteria: which one or more of the criteria will your project focus on? Why do you believe your team will do well on those criteria?

Usage of Ocean - A long-term goal of ours is to unlock value in US
healthcare data silos with Ocean Protocol based technology. As a first
step, we wish to create a proof-of-concept of a paradigm to store,
analyze and monetize these datasets for their aggregators and
**ultimately provide control to each patient over their own data**.

The largest neurophysiology companies provide services in \~ 100,000
surgeries a year, and the combined case coverage for companies based in
the US is \~ 750,000 [cases](https://ionm.uconn.edu/). Although the
total case volume is large, the types of cases (e.g. neck, thorax, low
back, brain aneurysms, tumors etc) being covered are many and the
patient population is varied. Hence an individual company lacks the
ability to collect sufficient data for machine learning.If a successful
data guild of stakeholders around these datasets can be formed, multiple
data providers, analysts and consumers will be onboarded to the Ocean
Marketplace contributing to its success.

Community - By establishing this paradigm of a data guild of
stakeholders for private, regulated, healthcare data on the Ocean
Marketplace, we will enable the Ocean community to develop similar
solutions in other verticals including other areas of healthcare as well
as other regulated and privacy sensitive industries (e.g. legal). We
expect the Ocean, as well as, the larger AI/ML community will develop
several novel algorithms for this guild and drive more value to the
Ocean marketplace.

Using their experience and connections in the surgical neurophysiology
field, the built-out core team will network with large and small
surgical neurophysiology company executives to deploy the service as a
long-term goal. The core team has a deep understanding of the vertical
allowing them to proactively respond to the customer needs and
specifications. The US Northeast, where the project lead is based, is at
the forefront of this field and sets the ‘standard of service’ for other
regions of the country.

### Funding Requested

3000 USD

### Proposal Wallet Address

0x4fDCCF789B8631110A942AD1A8663cE054846e21

### Have you previously received an OceanDAO Grant: No

-Discord Handle (if applicable): @mnkyntigr

-Project lead Contact Email: <nomesg2020+OceanDAO@gmail.com>

-Country of Residence: United States

### Part 2 - Team

Core Team

Ambarish S. Ghatpande, PhD, CNIM

    Role: project lead / coordinator

Relevant Credentials:

    LinkedIn: https://linkedin.com/in/ambarishghatpande 1

    Github: https://github.com/aghatpande

Experience and Background

    Statistical analysis and machine learning using R/RStudio 2013 - present

    Surgical neurophysiologist III with SpecialtyCare 2016 - 2021

    Surgical neurophysiologist Sentient Medical Systems 2015 - 2016

    Senior Research Scientist Lupin Ltd 2014

    Research positions at University of Colorado, Monell Chemical Senses Center and University of Maryland (2000-2013)

    PhD, dissertation in ion channel biophysics 1993 - 2000

Datona Labs Ltd / Principal: David N. Potter

    Role: privacy solutions expert / coder

Relevant Credentials:

    LinkedIn: https://www.linkedin.com/in/david-potter-2443332/ 1

Background/Experience

A senior software engineer with a history of developing and assuring
safety critical software in the rail and aviation industries. I’ve been
developing blockchain solutions since 2013 and am currently building a
decentralised privacy platform with associated DApps using linux,
javascript, solidity, web3.js, figma, react and styled components and
expertise in applied cryptography.

    Founder & CTO Datona Labs 2019 - present

    Independent software assessor for rail accident investigation team Hong Kong government 2018 - present

    Technical authority Hitachi 2016 - 2020

    Founder & CTO OpenSig 2016 - present

    Independent safety assessor Kawasaki 2015 - 2019

    Software safety assurance Ebeni 2012 - present

    Independent safety assessor Lloyd’s Register Beijing - 2011

    Technical authority Invensys Rail 2003 - 2011

    Technical consultant EADS 2003

    Technical consultant Silver Atena 2000 - 2002

    Software consultant Ultra Electronics 1999

    Software engineer Westinghouse Rail 1997 - 1999

    Software engineer Ultra Electronics 1996 - 1997

    BSc computer science University of York - 1996

We are scouting for academic neurophysiologists and senior executives in
neurophysiology / healthcare / AI companies to be members of the core
team.

### Advisers

Ongoing discussions with Ocean Protocol grantees in the healthcare and
AI space.

### Proposal Details

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
including those in the brain) surgeries. There are approximately 750,000
such surgeries performed annually in the United States and this case
coverage is growing every year.

During surgery, the surgical neurophysiologist present in the operating
room records neurophysiological data from the patient and runs tests at
the request of the surgeon. This allows the surgeon to operate avoiding
injury to neural tissue. For example, during brain tumor excision, a
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
other but are wary of this due to competition.

We believe two key requirements need to be met to onboard healthcare
data stakeholders. A legal mechanism to store and monetize the data,
and, a collaborative mechanism that ensures the individual datasets
remain private. Our proposed paradigm includes an inexpensive,
decentralized storage solution (e.g. Filecoin), absolute control of data
in the hands of the individual data providing company with fine-grained
layers of privacy. Furthermore, the providers should be able to publish
their dataset attributes / metadata with compute-to-data permissions
within the bubble. A data guild- / individual data provider- authorized
customer should be allowed to run compute-to-data ML algorithms on these
datasets and to access the predictive models / insights outputted by the
algorithm.

Demonstrating assured privacy and security for patients, data
aggregators, service providers and consumers using Ocean Protocol and
Datona Labs technology will be the primary goal for this proposal.

Using inputs from these stakeholders and after consultation /
collaboration with the Ocean Protocol developer community, the team will
outline legal and realistic solution/s to these problems based on the
paradigm described above.

### Project Deliverables

#### Any prior work completed thus far?

The project lead has **published two test datasets (vital\_signs\_1 &
2)** which can be used for predictive models using supervised learning.
The supervised learning algorithm is also working using R code and is
able to predict a patient’s insurance status. We will publish this as an
appropriate compute-to-data ML algorithm as part of our deliverables.
Running these ‘useful in real-life’ predictive models do not require
specialized compute infrastructure (e.g. GPUs) and are appropriate as a
proof-of-concept. The project lead is also contributing to the Algovera
AI hacking sessions actively to understand the intricacies of
compute-to-data. Basic code for privacy bubbles is mature and will be
appropriately customised.

#### What is the project roadmap?

The milestones will be worked on concurrently and delivery dates are an
approximate projection

Filecoin Plus storage and retrieval of dataset - End of January 2022

Publishing a private dataset suitable for supervised learning algorithms
and a relevant compute-to-data algorithm on Ocean Marketplace - Feb 2022

Custom ‘bubble’ to allow multiple variations of access and permissions
for all types of stakeholders - Feb 2022

Authorized customer (Ocean community member for the proof-of-concept)
purchases access to the dataset with permission to run the approved
algorithm, runs the algorithm and takes delivery of the predictive model
described earlier - March 2022

Once we have a proof-of-concept, we will approach neurophysiology
companies for outreach and iterate on the paradigm using their inputs.

We hope to deploy our service when a good market-fit is achieved,
perhaps, requiring multiple iterations of our paradigm along with other
necessary developmental processes.

#### Final delivery of proof-of-concept paradigm

end of March 2022

### Please include the team’s future plans and intentions.

We hope to successful implement this paradigm in the neurophysiology
field as our major goal by end of 2022. This should kindle interest
amongst other types of health provider companies (e.g. anesthesia
providers that typically work closely with surgical neurophysiologists
in the operating room) and stimulate their adoption of Ocean Protocol.

Our mission is to become a nationally accredited, specialized service
providing healthcare companies with storage, analytics and monetization
of their data on the Ocean Marketplace, while ensuring patient rights
and privacy. Funds requested in this proposal will allow us to develop a
*proof-of-concept* of such a service paradigm.
