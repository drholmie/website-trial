---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Graduate Student Researcher (PhD)
    company: RACELab
    company_url: 'https://sites.cs.ucsb.edu/~ckrintz/racelab.html'
    company_logo: racelab
    location: California, Santa Barbara
    date_start: '2021-09-22'
    date_end: ''
    description: |2- 
      Advised by Dr. Chandra Krintz and Dr. Rich Wolski
        * Flexible, robust schedulers for edge deployments  
        * Disaggregation of resources for FAAS programming
        * Distributed analytics for wildlife conservation
  - title: Research Intern
    company: Oracle
    company_url: 'https://labs.oracle.com/pls/apex/r/labs/labs/intro'
    company_logo: oracle
    location: California, Redwood City
    date_start: '2023-09-08'
    date_end: '2023-06-20'
    description: |2-
      Worked on improving concurrency and cold start latency in FAAS runtime systems for multi-tenant cloud environments
      * Profiled the impact of shared memory for serverless runtimes with JVM based applications
      * Improved cold starts by 9-29%, and memory usage by 1.2x, against native applications in a multi-tenant cloud     

  - title: Research Assistant
    company: Indian Institue of Science (IISc)
    company_url: 'https://cds.iisc.ac.in/research/labs/'
    company_logo: dreamlab
    location: Bangalore, India
    date_start: '2020-09-01'
    date_end: '2021-07-31'
    description: |2-
      Worked on distributed edge storage and emulation of edge deployments
        * ElfStore: Developed distributed storage and consistency for edge devices such as raspberry pis, nanos, etc
        * UltraViolet: Developed large scale docker deployments and network configurations to emulate IoT architectures        
        
  - title: Google Summer of Code (GSoC) Intern at CERN
    company: CERN
    company_url: 'https://hepsoftwarefoundation.org/activities/gsoc.html'
    company_logo: cern
    location: Remote (Bangalore, India)
    date_start: '2016-05-01'
    date_end: '2020-08-15'
    description: 
      Developed and designed a local replica of JAliEn central services for research and development. Containerised JAliEn, ALICE’s grid computing middleware, using docker deployments for developers to perform local testing and development. Accepted as Google Summer of Code proposal for the CERN ALICE project. Report can be found {{< staticref "https://medium.com/@animesh.leo/google-summer-of-code-2020-finale-4557564b9996" "newtab" >}} here {{< / staticref >}}

design:
  columns: '2'
---
