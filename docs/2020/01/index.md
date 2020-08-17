# Estimation Game: What is the Size of Requirements Documents in Industry?

## Author(s)

[Bernd Westphal](http://swt.informatik.uni-freiburg.de/staff/westphal/personalPage), Albert-Ludwigs-Universit&auml;t Freiburg, Germany, <westphal@informatik.uni-freiburg.de>

## Table of Contents

1. [Target Audience](#targetaudience)
2. [RE Skills Taught](#skills)
3. [Learning Goals](#goals)
4. [Summary of Activity](#summary)
5. [Context](#context)
6. [Prior Use](#prior)
7. [Future Work](#future)
8. [References](#references)


## Target Audience<a name="targetaudience"></a>

The target audience for this very small activity are the typical participants
of the topic area requirements engineering in our undergraduate introduction to
software engineering course [[1]](#ref0).  That is, our experience stems from undergraduate
students in the second year of an university B.Sc. program in Computer Science
who have (we asked!) received none or very little previous exposure to
requirements engineering concepts.


The estimation game as we use it does not require specific previous knowledge
on the side of the participants, so we can imagine that the activity can be
conducted in earlier semesters as well as in later semesters.  We conduct the
activity in larger groups yet it may as well be applicable in smaller groups
and within teaching formats different from our setting (a traditional
lecture).  What we consider important is that all participants are principally
able to look at all other participants during the estimation game (or other
means of distributing the results need to be set up).

## RE Skills Taught<a name="skills"></a>

The activity teaches less of a skill but more of a conception or
imagination of the challenges and complexities in practical requirements
engineering.  The aim is to increase appreciation for the procedures and
approaches taught in requirements engineering courses. 


## Learning Goals<a name="goals"></a>

The learning goals for our activity are as follows.

1. Share results of a survey on the preconceptions of course participants
   regarding the extension of requirements documents
   found in industry contexts.
   <br/>
   The activity should apply as well to any other quantifiable aspect of
   requirements engineering (like how many single requirements, how many
   revisions, etc.) for which there is a need to survey preconceptions and/or
   emphasise the presentation of findings.  For our purpose, the aspect
   "document size" is appropriate because it has a widely understood
   definition and almost immediately implies lower bounds on other aspects
   such as effort for writing, number of involved people, etc.
2. Establish a common conception for all participants to build on in the
   remainder of the course.
   <br/>
   The goal of the activity is to offer a mental image as a motivation for the
   relevance and difficulty of the whole topic area requirements engineering
   and thus firstly to prepare for the remainder of our course.  The hope is
   that following the course with motivation will help students to better
   connect to the praxis of requirements engineering later in their career.


## Summary of Activity<a name="summary"></a>

The activity is a variant of standard classroom questioning and the use of
images from the standard didactics and methods toolbox (cf. [[2]](#ref1),
[[3]](#ref2) for example) and takes the following form:

>   Lecturer: Oh, by the way, let us play a little estimation game to estimate
>   the extension (in number of pages if printed out) of requirements
>   documents that you may encounter in industry.
> 
>   Let's take a simple concrete example.  [The example can be anything
>   seemingly small, well imaginable, and sufficiently well understood by the
>   lecturer in case of follow-up questions.  We like the automotive domain of
>   which the manufacturer and supplier relation is well known.  Good
>   requirements specifications are important because they usually become
>   part of the contract between the two parties.  Examples from the
>   automotive domain include the charging subsystem of an electric car (the
>   component between charging station and car battery), or a central locking
>   system, or a tunnel sensor, etc.]
> 
>   Which extension (number of pages if printed out) would you expect to be
>   handed over from the design department to a supplier?
> 
>   The estimation game works as follows: I name increasing page numbers, and
>   you raise your hand if you think `that many or more'.

Then call out numbers, and give the audience enough time to decide on each
number and to look around how many hands remain raised:

>   1, 3, 10, 30, 50, 100, 200, 400

Time can be filled by encouraging participants to look around to see (!) other
participants' estimation, or by repeating the game's rule `that many or more'.

In my experience (recalled from memory) hands start to go down starting with
30 (hence, if students are not hacking the game, we find our hypothesis on the
reality of our students stated below supported).  Starting with number
100 the latest, we observe signs of hesitation whether to lower the hand,
considering the thought that this is just a ridiculous number to make fun of
the audience.  Usually, only two to three hands (of 20 to 30 students) remain
raised on number 400, presumably students with prior experience who we
regularly have in our audience.

> Okay, aha, 400.  Look around again on how few hands remain raised.

Then break the tension:

> Well, this is what I have been told by a member of such a department: 400
> pages.  On only this single car component.

Rhetorical follow-up questions or remarks:

> How many hours does it take to write this document?
> How likely are changes during this time?
> How many people does it take?
> Will it be the same persons during the whole time?
>
> And here we are: It is absolutely not uncommon that a statement on page 127
> plainly contradicts a statement on page 301.  Weeks may have passed between
> writing these statements, not to talk about changes.
>
> Okay?  Keep this image in mind - this is the context that we are working for
> here in this course, in this topic area.

Alternatively, one may ask one of the students with still raised hand how they
come to this bold estimation, so that they can share some of their previous
experience.

## Context<a name="context"></a>

### Background

As widely observed in the literature, one challenge of teaching requirements engineering is that many of the concepts taught do not connect well to the previous experience of undergraduate students.  The observations reported in the literature match my experience in teaching.  In particular with the topic area requirements engineering, there are times where it feels like there is a "glass wall" separating the lecturer and the audience.  There are points in time during our lectures where we look into many "empty stares" (not of the tired, sleepy, strained type but of the being-puzzled and being-thinking type) and we sense "thought bubbles" above heads reading: "What on earth is this all good for?",  "How can this be so complicated?", "Who would be so stupid to write a requirements document with _contradictions_ in it?" Even at points in time where the answers have principally just been given.

We conjecture that this (reproducible) effect is related to an observation also found in [[4]](#ref3).  Namely, that the first and second year of undergraduate studies may consist of programming courses (with tasks that can be solved, colloquially put, in an afternoon), small projects without much need for proper requirements documents, and lectures with exercises.  So in most cases, requirements occurring in the context of the study plan are small, and are written by _domain experts_ who know exactly what they want and who know how to specify as precisely as possible, e.g., in order to ease grading and marking. Hence in the early years of their studies, a majority of students does not develop a conception for the reality of requirements engineering; which includes large documents, which includes (constantly changing teams of) multiple persons working on the documents, which includes requirements projects that take weeks or months.

Rather than just reading out survey results and _telling_ the fact that requirements documents can grow large (as another fact in a long list of other facts), we were looking for an educational instrument that is more effective towards creating a common conception of requirements engineering reality.

### Where and When
* We use this activity in lectures on the topic area requirements
      engineering in an undergraduate introduction to software engineering.
* We usually offer the activity after having completed an overview over
      requirements engineering vocabulary and desirable properties of
      requirements documents (we would expect that there is too little common
      ground when moving the activity to a position even earlier).
* In our course, the activity marks the transition from the overview and
      basic vocabulary to the in-depth discussion of, e.g., requirements
      elicitation techniques and (formal) requirements description languages.
      That is, the activity is scheduled before those parts of the course
      which could be quite frustrating without at least a rough idea of the
      industrial practice. 
* In the lecture, we do from time to time refer back to the experience of
      the activity, e.g., to emphasise the motivation for certain techniques.
* We also refer to the experience of the activity in tutorial sessions
      after students have worked on just one short sentence as an example
      requirement so to allow students to adjust their understanding of the
      effort it may take to create requirements documents in praxis.
      
### Previous Knowledge
The activity does not assume any previous knowledge of participants
      (see above); that's the point.  The activity aims at providing shared
      knowledge that is then "previous" for everybody during the rest of the
      course.

### Other Applications
* Reporting a suggestion by a reviewer, we can imagine other connections
      that can be drawn to the experience of the activity.
      For example, an exercise consisting of a study and assessment of
      concrete requirements documents from industrial context (if available)
      for common quality properties or proportions of different kinds of
      content.
* Another example could be a requirements engineering project where
      participants could estimate how many pages their requirements document
      would have in order to, e.g., estimate effort, and later compare
      estimations with results.

## Experience<a name="prior"></a>

### Number of Uses

* The activity has been used for two or three years now, after a
      conversation with an industry contact about teaching challenges where I
      realised that the figures did not surprise me, and that I may have been
      going over this aspect too quickly in previous seasons.
* In the two or three years before, our course did not include the
      activity and we have the impression.

### Engagement and Effect

* In our experience, there are very few students who do not participate: We see almost all hands raised for the first offered number, and nobody is forced to participate. Hence there does not seem to be a strong resentment towards this activity.
* From the years without this activity, we know that the point in time
      of apparent confusion has always occurred. 
      As the results of the activity (how many students estimate which number)
      are quite stable over the previous years, we conjecture that one reason
      is the misconception that requirements documents are small and
      manageable in general, or that some students simply do not bring any
      preconception at all.
* With this activity, we observe reproducible effects: Many "empty gazes"
      (see above) go away (some maybe just because of the, very welcome,
      loosened up lecture procedure), and some students seem to take a second
      to accept the thought "Yes, that would be a massive document, I did not
      expect that."
      
### Changes

The activity has not changed in our context, yet one may vary the concrete example based on new input from practitioners.

### Risks

* We like this activity for its low risk: We anticipate a low risk for
      misunderstandings, that is, to make misconceptions worse, and in the
      worst case (that, e.g., nobody likes to participate) we only lose a few
      minutes of lecture time.
* We also see a low risk of exposing individual students because
      everybody has the possibility to rethink their estimation according 
      to the number of still raised hands one sees in the audience. 
      Asking each student for the one number of pages that would be his or her
      estimation would include the risk of exposition.
* We would recommend to use an example with a confirmed number of pages
      from an industry contact, at best a contact that could be reached on the
      phone in case students insist on verifying the claim.

## Future Work<a name="future"></a>

Unfortunately, we did not record the numbers of raised hands for each offered
estimation (partly because counting raised hands would break the flow of the
activity) and can only recall from memory that the proportions and final
numbers of raised hands do not deviate much between different years.

Investigating the concrete figures and possibly interviewing some students on
a voluntary basis would be helpful to extend the set of known, typical
misconceptions and subjective theories that are held by students during
different phases of their studies.  And then develop and evaluate activities
that address these misconceptions.


## References<a name="references"></a>

1. <a name="ref0"></a>Bernd Westphal: <a href="https://doi.org/10.1109/REET.2018.00006">An Undergraduate Requirements
   Engineering Curriculum with Formal Methods</a>, REET@RE, 2018, pages 1-10.
2. <a name="ref1"></a>Thomas Stelzer-Rothe, Ed.: Kompetenzen in der Hochschullehre, 2005, Merkur.
3. <a name="ref2"></a>Kathleen Cotton: School improvement research series, 1988, ioe-rdnetwork.com.
4. <a name="ref3"></a>Klaas Sikkel, Maya Daneva: <a href="https://doi.org/10.1109/REET.2011.6046270">Getting the client into the loop in information
   system modelling courses</a>, REET, 2011, pages 1-4.

## License

![Creative Commons BY License logo](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

