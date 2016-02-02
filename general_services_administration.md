# General Services Administration (Integrated Award Environment)

*by Navin Vembar*

[Download PDF version](http://www.agilegovleaders.org/wp-content/uploads/2015/06/CaseStudyAgileGovernmentandGeneralServicesAdministrationIntegratedAwardEnvironment.pdf)

Intro

It’s really a question of how to scale: While it’s important to note that a key aspect of Agile is to break down problems into small enough chunks so they can be managed successfully, one must always keep in mind the larger picture that is critical in most government environments. That larger picture often is motivated by a mission need that drives forward an organization in its entirety.

## Context

For this case study, let’s look at  my organization, the U.S. General Services Administration’s Integrated Award Environment (IAE). The IAE manages 10 federal information technology systems that enable registering, searching, and applying for federal awards, as well as tracking them. The IAE also manages the Federal Service Desk.

Each of the 10 applications managed by the IAE are government-wide and each collects and stewards data about acquisitions, grants, loans, and other government awards. In addition to being used throughout the government, the systems are used by a large population of business owners, grants seekers, and other public entities trying to conduct business with the federal government.

The largest of the 10 systems is a prime example of a key IAE system: The System for Award Management (SAM) is where all entities that want to do business with the federal government must register. The Federal Procurement Data System (FPDS) is where all contract actions over the Simplified Acquisition Threshold are captured. And FedBizOpps (FBO) provides information about business opportunities throughout the government. All 10 systems and their functions are listed here:

http://www.gsa.gov/portal/content/105036

The one thing that unites them all? Each one needs to be modernized. With each system, their user interfaces (and experiences) are outdated and the data contained within them are siloed and more difficult to use than should be.

## Motivation

Given both the public nature of the IAE applications and the complexity of managing a large transformation, much had to be carefully considered and managed.

The IAE staff had to find a way to break down the problem of modernization into manageable chunks that would demonstrate progress, but we also had to be sure to capture a wide variety of user needs with the ability to respond to those needs throughout development. It became clear that a sea change was needed in how the IAE worked.

We decided to embrace Agile methodology.

With that significant change, it became critical for us to understand how to make Agile work specifically for an organization of more than 100 people (when considering government employees and multiple contractors).

We chose to shift our way of working from the traditional waterfall method to the customized Scaled Agile Framework (SAFe).

## Experience

### An Initial Test of the Process

As a first step in the new Agile environment, we tried our hand at a smaller, single-scrum team project. We used a small amount of money to create an API for SAM.gov during three two-week sprints. As an added challenge, we had to work out the logistics of executing on Agile within GSA, an agency that relies heavily on telework. In this case, we had a product owner who works in Florida while the rest of our team was spread across the metro Washington, DC area.

To succeed, we relied on IBM’s RTC tool for our scrum board and on Adobe Connect for our daily scrum sessions. Once we finished the 6 weeks, we found ourselves at the end of a successful release and even more enthusiastic about moving forward with Agile. We conducted two more releases on the API and improved it further. We also launched a SAM Status Tracker as a client of the API, to help users look up their registration status.

### Scaling up

Once we awarded our Platform-as-a-Service contract, we migrated over to JIRA as our primary tool, as that was part of the larger suite of tools we were using for continuous integration. We added the JIRA Structure and JIRA Portfolio plugins to manage our entire SAFe epic/feature/story structure. This allows us to collaborate between a larger set of teams, share documentation using JIRA Confluence with the distributed team, and, most importantly, make leadership decisions at the portfolio level while letting the teams execute on their products. However, the tools are not always ideal for our scenario. This has lead to some research currently going on to determine if we can configure them to work as we need.

Our timeline is long; we have a four-year plan of which we currently are in the first year. Because of the nature of the systems we manage within IAE and how they are integrated into the larger community, we release only on a quarterly basis. Even so, we are executing on a bi-weekly sprint cycle that we intend to synchronize through the use of a release train manager.

The IAE still is maturing as an organization, so we have not yet reached that milestone. Our plan is to conduct two releases of foundational platform development, the second one ending in June. We then will begin executing on application development, starting with some low-hanging fruit and then leading rapidly in the latter part of this calendar year into a revamp of the FedBizOpps.gov application. That revamp will be heavily reliant on user engagement.

## Results

Within the IAE, we are excited about using Agile for our execution. Early on, we have found that it’s not always the easiest transition to pull off, and we’ve definitely hit a few stumbling blocks in making sure that we, ourselves, as a team were entirely ready.

But as we mature, we are confident we will hit our schedule, produce quality applications, and most importantly, learn from user input on how to provide the best experiences for them.

