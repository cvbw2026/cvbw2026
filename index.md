---
layout: splash
author_profile: false
comments: false
permalink: /
speakers:
  - url: https://www.sralab.org/researchers/r-james-cotton-md-phd
    image_path: https://cvbw2026.github.io/assets/speakers/james.jpg
    alt: "R. James Cotton"
    caption: "R. James Cotton, Northwestern University"
  - url: https://scholar.google.com/citations?user=T9gE8P0AAAAJ&hl=en
    image_path: https://cvbw2026.github.io/assets/speakers/marilyn.png
    alt: "Marilyn Keller"
    caption: "Marilyn Keller, ETH Zurich"
  - url: https://www.patricklucey.com/
    image_path: https://cvbw2026.github.io/assets/speakers/patrick.jpg
    alt: "Patrick Lucey"
    caption: "Patrick Lucey, Stats Perform"
  - url: https://nmbl.stanford.edu/people/scott-uhlrich/
    image_path: https://cvbw2026.github.io/assets/speakers/scott.jpg
    alt: "Scott Uhlrich"
    caption: "Scott Uhlrich, University of Utah"

organizers:
  - url: https://scholar.google.com.au/citations?user=DFdwDKkAAAAJ&hl=en&oi=ao
    image_path: https://cvbw2026.github.io/assets/org/ethan.jpg
    alt: "Ethan Goan"
    caption: "Ethan Goan, QUT"
  - url: https://scholar.google.com.au/citations?user=anHgASIAAAAJ&hl=en&oi=ao
    image_path: https://cvbw2026.github.io/assets/org/akila.png
    alt: "Akila Hewa Thondilege"
    caption: "Akila Hewa Thondilege, QUT"
  - url: https://scholar.google.com/citations?user=T9gE8P0AAAAJ&hl=en
    image_path: https://cvbw2026.github.io/assets/org/marilyn.png
    alt: "Marilyn Keller"
    caption: "Marilyn Keller, ETH Zurich"
  - url: https://ndfcampbell.org/
    image_path: https://cvbw2026.github.io/assets/org/neil.jpg
    alt: "Neil D. Campbell"
    caption: "Neil D. Campbell, University College London"
  - url: https://david-pagnon.com/fr/en-deux-mots/
    image_path: https://cvbw2026.github.io/assets/org/davidpagnon.jpg
    alt: "David Pagnon"
    caption: "David Pagnon, University of Bath"
  - url: https://researchportal.bath.ac.uk/en/persons/dario-cazzola/
    image_path: https://cvbw2026.github.io/assets/org/dario.jpg
    alt: "Dario Cazzola"
    caption: "Dario Cazzola, University of Bath"
  - url: https://people.csiro.au/a/d/david-ahmedtaristizabal
    image_path: https://cvbw2026.github.io/assets/org/dahmedt.jpg
    alt: "David Ahmedt"
    caption: "David Ahmedt, CSIRO"
  - url: https://people.csiro.au/H/S/Simon-Harrison/
    image_path: https://cvbw2026.github.io/assets/org/simonharrison.jpg
    alt: "Simon Harrison"
    caption: "Simon Harrison, CSIRO"
  - url: https://experts.griffith.edu.au/21209-luke-kelly
    image_path: https://cvbw2026.github.io/assets/org/lukekelly.jpg
    alt: "Luke Kelly"
    caption: "Luke Kelly, Griffith University"
  - url: https://www.qut.edu.au/about/our-people/academic-profiles/c.fookes
    image_path: https://cvbw2026.github.io/assets/org/clint.png
    alt: "Clinton Fookes"
    caption: "Clinton Fookes, QUT"
  - url: https://www.qut.edu.au/about/our-people/academic-profiles/glen.lichtwark
    image_path: https://cvbw2026.github.io/assets/org/glen.jpg
    alt: "Glen Lichtwark"
    caption: "Glen Lichtwark, QUT"


excerpt: "CVPR 2026 -  June 3-7, Denver, Colarado"
header:
  overlay_image: "assets/header.png"
