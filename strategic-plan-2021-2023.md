# Strategic Plan 2021-2023

BACKGROUND

The Ersilia Open Source Initiative \(EOSI\) is a UK-registered charity founded in November 2020 by three early career scientists who share the belief that scientific development in Low and Lower Middle Income Countries is a major player in their way to progress.

Our inspiration to start EOSI is well summarized in this extract from the WHO world health report 2013:

_The results of some research studies are widely applicable, but many questions about universal health coverage require local answers. All countries therefore need to be producers of research as well as consumers of it._

The current academic research system concentrates most of the scientific potential in High and Upper Middle Income Countries \(jointly, they account for over 90% of the science and engineering publications worldwide\). To revert this trend, the research capacity of LMIC institutions must be developed, handing them the leadership of research projects and putting the focus on their interests and needs. This change will enable:

* The establishment of a prosperous and sustainable research environment in LMICs, involving universities, companies and non-profit stakeholders that informs the policy-making organisms.
* The development of research lines that have at their forefront the best interests of their countries in health, environmental and technological challenges.
* The capacity to train the next generation of scientists and engineers, levelling up the education system.

We acknowledge that this is a vast challenge that requires a multi-pronged approach, and, as a starting small NGO, we had to narrow it to a specific area of action. Thus, based on our expertise and previous work, we have focused on:

**Drug discovery for infectious and neglected tropical diseases**: communicable diseases still account for over 50% of the disease burden in LMICs, but only 10% of the drugs currently in development are tackling this disease area. As diseases associated with poorer regions of the world, the return on investment is deemed too low by the pharma industry, which strengthens the need of LMICs to develop their own solutions, for example by leveraging the natural resources and the hundreds of years of accumulated expertise on traditional medicine and plant-based treatments.

**Implementation of artificial intelligence and machine learning \(AI/ML\) methods**: AI/ML holds the promise to revolutionize biomedical research. By analyzing large amounts of data in less time, it enables _in silico_ hypothesis testing, experiment prioritization and large-scale studies. Moreover, AI/ML is particularly suitable for low-resourced settings as it is relatively cheap to implement compared to experimental approaches. We believe there is no reason for the best computational centers to be in well-equipped facilities in the Global North. With the appropriate expertise, a moderate investment and leveraging existing cloud computing solutions, any university or research center can become a world class data center.

This strategic plan lays out the direction of EOSI for the next **three years** and draws the roadmap to set the basis of a strong, sustainable organization that is best positioned to contribute towards the development of a LMIC research network.

MISSION

EOSI mission is to strengthen the research capacity against infectious and neglected diseases by democratizing the access to machine learning tools.

VISION

Our vision is that of a world with egalitarian research capacity and access to healthcare.

VALUES

**Openness:** working in the “open” is one of the core tenets of EOSI. We aim to achieve 100% transparency at all levels, including scientific methodology, decision making processes and capital expenditures.

**Innovation:** we cherish creative thinking and support those with new, bold ideas.

**Empowerment:** we support the development from within the community to achieve independent and sustainable growth.

**Inclusion and Diversity:** we welcome people of all backgrounds and hope to grow as a diverse organization where everyone has an equal opportunity to contribute and learn.

**Integrity:** we are committed to always acting in the best interest of those we serve, with honesty and truthfulness.

**Accountability:** we are ready to take the responsibility of the projects we engage with.

STRATEGIC PLAN

This document was drafted in November 2020 by the EOSI co-founders, but we have taken nine months to reshape it before releasing this final version. The reason behind this is that we wanted to write a comprehensive, yet realistic, document that could serve as the roadmap for the development of the initiative. After a thorough exploration of the environment, the real needs of scientists in LMICs and the funding and collaboration possibilities, we have summarized our path in the following goals, which are primarily aimed at a\) building a sustainable organization b\) setting the basis of EOSI charitable work c\) developing what will become the main assets of the charity.

**Goal 1: Facilitate the access of AI/ML technologies to all scientists**

One of the main limitations for the implementation of AI/ML methods to day-to-day research, as reported by scientists themselves, is the lack of computational skills. With the popularization of AI/ML, the number of models developed and published in scientific journals has increased, but most of them, even if accompanied by the source code, are not accessible to the majority of researchers. To promote the re-usability of already generated resources and popularize the use of AI/ML in experimental laboratories, we aim to gather in a single platform a plethora of AI/ML models for drug discovery in neglected diseases. The Ersilia Model Hub is designed to be a user-friendly environment with pre-trained models ready-to-use in standard computers.

