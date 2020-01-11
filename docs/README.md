---
pageClass: home-page
# some data for the components

name: Vladimir Juárez
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/vladimirjv
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/vladimir-juarez/
  - title: gitlab
    icon: "/icons/gitlab-mono.svg"
    link: https://gitlab.com/vladimirjv
  - title: devto
    icon: "/icons/devto.svg"
    link: https://dev.to/vladimirjv
  # - title: instagram
  #   icon: "/icons/instagram-mono.svg"
  #   link: https://www.instagram.com

cv: docs/ivladimirjuarezcv.pdf
bio: Software Developer 💻
email: ivladimirjuarez@gmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Always disciplined and committed with my passions, technology, **automation**, and the **IoT**.

I learned persistently and improved my **soft skills** 📣 working in great teams, developing and building different projects, also leadership skills helped me to perform and adapt to circumstances to deliver in a deadline.


## News

- [Feb 2019] - [Jan 2020] I worked in **Stackcode** at ***Veracruz***, ver as **Software Developer**.
- [Nov 2019] I graduated as **Mechatronic Engineer** at [Instituto Tecnológico de Veracruz](http://www.itver.edu.mx/) with a specialization in **automation**.
- [Mar 2019] I finished college at [Instituto Tecnológico de Veracruz](http://www.itver.edu.mx/).
- [Aug 2018] - [Feb 2019] I made my ***internship*** in **Mabe Typ** at **Quéretaro**.



## Education & Experiences

- **Instituto Tecnológico de Veracruz (Mechatronic Engineer)** <br/>
Aug 2014 - March 2019
- [**Diploma In Computing Systems (Computación del golfo)**](docs/systemsDiploma.pdf) <br/>
May 2015
- [**Diploma Industrial Automation (Computación del golfo)**](docs/automationDiploma.pdf) <br/>
Oct 2016


## Projects


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  **The Making of Harry Potter's Wand**

  Harry P., Hermione G., *et al*
  
  Harry's wand was broken in 1997, but was repaired by him after the 1998 Battle of Hogwarts. Usually the repair of a wand is impossible, but with the use of the Elder Wand it was achievable.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **Harry Potter and the Deathly Hallows**
  
  In the epilogue of Deathly Hallows, which is set 19 years after Voldemort's death, Harry and Ginny are a couple and have three children: James Sirius Potter, who has already been at Hogwarts for at least one year, Albus Severus Potter, who is starting his first year there, and Lily Luna Potter, who is two years away from her first year at the school.

  [[Link](https://www.google.com)]

</ProjectCard>


## Awards & Honors

### Contests

- First place in **The Hogwarts House Cup**


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 16px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
