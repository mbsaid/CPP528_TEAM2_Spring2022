---
title: About Us
team:
  - name: Caitlyn McCullers
    img: ../assets/images/cait.PNG
    desc: Caitlyn McCullers is currently pursuing her master's in Program Evaluation and Data Analytics. She is a data manager for ASU's project TEAS.
    github: https://github.com/ctmccull
  - name: Sarah Johaningsmeir
    img: ../assets/images/IMG_0294.jpg
    desc: Sarah Johaningsmeir is a student in Arizona State University's Program Evaluation and Data Analytics MS program. She works as a researcher in the Complex Care Program at the Medical College of Wisconsin and Children's Wisconsin.
    github: https://github.com/johaning
  - name: Ahmed Radwan
    img: ../assets/images/Ahmed radwan-edits.jpg
    desc: Ahmed Radwan is pursing his master’s in Program Evaluation and Data Analytics. He works as a data analyst at UnitedHealth Group.  
    github: https://github.com/radwan-a
  - name: Mohamed Said
    img: ../assets/images/mohamed.PNG
    desc: Mohamed Said works as Project Coordinator and researcher for SIDRA Institute in Somalia. He is currently pursuing his Masters in Program Evaluation and Data Analytics at Arizona State University (ASU).             
    github: https://github.com/mbsaid

---

#### Meet Team 2!


{% include list-circles.html items=page.team %}

## Website design source

The Jekyll website design was adapted from Niklas Buschmann's [contrast theme](https://github.com/niklasbuschmann/contrast).

## GitHub Repo

You can find the source code that powers this website [on this GitHub repo](https://github.com/R-Class/cpp-528-template).

<!--- CSS for Circles --->

<style>

/* now starting CSS for circles down below */
.list-circles {
  text-align: center;

}

.list-circles-item {
  display: inline-block;
  width: 240px;
  vertical-align: top;
  margin: 0;
  padding: 20px;
}

/* make the background a bit brighter than the current dark gray (#282828) */
.list-circles-item:hover {
  background: #5e5e5e;
}

.list-circles-item .item-img {
  max-width: 200px;
  height: 200px;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  border: 1px solid #777;
}

.list-circles-item .item-desc {
  font-size: 16px;
}

.list-circles-item .item-links {
  margin-top: 5px;
}

.list-circles-item .item-link {
  margin:0 3px;
  color: #FFFFFF;
  text-decoration: none !important;
}

.list-circles-item .item-link:hover {
  color: #000000;
}

</style>

