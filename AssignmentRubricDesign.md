# A Path to Assignment Design

## Assignment Plan
Questions to ask yourself before you start designing the assignment. (Answer if you can, and save these answers for later!)

- What course/module learning outcomes should this assignment support?
- What degree of support structure and material is provided to the students to ease the barriers to learning? 
- What other assignments/assessments are in progress during the time this assignment active?
- How much time does a student have available to work on this assignment? Remember students should only have to dedicate 12 hours/week to the class, which includes learning the material and engaging in other content.
- Who will review/test this assignment before deployment?
- Is this assignment formative or summative? 
  - Do I need to assist the students in learning and reinforcing concepts? (Formative)
  - Do I need to evaluate students on what they’ve already learned? (Summative)

#### Formative Assessments
The purpose of formative assessment is to aid the student in the learning process. These can be short or long, but generally should be low-stakes, while maintaining the standard of work quality. These can take the form of short coding exercises, reflections, low-point-value quizzes with multiple attempts, etc.  The emphasis on this assignment is not gauging the students’ knowledge, but on helping them learn and helping them understand how they learn better.
- What module learning outcomes does this assignment help the student learn?   
You may want to refer back to your module learning outcomes regarding…
  - Why these key questions are important?
  - What are some use cases for the topics related to the key questions?
  - What impractical (but fun!) uses do these skills have?
- What areas of knowledge are prerequisite to those key questions?
  - Are skills Introduced, reinforced, or is mastery assessed?
  - Have these been adequately reinforced? 
  - Do students commonly struggle with any of these areas?
  - What additional resources might you provide to address these gaps?
- When students encounter areas of need for additional learning, what are their next steps?
- What modules/topics/lectures will assist the student when they’re working towards these outcomes?
- What active learning techniques lend themselves to use in these topics?

#### Summative Assessments
The purpose of a summative assessment is to gauge the students’ accrued knowledge.  These can take the form of exams, observed programming, submitted projects and reports. The emphasis should not be on helping the student to learn, but determining whether each student has met the module learning outcomes.
- From the students’ perspective: “What would I be able to do if I have met module learning outcome X?”
- What module learning outcomes do I need to evaluate the students on?
- Is this a comprehensive assessment over multiple weeks’ learning outcomes, or a specific targeted assessment?
- If targeted, are there any ways you can reduce the contribution of previous’ modules’ outcomes, as long as they don’t bear directly on those you’re looking at?
- What metrics can I use to determine if the students have demonstrated their understanding of the module learning outcomes? 
- What technologies lend themselves to analysis (possibly partially automated) of these learning outcomes?

## Brainstorm Assignment Ideas
Once you have answered these questions, you should be starting to have a very high-level view of **what you want from this assignment,** and (for Formative) **what you want the students to get out of it**.  Now for a big jump...

#### Formative
Looking back at what learning outcomes you want to help the students achieve in this assignment, brainstorm (preferably with someone else) some ideas on interesting activities that will give students low-stakes opportunities to practice those outcomes in a way that is engaging as well as informative.  

#### Summative
Looking back at what learning outcomes you want to evaluate in this assignment, brainstorm (preferably with someone else) on how to test those specific areas of knowledge, preferably with as little dependence on other learning outcomes as possible.

## Sketch the Assignment

Working from here to actual assignment implementation is a major hurdle, so we’ll break this up into pieces. As a note, it’s very important to not lose track of the learning outcomes.

Just because an assignment is fun, doesn’t necessarily mean it does what we want it to do.  I’d highly suggest reviewing your answers to the initial questions in this document and selecting one assignment idea to move forward from here. Don’t worry about filling them in in detail at this point - an assignment sketch is all you’ll need for now. So take your brainstormed idea, write out the outcomes, and sketch out in general terms what an implementation might look like.  Once you’re done… once you have the concept in general terms on paper and in your head, set it physically aside (and don’t peek at it) and move on to the next step below.

