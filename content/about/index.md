+++
title = "About Me"
showDate = false
showDateUpdated = true
showWordCount = false
showReadingTime = false
heroStyle = "thumbAndBackground"
+++

## Background

I am currently a third year Ph.D student at the University of Wisconsin -
Madison studying computer science. I'm working on formal verification of
software as part of the [madPL](https://madpl.cs.wisc.edu/) group with my
advisor [Tej Chajed](https://www.chajed.io/).

Before moving to Madison, I got my undergraduate degree in Computer Science at
Michigan Technological University, graduating in December 2022. Previously, I
was a head teaching assistant in CS 400, Programming III after being a standard
teaching assistant my first semester in Wisconsin. While at Michigan Tech, I
served as a Learning Center Coach for four semesters, Teaching Assistant for two
semesters, and a Lab Instructor for one semester. During the summer of 2021, I
participated in the Google Summer of Code by working with
[NetworkX](https://networkx.org/) on implementing an Asymmetric Traveling
Salesperson Problem approximation algorithm. Blog posts from that project are
available on the
[Scientific Python blog](https://blog.scientific-python.org/tags/traveling-salesman-problem/).
The next summer, I was part of a Research Experiences for Undergraduates (REU)
program funded through the National Science Foundation. Working with
[Dr. Satish Puri](https://www.linkedin.com/in/satish-puri-a994a71a/), I
developed a multi-threaded C++ system for finding the approximate nearest
neighbor for polygons. During the summer of 2024, I overhauled the graph
visualization API in NetworkX, moving to an API design were all information is
read off the graph directly.

For more information, please see my [curriculum vitae](cv-schwennesen.pdf).

## Research Interests

My research interests lay in program verification, roughly speaking how we can
formally prove that programs behave correctly under all circumstances. My
current project seeks to reason about software updates, ensuring that a new
version of the program can successfully interpret persistent state and handle
interactions with the environment in a compatible way with the old version of
the program. This involves formally defining what it means for a message schema
to be compatible with another. We aim to build a verified update compatibility
checker for Protobuf and JSON. Before that I worked on
[`grackle`](https://github.com/mjschwenne/grackle), a program which generated
validated or proof-instrumented data marshaling and unmarshaling `go` code.
Though this process, I'm been learning more about proof assistants, specifically
`rocq`, although I have also worked with F★. My venture into the field of
programming languages has been extremely rewarding, blending all of the aspects
I love about theory with practical applications about how we can reason about
the behavior of programs.

## Other Interests

Computer science education is a secondary topic of interest for me. While
working with students over the last 4 years, I've seen a lot of different
methods to teach students computer science concepts and how they develop those
concepts into programs. Often, too much emphasis is placed on the final result
or program behavior, while ignoring the development progress itself.

Outside of my academia interests, I am passionate about open source software,
which I believe is important for a private and secure digital experience. In my
free time, I enjoy playing tabletop role-playing games such as Pathfinder or
Stars Without Number, watching movies, exploring the outdoors and cooking. You
can even find a collection of recipes on this website.

## Timeline

{{< timeline >}}

{{< timelineItem icon="graduation-cap" header="Master's Degree"

subheader="University of Wisconsin - Madison" badge="Dec 2025">}}

Obtained Master's degree in Computer Science from the University of Wisconsin -
Madison.

{{</timelineItem>}}

{{< timelineItem icon="graduation-cap" header="Passed Qualifying Exam"

subheader="Grackle: Automated, Verified Message Encoding and Decoding"

badge="Sept 2025">}}

I passed my qualifying exam, building off of the work I originally did for
Grackle. You can view my <a href="qual.pdf">presentation slides</a>.

{{</timelineItem>}}

{{< timelineItem icon="pencil" header="Midwest Programming Languages Summit"

subheader="University of Chicago" badge="Nov 2024">}} Attended MWPLS at the
University of Chicago. {{</timelineItem>}}

{{< timelineItem icon="code" header="NetworkX - New Graph Visualization API"
subheader="Indpendent Contract" badge="Jun 2024 - Aug 2024">}} Rewrote the
existing visualization API to be agnostic to the visualization tool (in this
case <code>matplotlib</code>), provide more flexibility and the potential for
visualization dispatching in the future. {{</timelineItem>}}

{{< timelineItem icon="pencil"

header="Tutorial - Software Tools for Supporting Network Science"

subheader="International School and Conference on Network Science"

badge="June 2024" >}} I presented a tutorial titled
<a href="https://netsci.nascol.net/school"><i>Software Tools for Supporting
Network Science</i></a> along with Tamás Nepusz from <code>igraph</code> and
Tiago Peixoto from <code>graph-tool</code> at NetSci 2024 in Québec City. {{<
/timelineItem >}}

{{< timelineItem icon="pencil" header="OPLSS@BU" badge="June 2024" >}} Attended
the <a href="https://www.cs.uoregon.edu/research/summerschool/summer24/">2024
Oregon Programming Languages Summer School at Boston University</a>. The topic
of the conference is Types, Semantics and Applications. {{< /timelineItem >}}

{{< timelineItem icon="graduation-cap" header="Began Graduate Studies"
subheader="University of Wisconsin - Madison" badge="Sept 2023" >}} Pursuing a
Ph.D. in Computer Science. {{< /timelineItem >}}

{{< timelineItem icon="graduation-cap"

header="Bachelor's Degree" subheader="Michigan Technological University"

badge="Dec 2022" >}} Graduated with a B.S. in computer science, minor in
mathematical studies. {{< /timelineItem >}}

{{< timelineItem icon="graduation-cap" header="Lab Instructor"

subheader="CS 1121 Introduction to Programming I"

badge="Jan 2023 - May 2023" >}} Worked with Sarah Larkin to teach CS 1121
Introduction to Programming I. This course is an introductory Java programming
course covering objects, loops, methods, code design, documentation and
debugging programs. My responsibilities included running a weekly lab
assignment, grading, holding office hours and proctoring exams. {{<
/timelineItem >}}

{{< timelineItem icon="graduation-cap" header="Undergraduate TA"

subheader="CS 3411 Systems Programming" badge="Aug 2022 - May 2023" >}} Worked
with Dr. Soner Onder (Fall 2022) and Dr. Jean Mayo (Spring 2023) to teach CS
3411 Systems Programming. This course includes file I/O using system calls,
process creation and management, linking and libraries, interprocess
communication and socket programming. My responsibilities included grading,
holding office hours, proctoring exams and developing automatic graders. {{<
/timelineItem >}}

{{< timelineItem icon="code" header="Research Experience for Undergraduates"
subheader="Marquette University" badge="May 2022 - Aug 2022">}} Worked on
finding the approximate nearest neighbors of polygons using locality sensitive
hashing. The work resulted in a multi-threaded C++ system using the developed
techniques. {{< /timelineItem >}}

{{< timelineItem icon="code" header="Google Summer of Code"

badge="May 2021 - Aug 2021" >}} Worked with NetworkX implementing the Asadpour
et al. algorithm to approximate the asymmetric traveling salesperson problem.
For more information, see

<ul>
  <li><a href="https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.approximation.traveling_salesman.asadpour_atsp.html">NetworkX documentation</a></li>
  <li><a href="https://blog.scientific-python.org/tags/traveling-salesman-problem/">Google Summer of Code Blog Series</a></li>
  <li><a href="https://pubsonline.informs.org/doi/abs/10.1287/opre.2017.1603">Original Paper by Asadpour et al.</a></li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="code" header="Learning Center Coach"

subheader="College of Computing - Michigan Technological University"

badge="Jan 2021 - Dec 2023" >}} Help students completing assignments for
beginning and intermediate classes at Michigan Technological University, on
topics including

<ul>
  <li>Data Structures</li>
  <li>MIPS and C programs</li>
  <li>Introductory Java programs</li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="graduation-cap"

header="Michigan Technological University"

badge="Aug 2019" >}} Began courses at Michigan Technological University pursuing
a degree in computer science. {{< /timelineItem >}}

{{< /timeline >}}