Objectives:

1. **Release of the Ersilia Model Hub**, understood as a fully working package that users can download and run in average computers, and, in 2022, develop an interactive website app where users can query the models online.
2. **Addition of 75 literature-based models per year** to the Hub, increasing the visibility and usability of already existing assets by third-parties. EOSI always acknowledges the original authors and maintains their license notices.
3. **Addition of 50 in-house trained models from key datasets per year** to the Hub, including data relevant to our tasks and findable in scientific databases and data produced by experimental collaborators.
4. **Precomputation and storage of frequent queries** in order to save computational resources and provide a faster service to our users.

Measurements of success and expectations:

* A functional Model Hub accessible from all computer systems \(Linux, MacOSX and Windows\) by September 2021.
* The number of models in the Hub, expected to serve 400 models by the end of 2023 \(including 250 models from the literature and 150 models in-house developed\).
* The number of Hub users, aiming to reach 100 new users per year.
* The number of Hub contributors, understood as authors that directly donate their models to the Hub. We hope to raise the interest of over 50 contributors by the end of 2023.
* The number of datapoints stored in our database, including, at least, pre computations for 1000 compounds and 50 models each year.

Resources needed:

* Data hosting and management: the code of the Hub is available as a GitHub repository. The datasets for model training, when available, are stored in Zenodo, and the pre-computed predictions will be stored in a cloud-based database such as DynamoDB. Both GitHub and Zenodo are free resources, and we aim at obtaining support for non-profit projects from AWS to maintain the DynamoDB database.
* Computers: in addition to standard laptops for each developer, an on-premises GPU unit is deemed essential for model training. We will also leverage open-source solutions \(FossHost\) and apply for access to academic resources such as the Barcelona Supercomputing Center.
* Personnel: to maintain the Hub backend system we will need to hire an IT developer \(expected by January 2022\) or, if it is not possible, to engage a community of volunteer programmers that can provide support. The model collection and training will be covered by EOSI scientists Dr. Duran-Frigola and Dr. Turon.

**Goal 2: Achieve sustainability for the Ersilia Model Hub**

The Ersilia Model Hub will grow to become the central asset of the charity, a platform that will not only provide access to AI/ML methods without the need to code, but also a platform for dissemination of research results, where scientists can report on the models they have used and contribute to their improvement, as well as a resource that stimulates scientific collaboration and solidarity. As such, it is essential that we define the next steps to ensure the maintenance and growth of the Hub.

Objectives:

1. **Engage relevant open-source stakeholders** for in-kind support and contributions, such as computational power and storage capacity.
2. **Increase revenue from Open-Source grants** as a complement to the research-oriented grants.
3. **Launch periodic crowd-sourcing campaigns** for Hub users and supporters to contribute to the mission.
4. **Establish a network of grant-making foundations** from the UK and abroad that are compelled by EOSI’s mission and are able to support our work with regular grants.

Measurements of success and expectations:

* Computer resources obtained, including at least one cloud-based computational unit and one terabyte of free storage.
* The number of open-source grants awarded. We expect to merit two grants/awards by the end of 2023 from organizations such as AWS, Google, the Mozilla Foundation or the Chan-Zuckerberg Foundation.
* The number of foundations engaged \(30 per year\) and donations raised \(5-10 per year\).
* The number of regular donors and one-off donors and the amount of money obtained via crowd-sourcing efforts, which we estimate to be 10.000 per year.

Resources needed:

* Personnel: we would highly benefit from having a fundraising volunteer or employee with experience in the field.
* Platforms: our main fundraising platform is Open Collective, which has the added benefit of offering full transparency in the transactions.

**Goal 3: Implement AI/ML routines in LMIC laboratories**

In addition to offering free access to pre-trained models via the Hub, we will engage in partnerships with LMIC institutions to develop tailored AI/ML tools and provide personalized support for their implementation.

Objectives:

1. **Establish partnerships with key researchers in the field**, to further support outstanding scientists in their home countries who can benefit from EOSI’s expertise and become stakeholders in the development of data science facilities in their institutions.
2. **Offer AI/ML introductory training lessons for university students**, to familiarize the next generation of scientists in the data science field and encourage them to seek AI/ML models that can be applied to their specific research interests
3. **Obtain support and funding to establish computation stations** in the host institutions, to ensure project continuation and sustainability once the collaboration with EOSI is completed.

Measurements of success and expectations:

