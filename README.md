# Blearn
Blearn is a mastery learning tool.  It's named for Benjamin Bloom, who proposed it in 1968.

Mastery Learning is an educational technique where each student achieves mastery of content before moving on to new content.  In traditional education, a class spends a pre-determined amount of time on each topic.  Slower students learn less and faster students get bored.  In mastery learning, each student learns at their own pace.  Slower and faster students learn the same content to the same level of understanding, but the faster students move through the content faster.

Blearn will
1. Display educational content
2. Administer and score quizzes
3. Use spaced repetition to help students maintain knowledge
4. Track student progress
5. Help student understand pre-requisite concepts before advancing to new content

Proposed artifacts
1. A set of educational content for learning a particular topic
   A. Grouped into modules with a cool badge icon for each module
   B. High-quality readings of text and diagrams
2. A data format for the content
3. Software for students to use to learn the modules
4. A data format for the student's usage of the content, without PII.
5. Software to help instructors monitor student progress and decide how to allocate their time among students and activities
6. Software to help content maintainers to identify student misunderstandings of content, group and prioritize them, and then update the content to eliminate misunderstandings
7. Case studies of usage

# Educational Content
1. Topic
   A. All content is divided into topics
   B. A topic takes 10-30 minutes to learn
      i. With short topics, students frequently finish topics and experience positive emotions of success and accomplishment. 
      ii. These positive emotions improve learning.
   C. Each topic has a name and number.
   D. Each topic has an icon.
   E. Each topic has a list of pre-requisite topics.  The graph of pre-requisites is acyclic.
   F. Content is mostly text, diagrams, and photos
   G. Content may contain short animations and short videos.  These videos do not contain narration.
   H. Diagrams, photos, animations, and videos have detailed text explanations for the visually-impaired.
   I. Content may contain high-quality recordings of readings of text.
   J. All content uses simple language where possible.
   K. When an academic word is used, the word's topic is listed as a pre-requisite.
   L. Versions of content do not target different levels of understanding.  To teach a deeper understanding of a topic, create another topic.
   N. Each topic has a hidden list of concepts.
      i. Each concept has a number and a description.
      ii. A student must master every concept to pass the topic.
   M. Each topic has a set of quiz questions
      i. Each question has correct and incorrect answers
      ii. Each incorrect answer has a link to the place in the content that explains the correct answer.
      i. Each question is tagged with the concepts it checks.
      ii. Some questions are "exercises" and include multiple concepts.
      iii. When a student exhausts the questions on a topic, they are referred to the instructor.
   P. There may be multiple versions of the content, explaining it in different ways.
   Q. Every question version and content version have distinct ID numbers.  These numbers are unique for all historical versions of the topic.  This allows us to see how performance changes as we modify questions.
2. Module
   A. A module is a group of topics
   B. Each module has a name and number.
   C. Each module has a cool badge icon and physical paper sticker design.
   D. Each module has a list of pre-requisite modules.  The graph of pre-requisites is acyclic.
   E. Each module has an overview topic that explains what the module is about and why it is important to learn.

TODO: Make some words for:
1. This topic requiring another topic.
2. Another topic requiring this topic.
3. The list of topics that require this topic.
4. The list of topics required by this topic.

# Links
1. https://en.wikipedia.org/wiki/Mastery_learning
2. https://nintil.com/bloom-sigma/

# License
TODO: Pick a license that requires content and code to be freely available for use under the same license, like the Apache license and GNU Public License.
