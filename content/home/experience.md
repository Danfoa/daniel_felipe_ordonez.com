---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
cms_exclude: true
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Assistant Researcher
    company: Institute of Robotics and Industrial Informatics (IRI - CSIC)
    company_url: 'https://www.iri.upc.edu/'
    company_logo: iri
    location: Barcelona - Spain
    date_start: '2020-11-01'
    description: |2-
        I Work under the supervision of [Dr. Francesc Moreno](https://www.iri.upc.edu/people/fmoreno/) on:
        * [Learning natural-looking legged locomotion with Reinforcement
        Learning techniques and template dynamical models](publication/icra-paper/)
        * [Interactive Perception-Action-Learning for Modelling Objects (IPALM)](https://sites.google.com/view/ipalm)
  - title: Student Researcher
    company: Institute of Robotics and Industrial Informatics (IRI - CSIC)
    company_url: 'https://www.iri.upc.edu/'
    company_logo: iri
    location: Barcelona - Spain
    date_start:  '2019-10-01'
    date_end: '2020-10-01'
    description: |2-
        Assisted in projects of:
        * Human hand motion forecasting and pose discretization for [Dr.Júlia Borràs Sol](https://www.iri.upc.edu/staff/jborras)
            - Calibrating and pre-processing of raw sensor data from [CyberGloves](http://www.cyberglovesystems.com/)
            - Visualization tool for pre-recorded hand motions
            - Processing of [KINE-ADL](https://data.mendeley.com/datasets/8mf4y2srgh/1) and study of motion trajectories and main poses using latent space obtained with a Variational Autoencoder
        * Virtual avatar generation from single RGB images for [Dr. Jordi Sanchez Riera](https://www.iri.upc.edu/staff/jsanchez)
            - Finetunning and extension of the VNect architecture for body parts segmentation and 3D body pose estimation  

  - title: Junior Research Assistant
    company: Invite Research (INVITE - Bayer AG)
    company_url: 'https://www.invite-research.com/'
    company_logo: invite
    location: Cologne - Germany
    date_start: '2018-10-01'
    date_end: '2019-09-01'
    description: |2-
        **Research project**:
        Manipulation of plastic bags (deformable materials) using a two-arm robot and 3D vision guidance. The system used multi-viewpoint stereographic cameras to detect the 3D structure of the material, infer robot grasping points, and plan and execute robot manipulations to reach the target material topology.
        * [**EP Pending Patent**: Autonomous Drum and Inliner Handling](publication/patent/)
        * [Project Presentation Video](publication/patent/)
        * [Final work certificate](uploads/invite-junior-researcher-report.pdf)

  - title: Robotics Intern
    company: Invite Research (INVITE - Bayer AG)
    company_url: 'https://www.invite-research.com/'
    company_logo: invite
    location: Cologne - Germany
    date_start: '2017-10-01'  
    date_end: '2018-04-01'
    description: |2-
        I worked in the manipulation system for handling deformable materials, using a two-arm industrial robot, 3th-party vision guidance, and force feedback. Additionally, I participated in the designing and construction of robot vacuum grippers for plastic bag manipulation and automation of robot tasks for a biotechnology laboratory, force/torque feedback.
        * [Final work certificate](uploads/invite-internship-report.pdf)

  - title: Software Developer
    company: Busescool
    company_url: 'https://busescool.com/'
    company_logo: busescool
    location: Bogota - Colombia
    date_start: '2016-03-01'
    date_end: '2016-10-30'
    description: Developed front and back-end of administrative tools that allowed the control and monitoring of Busescool’s realtime database and services

  - title: Engineering faculty tutor
    company: Universidad Nacional de Colombia
    company_url: 'https://unal.edu.co/en/'
    company_logo: unal
    location: Bogota - Colombia
    date_start: '2016-03-01'
    date_end: '2016-10-30'
    description: |2-
        Courses tutored:

        * Data structures and algorithms
        * Numerical methods
        * Control theory
        * Object-oriented programming
        * Basic programming

design:
  columns: '2'
---
  <!-- {{< youtube w7Ft2ymGmfc >}} -->