* The number of signed Memorandums of Understanding \(MoU\), our goal is to establish relations with 5 new institutions per year, leading to 1-2 MoU.
* The number of students reached via our courses, aiming at providing training to a hundred per year.
* Funding raised towards computer core infrastructure, expected to reach 50.000USD before the end of 2023.

Resources needed:

* Personnel: the CEO is in charge of establishing new contacts with institutions and catalyzing them into specific projects and collaborations. EOSI scientists will share the courses’ workload. We would like to attract volunteers to support the courses, as we understand it is an engaging activity requiring a limited amount of time and with benefits for both the student and the teacher.
* Education: organizing courses and hands-on trainings is part of EOSI’s mission but it is not its core mandate. Therefore, partnering with specialized organizations is essential to avoid spreading too thin the limited resources available to EOSI. Such organizations include TreND in Africa, the University of Bern and the host institutions with whom we collaborate.

**Goal 4: Increase acceptance and popularity of computational research**

Data science projects often have to overcome two opposite, yet equally damaging, preconceptions. On one hand, the hype around AI/ML leads some researchers to think that it can magically solve any question, regardless of the problem and availability of data. On the other hand, skeptical users perceive AI/ML models as black boxes, and consider their predictions not reliable. We aim to find the middle ground, increasing the adoption of AI/ML thanks to use-case examples, strict open science guidelines and full documentation of each model, including training set, possible biases, application domain etc.

Objectives:

1. **Experimental validation** of AI/ML models thanks to our collaborators in the field.
2. **Radical Open Science approach** to all EOSI’s projects, which includes open-sourcing all the code and licensing it under a permissive MIT license \(when not restricted by other third-party licenses\), providing access to the original datasets used to train the models, or in its defect, the training parameters, and publishing monthly reports of our work, so EOSI can be held accountable at each step of the process.
3. **Publish the results in peer-reviewed journals** to obtain feedback and suggestions from fellow researchers. Moreover, we will only publish in open access journals in line with the Open Science ideal.
4. **Participation in international congresses and seminars**, increasing the visibility of the tools we develop and engage with the scientific community.

Measurements of success and expectations:

* The number of in-house developed models that have been tested _in vitro_ and/or _in vivo_. We aim to validate at least 10 models per year thanks to our collaborators.
* The number of papers accepted for publication with EOSI as affiliation, either as first/last author \(one per year\) or in co-authorship \(3 papers by the end of 2023\).
* Scientific audience reached via conferences, which are key to strengthening the research network and finding common interests with other groups, so we aspire at participating in 5-10 congresses/seminars each year.

Resources needed:

* Collaborators: identifying experimental scientists with whom to establish sustainable and productive bilateral relationships, where EOSI provides the data science expertise and they provide wet-lab capabilities is key to our mission
* Funding for publications and conferences: EOSI must identify sources of funding to cover open-access fees and conference registration and travel.

**Goal 5: Improve EOSI Governance and Organogram**

To fulfill the above-mentioned objectives, it is of foremost importance as a recently born organisation that we grow, increasing our operational capacity and involving the community, including stakeholders, beneficiaries and supporters in our activities and decision-making processes, to become an inclusive organization that answers the real needs of those whom it serves.

Objectives:

1. **Consolidate the Board of Trustees**, engaging people from different disciplines that are highly motivated by EOSI’s mission and willing to serve as trustees, a voluntary position key to ensure the charity’s governance.
2. **Create a community of Software developers** that are able to provide in-kind support and complement the expertise of EOSI staff.
3. **Engage students** in short-term, defined projects with the goal of both supporting EOSI’s mission and training the students for future work in academia or enterprise.
4. **Scale the operational capacity** by recruiting IT personnel that can handle the expansion of the Hub.
5. **Build a strong diversity and inclusion** work environment.

Measurements of success and expectations:

* The number of trustee’s, ideally a board of 5 to 6 trustees, which would encompass a sufficiently diverse set of skills and promote a healthy debate on key decisions.
* The number of GitHub commits as a measure of the open source software community engagement
* The number of students doing short term projects within EOSI. Due to the current size of the organization, and because we want to give each student the appropriate attention, we would like to have one student per semester only.
* The number of new personnel joining the organization. We expect to be able to expand our team in January 2022.

Resources needed:

* Personnel: we believe in the community power and welcome all efforts to support our mission, be it with time, expertise, network or funds, and wish to create a strong group of supporters. Nevertheless, to achieve our goals we must grow sustainably, adding Trustees to our board who can help guide our efforts and team members that supply expertise currently needed.
* Protocols to ensure we remain an inclusive organization with clear anti-discrimination practices

