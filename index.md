---
layout: page
title: About
---

<style>
.about-intro {
  display: grid;
  grid-template-columns: minmax(0, 1fr);
  gap: 1rem;
  align-items: start;
  margin-bottom: 1rem;
}

.about-photo {
  width: 300px;
  height: auto;
  margin: 0 auto;
  border-radius: 10px;
}

.about-bio > :last-child {
  margin-bottom: 0;
}

@media (min-width: 56em) {
  .about-intro {
    grid-template-columns: 300px minmax(0, 1fr);
  }
}
</style>

<div class="about-intro">
  <img class="about-photo" src="/assets/images/profile.jpg" alt="Ankit Mahajan">
  <div class="about-bio" markdown="1">

I am an Associate research scientist at the [Flatiron Institute](https://www.simonsfoundation.org/people/ankit-mahajan/) jointly appointed between the Center for Computational Quantum Physics ([CCQ](https://www.simonsfoundation.org/flatiron/center-for-computational-quantum-physics/)) and the Initiative for Computational Catalysis ([ICC](https://www.simonsfoundation.org/flatiron/initiative-for-computational-catalysis/)). I develop numerical approaches to tackle quantum many-body problems in strongly correlated materials and catalysis, with a particular focus on quantum Monte Carlo methods.

  </div>
</div>

Current research areas include:

- Auxiliary Field Quantum Monte Carlo for correlated electrons
- Interplay of electron-phonon coupling and strong electronic correlations
- Chirality and spin transport

## Education and work experience

- **Postdoctoral Researcher** - Columbia University  
  _Advisor: [Prof. David Reichman](https://reichmangroup.chem.columbia.edu/)_

- **Ph.D. in Chemical Physics** - University of Colorado, Boulder  
  _Advisor: [Prof. Sandeep Sharma](https://cce.caltech.edu/people/sandeep-sharma)_  
  Thesis: Stochastic electronic structure theory

- **Integrated Masters in Physics** - IIT Bombay  
  _Minor in Computer Science_

## Software & Code

I enjoy writing differentiable and performant code. Here are some examples:

- [trot](https://github.com/ankit76/trot): End-to-end differentiable Auxiliary Field Quantum Monte Carlo
- [nn_eph](https://github.com/ankit76/nn_eph): Neural quantum states for electron-phonon interactions
- [Dice](https://github.com/sanshar/Dice/tree/master): Suite of multi-reference electronic structure methods in C++

## Get in touch!

If you are a graduate student interested in working with me, you can apply to postdoctoral or predoctoral positions at [ICC](https://www.simonsfoundation.org/flatiron/initiative-for-computational-catalysis/) or [CCQ](https://www.simonsfoundation.org/flatiron/careers/?tab=job-openings&center=ccq). I am happy to discuss potential research opportunities and collaborations.

**Email:** ankitmahajan76 [at] gmail.com

**GitHub:** [ankit76](https://github.com/ankit76)