## Work out a Grading Criteria Sheet
Unsurprisingly, one key to good assignment design is ensuring you’re actually awarding grades based on what you want the students to learn (or to have learned already, in the case of summative assessments). You’ve already determined what module outcomes you’re addressing, so the next step is to draw up a grading criteria sheet.  A grading criteria sheet is to a rubric as a tadpole is to a frog - sort of an infant-stage in the development. In this you’ll tie in objectives in the assignment to learning outcomes.  Good labels for these fields are “developing, meeting, exceeding”. An partial example might look like the table below. The “Exceeding” column will likely be empty for many of your rows, but it’s a good place to slot in potential extra credit.


##### Outcome: Use tools to clean and transform datasets for use in database systems

| Criteria | Developing | Meeting | Exceeding | 
| ----- | ----- | ----- | ----- |
|Data converted to CSV or TSV | CSV or TSV formatted, but errors handling quotes/commas in fields or NULL fields. | CSV formatted, no errors due to quotes/commas NULL fields | Meets Criteria, and also supports extended character sets (e.g. Unicode) |
| Data loads into R, SQL, or MatPlot | Data loaded into tool, but incomplete | Data fully loaded into tool and evidence provided | N/A |

These may or may not be assignment specific, but don’t worry about that now, you can fix it later. The reason we’re filling in the rubric before the assignment is to give us a framework in the actual assignment design. Keep going until you have a complete grading criteria sheet. This is the first real design step, so take your time.  A good grading criteria sheet will address all the desired outcomes in detail, and explain specifically how the student is learning or demonstrating them. Ideally, it’ll also fit with the assignment you’d had in mind as well!  Remember, good rubrics take time to design upfront, but they save time and headaches, and eliminate student complaints, in the long run.

## Fill in the Assignment
Now that you have a thorough Grading Criteria, go back and look at your Assignment Sketch.  Is it possible to use this assignment when grading the criteria in your sheet? Is one of your other assignment ideas a better match?  Now is a great time to go back and modify (or re-create) your assignment sketch to make sure the targeted learning outcomes (as detailed in the grading rubric) are being properly addressed.  Once you have good alignment among your Grading Criteria, Assignment Sketch, and target Learning Outcomes, it’s time to fill in the assignment page. For a look at formatting, you might take a look at a CS Assignment Template draft [HERE](https://beav.es/ZgS "CS Assignment Template Draft"). It’s great to include a statement of purpose in the introduction which explains to the students why they’re being asked to complete this assignment, and what they’ll get out of it (other than a grade).

It’s likely you already have some idea of what form it will take, but what may not be obvious is what supplied materials will be necessary for the students to complete the assignment.  If you can link assignment sections to former learning outcomes (In Assignment N you learned X, now let’s apply it to System Y like this…) that’s even better.  As you fill in the assignment in more detail, make sure that the grading criteria is fairly implicit - that’ll make the actual rubric much easier to write in the next step.  It’s difficult to go into great detail in this document due to the widely varying nature of possible assignments, but remember you’re not alone in this design - you’ll have co-instructors or TA’s looking at these soon!


## Test & Fix the Assignment
Designing in a bubble is a great way to write a fantastic assignment with tons of cool aspects that end up imploding as soon as it makes contact with a student.  The purpose of this step is to catch as many of the issues with your assignment as you can **before** that happens. If you’re writing this assignment as part of a course redesign, you should have at least one assigned assistant who can help test out the assignment. Alternatively,you can snag one of your TA’s for this duty. The key here is to have someone actually complete the assignment using only your completed assignment materials and grading criteria.  This will help uncover missing information, misleading prompts, rubric items that don’t match the assignment documentation, etc..  Assignments need to be bug-tested too!

While completing the assignment, have them document their progress.  Once they’re done, they can submit this documentation to you, along with the assignment, so you can see what they may have misinterpreted, and where you need to add or remove information.  You should use this to really polish the assignment before it ever gets to the student!


## Finalize the Rubric  
At this point you should have a polished assignment document and a moderately tuned grading criteria.  At this point you want to take that criteria and mold it into a final rubric.  Point allocations should follow fairly easily from your Developing/Meeting/Exceeding specifications, but you may need to add additional line-items if your grading criteria sections are a bit more broad than the assignment specifications (our students love to nitpick).  You should also add additional points (or add point-deduction-only items) for partial credit, late penalties, style requirements, or other assignment requirements such as type of submission and source citation.
