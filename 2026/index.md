---
layout: workshop
year: 2026
date: April 26th or 27th, 2026
location: ICLR 2026
openreview: https://openreview.net/group?id=ICLR.cc/2026/Workshop/Re-Align
show_cfp: true
show_cfcr: true

cover_image:
  image: "/assets/images/locations/rio.jpg"
  author: Rafael Rabello de Barros
  licence_name: "CC BY-SA 3.0"
  licence_link: "https://creativecommons.org/licenses/by-sa/3.0/"

buttons:
  - text: OpenReview
    url: https://openreview.net/group?id=ICLR.cc/2026/Workshop/Re-Align
  - text: ICLR.cc
    url: https://iclr.cc/virtual/2026/workshop/10000807

cfp:
  intro: |
    We invite the submission of papers for presentation at the ICLR 2026 Re-Align workshop.
    We broadly welcome submissions related to representational alignment
    among artificial and biological information processing systems.
    Submissions can come from any area of cognitive science, neuroscience,
    machine learning, or related fields. We welcome
    **short** (up to 5 pages + references and appendix) or
    **long** (up to 10 pages + references and appendix)
    technical and position papers.

    (*For submissions related to the Re-Align Challenge, please see the
    [call for challenge reports](#cfcr).*)

  dates:
    - event: Paper submission deadline
      date: Thursday, February 5th, 2026
    - event: Reviewing deadline
      date: Thursday, February 26th, 2026
    - event: Author notification
      date: Sunday, March 1st, 2026
    - event: Camera-ready deadline
      date: Sunday, April 19th, 2026

cfcr:
  intro: |
    [Research in representational alignment converges on central questions but diverges in its answers.](https://arxiv.org/abs/2310.13018) Building on our
    successful [hackathon](/2025#hackathon) from last year, we have prepared the 
    <a href="https://github.com/representational-alignment/challenge" class="btn btn-secondary btn-xs" target="_blank">Re-Align Challenge</a> to
    promote transparency, reproducibility, and collaboration in representational alignment
    research. The challenge provides access to
    efficient implementations of representational comparison measures and a leaderboard for
    friendly competition on a representational alignment benchmark.

    We invite submissions of **challenge reports** as companions to leaderboard submissions.
    For leaderboard submissions to be considered as ICLR 2026 workshop contributions, authors must submit
    a challenge report through OpenReview that will undergo review by the [organizing committee](#organizers).

    (*Position papers and other contributions **not** directly tied to leaderboard submissions
    should be submitted to the [call for papers](#cfp).*)

  dates:
    - event: Challenge report submission deadline
      date: Thursday, February 26th, 2026
    - event: Author notification
      date: Sunday, March 1st, 2026
    - event: Camera-ready deadline
      date: Sunday, April 19th, 2026

speakers:
  - name: David Bau
    affiliation: Northeastern University
    website: https://baulab.info/
    image: profile_bau.png
  - name: Arturo Deza
    affiliation: Artificio
    website: http://arturodeza.wikidot.com/
    image: profile_deza.jpg
  - name: Judy Fan
    affiliation: Stanford
    website: https://psychology.stanford.edu/people/judith-ellen-fan
    image: profile_fan.jpg
  - name: Alona Fyshe
    affiliation: University of Alberta
    website: https://webdocs.cs.ualberta.ca/~alona/
    image: profile_fyshe.webp
  - name: Phillip Isola
    affiliation: MIT
    website: https://web.mit.edu/phillipi/
    image: profile_isola.jpeg
  - name: Danielle Perszyk
    affiliation: Amazon AGI SF Lab
    website: https://scholar.google.com/citations?user=jLcGAcQAAAAJ
    image: profile_perszyk.jpg

organizers:
  - name: Badr AlKhamissi
    affiliation: EPFL
    website: https://bkhmsi.github.io/
    image: badr.jpeg
  - name: Brian Cheung
    affiliation: MIT / UCSF
    website: https://briancheung.github.io/
    image: brian.jpg
  - name: Dota Dong
    affiliation: MPI for Psycholinguistics
    website: https://tianaidong.github.io/
    image: dota.jpg
  - name: Erin Grant
    affiliation: NYU / UAlberta
    website: https://eringrant.github.io/
    image: erin.jpeg
  - name: Stephanie Fu
    affiliation: UC Berkeley
    website: https://stephanie-fu.github.io/
    image: stephanie.jpg
  - name: Kushin Mukherjee
    affiliation: Stanford
    website: https://kushinm.com/
    image: kushin.jpeg
  - name: Ilia Sucholutsky
    affiliation: NYU / Purdue
    website: https://ilia10000.github.io/
    image: ilia.jpeg
  - name: Siddharth Suresh
    affiliation: UW-Madison / Amazon AGI SF Lab
    website: https://www.sidsuresh.com/
    image: sid.jpg

news:
  - content: The <a href="#cfp">call for papers</a> and <a href="#cfcr">call for challenge reports</a> are now live!
  - content: The 2026 edition of Re-Align was accepted as a <a href="https://iclr.cc/virtual/2026/workshop/10000807">workshop</a> at <a href="https://iclr.cc/Conferences/2026/">ICLR 2026</a>!

about: |
  The [first](/2024) [two](/2025) editions of the Workshop on Representational Alignment (Re-Align) at ICLR established a community
  bringing together researchers from **machine learning, neuroscience, and cognitive science** to tackle a foundational
  question: [How can we meaningfully compare and align the internal representations of intelligent systems?](https://arxiv.org/abs/2310.13018)

  Building on this foundation, the third edition of the Re-Align Workshop at ICLR pivots from asking *how* we measure
  alignment to *what we can conclude from observing alignment*. In particular, our next edition brings focus on what
  **affordances alignment makes possible**. In other words, **what can we do with alignment?**

  The workshop this year has two interdisciplinary focus areas:

  **1. Neural control.** When does representational alignment allow us to
  meaningfully intervene on a system's behavior? In AI, this connects to the goals of mechanistic interpretability
  and the engineering challenge of building safer, steerable models. In neuroscience, it parallels the long-standing
  goal of understanding how local neural activity gives rise to global function. By exploring how to identify, control,
  and even compose representations of specific functions or concepts, we create a shared framework for moving from
  simply mapping circuits to actively understanding their causal role in both artificial and biological systems.

  **2. Downstream behavior.** While much work in representation learning focuses on acquiring useful base
  representations, representational alignment enables a new capability: targeted control over how those
  representations are deployed for specific tasks. This moves us beyond asking "does the model know X?" to
  "can we steer when and how the model applies X?". We need tasks that assess whether a system's features can be
  dynamically reconfigured to meet novel demands in complex domains like collaboration and communication. We invite
  contributions exploring how alignment transforms static representations into controllable computational primitives.

  In addition, this year we introduced a new component, the [Re-Align Challenge](#cfcr).

program_committee:
  - name: To be announced.
---
