---
title: Projects - Erica Scarpa
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
art: dots
projects:
  Current Focus:
    - name: 'H-SeTIS'
      link: 'https://h-setis.cnr.it/'
      desc: 'Heritage - Semantic Tools and Interoperability Survey. A comprehensive hub for systematically surveying and describing various semantic artefacts and tools relevant to the Heritage domain. (Co-Editor) '
      icon: 'i-ph-cactus'
    - name: '‹H/SORT›'
      link: 'https://hsort-ec1af2.gitlab.io/'
      desc: 'Heritage Science, with a Semantic Flavour. A collaborative platform dedicated to exploring and defining the conceptual foundations of Heritage and the broader Heritage Science domain. (Co-Editor)'
      icon: 'i-ph-carrot'

  Assyriology:
    - name: 'Ebla Digital Archives'
      link: 'http://ebda.cnr.it/'
      desc: 'Rebuilding the Oldest Archive in the History of Mankind in Digital Form. (Co-Editor)'
      icon: 'i-ph-castle-turret'
    - name: 'The City of Ebla Bibliography'
      link: 'http://ebda.cnr.it/biblio'
      desc: 'Complete bibliography referring to resources concerned with the ancient city of Ebla. (Author)'
      icon: 'i-ph-cherries'
    - name: 'The City of Ebla: A Primer'
      link: 'https://github.com/erica-scarpa/the-city-of-ebla-primer'
      desc: 'A foundational resource for those seeking a clear and engaging introduction to Ebla`s history, culture, and the ongoing research that sheds light on its enduring legacy'
      icon: 'i-ph-cat'

---

<!-- @layout-full-width -->
<ListProjects :projects="frontmatter.projects" />