---
<style>
  .half {
      display: flex; /* Ensures the elements inside are laid out in a row */
      justify-content: space-around; /* Adds space around the items */
      align-items: center; /* Vertically centers the items in the container */
      width: 100%; /* Makes the figure element take the full width of its parent */
  }
  .half video {
      width: 100%; /* Makes the video take the full width of its container */
      height: auto; /* Ensures the height adjusts to maintain the aspect ratio */
  }
  .half img {
      width: 100%; /* Adjusts the image to take the full width of its container */
      height: auto; /* Maintains the aspect ratio of the image */
  }

  .gallery-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .gallery-container.single figure {
    flex: 0 1 100%;
  }

  .gallery-container.half figure {
    flex: 0 1 calc(47% - 5px);
  }

  .gallery-container.third figure {
    flex: 0 1 calc(31% - 10px);  /* Adjusted to divide the space into thirds precisely */
  }

  .gallery-container.fourth figure {
    flex: 0 1 calc(22% - 15px);  /* Adjusted to divide the space into thirds precisely */
  }

  .gallery-image, .fixed-height-img {
    height: 300px; /* Fixed height for all images */
    object-fit: cover; /* Ensures the image covers the fixed dimension without distortion */
    width: 90%; /* Adjust width to maintain aspect ratio */
  }

  .gallery-container figure {
    display: inline-block;  /* Makes sure figures are aligned as inline elements */ß
    text-align: center;    /* Center-aligns the title */
    margin: 5px;          /* Provides some space around each image */
    vertical-align: top;   /* Aligns items to the top, useful for multi-row galleries */
  }

  /* Adjustments for smaller screens */
  @media (max-width: 450px) {
    .gallery-container figure {
      flex: 0 1 100%;
    }
  }
  @media (max-width: 768px) {
  .gallery-container.half figure,
  .gallery-container.third figure {
    flex: 0 1 calc(47% - 5px)!important;  /* Using `!important` to ensure this rule takes precedence */
  }
}
  @media (max-width: 450px) {
  .gallery-container.half figure,
  .gallery-container.third figure {
    flex: 1 0 100%!important;  /* Using `!important` to ensure this rule takes precedence */
  }
}

  .gallery-container figtitle {
    font-size: 1.35em; /* Increases the font size of titles */
  }
</style>

Human movement analysis is entering a new era driven by advances in computer vision and machine learning. Accurate estimation of body pose, shape, motion, forces, and joint dynamics is crucial for translating visual data into meaningful biomechanical insights. Yet, challenges such as data variability, limited annotations, and domain generalization persist. This workshop explores emerging intersection of computer vision and biomechanics, bringing together researchers and practitioners to discuss new methods, datasets, and applications that bridge perception and physical understanding enabling precise, data-driven insights and extending the impact of vision-based biomechanics across diverse domains such as rehabilitation, sports performance, and injury prevention.



<div id='important'></div>
## Important Dates

- January 23 - [Submission Opens](https://openreview.net/group?id=thecvf.com/CVPR/2026/Workshop/CVBW#tab-recent-activity)
- March 15 - Submission Deadline
- April 7 - Notification
- April 11 - Camera Ready
- June 3-4 - Workshop


<div id='call_for_papers'></div>
## Call for Papers

Submission Link can be found [here](https://openreview.net/group?id=thecvf.com/CVPR/2026/Workshop/CVBW#tab-recent-activity).

This workshop will be accepting short papers (4 pages excluding references and appendix). Topics of interest for this workshop include, but are not limited to,

- Computer vision for injury prevention and rehabilitation monitoring
- Computer vision for movement disorder assessment
- Vision-based musculoskeletal modeling and simulation
- Physics informed neural networks for musculoskeletal modeling and simulation
- Predicting ground reaction forces and center of pressure from video data
- Multimodal data fusion: integrating vision with wearable sensors for better biomechanics
- Open datasets, benchmarks, and reproducibility in biomechanical vision research
- Ethics, privacy, and fairness in vision-based biomechanics
- Clinical evaluation metrics and explainable models for computer vision enabled biomechanics
- Privacy preserving approaches to enable computer vision for biomechanical analysis
- Deploying vision-based biomechanics in low-resource settings and on consumer grade devices


Researchers interested in contributing should upload a short paper of up to 4 pages (not counting references and appendices) by **March 15, 2026, 23:59 AoE**. The link for submission is available [through OpenReview here](https://openreview.net/group?id=thecvf.com/CVPR/2026/Workshop/CVBW#tab-recent-activity). References and supplementary material can exceed 4 pages.  Please upload a single PDF that includes the main paper and any supplementary material. Submissions that exceed 4 pages or submissions with significant formatting violations will be rejected.

Authors should use the same CVPR LaTeX style provided on the main website [here](https://github.com/cvpr-org/author-kit/archive/refs/tags/CVPR2026-v1(latex).zip). (If clicking on the link does not work, please copy the link and paste in your browser tab). Submissions don't need to be anonymized. The workshop allows submissions of papers that are under review or have been recently published in a conference or a journal. Authors should state any overlapping published work at the time of submission. The workshop will not have any official proceedings, so it is non-archival.

All submissions will be reviewed and will be evaluated on the basis of their technical content. Accepted papers will be selected for either a short oral presentation and/or poster presentation.

Following CVPR review guidelines, authors of papers may be recruited as reviewers for this workshop.

If you have any questions or difficulty submitting your paper, contact us at [cvbw2026@gmail.com](cvbw2026@gmail.com).



<div id='invited'></div>
## Invited Speakers
{% include gallery id="speakers" class="full" layout="half" %}

<div id='program'></div>
## Program

TBC

<div id='organising'></div>
## Organising Team
{% include gallery id="organizers" class="full" layout="half" %}


<div id='contact'></div>
## Contact

[cvbw2026@gmail.com](cvbw2026@gmail.com)
