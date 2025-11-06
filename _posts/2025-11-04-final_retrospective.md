---
layout: page
title: Trimester 1 Retrospective
permalink: /tri1Retrospective/
---

<style>
.retrospective-container {
  max-width: 900px;
  margin: 0 auto;
  color: #e0e0e0;
  line-height: 1.6;
}

.section-divider {
  border-bottom: 1px solid #404040;
  margin: 40px 0 30px 0;
  padding-bottom: 10px;
}

.section-divider h2 {
  margin: 0;
  font-size: 1.8em;
  font-weight: 600;
  color: #ffffff;
}

.content-block {
  margin: 25px 0;
}

.content-block h3 {
  color: #b0b0b0;
  margin-top: 0;
  margin-bottom: 15px;
  font-size: 1.3em;
  font-weight: 500;
}

.content-block h4 {
  color: #909090;
  margin: 15px 0 10px 0;
  font-weight: 500;
}

.content-block p {
  margin: 10px 0;
}

.content-block ul, .content-block ol {
  margin: 10px 0;
  padding-left: 25px;
}

.content-block li {
  margin: 8px 0;
}

.tool-list {
  list-style: none;
  padding-left: 0;
}

.tool-list li {
  margin: 15px 0;
  padding-left: 20px;
  border-left: 2px solid #404040;
}

.tool-list strong {
  color: #c0c0c0;
}

.intro-text {
  font-size: 1.05em;
  margin: 20px 0 40px 0;
  padding: 20px 0;
  border-bottom: 1px solid #404040;
}

.feedback-item {
  margin: 20px 0;
  padding-left: 15px;
  border-left: 2px solid #505050;
}

.feedback-item blockquote {
  margin: 5px 0 10px 0;
  font-style: italic;
  color: #b0b0b0;
}

.stats-row {
  display: flex;
  gap: 30px;
  margin: 20px 0;
  flex-wrap: wrap;
}

.stat-item {
  flex: 1;
  min-width: 120px;
}

.stat-item .number {
  font-size: 2em;
  font-weight: bold;
  color: #ffffff;
  display: block;
}

.stat-item .label {
  font-size: 0.9em;
  color: #808080;
}

blockquote {
  border-left: 2px solid #505050;
  padding-left: 15px;
  margin: 15px 0;
  color: #b0b0b0;
}
</style>

<div class="retrospective-container">

<div class="intro-text">
  At the beginning of the year, I did not know any Java or how to make a Spring Boot project. Through this project, I learned how to make a full stack frontend-backend project with Java and gained hands-on experience with REST APIs and client-server communication.
</div>

<div class="section-divider">
  <h2>Skills Acquired: Three Sprint Journey</h2>
</div>

<div class="content-block">
  <h3>Development Tools</h3>
  <ul class="tool-list">
    <li><strong>VSCode:</strong> Set up my development environment and learned to work with Java extensions and integrated debugging tools</li>
    <li><strong>GitHub:</strong> Learned version control practices including commits, push/pull operations, and team collaboration through repositories</li>
    <li><strong>Spring Boot:</strong> Configured backend server architecture and learned about REST APIs, endpoints, and request/response handling</li>
    <li><strong>Postman:</strong> Used to test API endpoints during development and debug backend functionality</li>
  </ul>
</div>

<div class="content-block">
  <h3>Programming Fundamentals</h3>
  <ul class="tool-list">
    <li><strong>JavaScript:</strong> Worked extensively with JavaScript for frontend development, including DOM manipulation, event handling, and the fetch API</li>
    <li><strong>Java:</strong> Learned object-oriented programming concepts such as classes, objects, methods, and data structures</li>
    <li><strong>API Integration:</strong> Connected frontend JavaScript to Java Spring Boot backend using RESTful endpoints and handled JSON data parsing</li>
    <li><strong>Full Stack Development:</strong> Understood how frontend and backend communicate and work together in a complete application</li>
  </ul>
</div>

<div class="content-block">
  <h3>Project Management</h3>
  <p>Learned how to manage a project from start to finish, including planning features, coordinating with team members, and delivering a working product.</p>
</div>

<div class="section-divider">
  <h2>Night at the Museum</h2>
</div>

<div class="content-block">
  <h3>Overall Experience</h3>
  <p>Night at the Museum went well overall. We received 8 feedback responses from visitors who interacted with our quest-based learning platform. The presentation allowed us to showcase our full-stack Spring Boot application and explain how the frontend and backend work together.</p>
</div>

<div class="content-block">
  <img src="{{site.baseurl}}/images/natm_picture.png" alt="GitHub Commit History" style="max-width: 100%; height: auto;">
  <h3>Positive Feedback</h3>
  <div class="feedback-item">
    <blockquote>"This presentation is very interactive, hooks in the audience greatly."</blockquote>
    <p>Our gamified approach successfully engaged visitors and made learning more interactive</p>
  </div>
  
  <div class="feedback-item">
    <blockquote>"I learned a lot about API's, I also taught this lesson."</blockquote>
    <p>The module effectively explained technical concepts like REST APIs in an accessible way</p>
  </div>
  
  <div class="feedback-item">
    <blockquote>"This project was well developed and the presentation was easy to follow and understand. As a CSP student I appreciated understanding where the templates and formats we used came from."</blockquote>
    <p>This was especially meaningful because it shows we helped bridge understanding between CSP and CSA concepts</p>
  </div>
  
  <div class="feedback-item">
    <blockquote>"This lesson was very informative and helpful for my future."</blockquote>
    <p>Achieved our goal of creating educational content that has real value</p>
  </div>
</div>

<div class="content-block">
  <h3>Constructive Criticism</h3>
  
  <h4>UI/UX Issues</h4>
  <p>One visitor pointed out that the "Previous Lesson" button was positioned inside the "Next Lesson" button, making navigation confusing. This is definitely something we need to fix in future iterations.</p>
  
  <h4>Layout and Design Improvements Needed:</h4>
  <ul>
    <li>Better button placement and spacing</li>
    <li>More comprehensive UI testing before deployment</li>
    <li>Clearer visual hierarchy</li>
  </ul>
</div>

<div class="content-block">
  <h3>Key Takeaways</h3>
  <ol>
    <li>Strengths: Interactive design and educational value resonated well with visitors</li>
    <li>Improvements Needed: UI/UX design requires more attention and user testing</li>
    <li>Growth Opportunity: Learning to accept and implement constructive criticism is part of the development process</li>
  </ol>
  <p>The mixed feedback was actually valuable because it shows both what we did well and where we need to improve. For next trimester, I want to focus more on user experience design and thorough testing before presenting.</p>
</div>

<div class="section-divider">
  <h2>Future Goals</h2>
</div>

<div class="content-block">
  <h3>Project Vision</h3>
  <p>I liked this overarching idea of doing quest-based learning. In general, gamified learning seems like a good thing to do to get people engaged and motivated. I would say we should have more creativity for next trimester's project. Maybe each group could have more freedom to innovate, and we could work on something larger and more complex rather than simple modules.</p>
</div>

<div class="content-block">
  <h3>Learning Objectives for Next Trimester</h3>
  <p>More advanced Java concepts for the AP exam, including:</p>
  <ul>
    <li>Advanced object-oriented programming (inheritance, polymorphism, interfaces)</li>
    <li>Data structures (ArrayLists, 2D arrays)</li>
    <li>Algorithm development and optimization</li>
    <li>More complex problem-solving strategies</li>
  </ul>
</div>

<div class="section-divider">
  <h2>Analytics and Contributions</h2>
</div>

<div class="content-block">
  <h3>GitHub Commit History</h3>
  <img src="{{site.baseurl}}/images/commit_graph.png" alt="GitHub Commit History" style="max-width: 100%; height: auto;">
  <h3>OCS Commit Graph</h3>
  <img src="{{site.baseurl}}/images/ocs_commit_graph.png" alt="GitHub Commit History" style="max-width: 100%; height: auto;">
</div>

<div class="content-block">
  <h3>Features Implemented</h3>
  <ul>
    <li><strong>Plant Feature:</strong> Developed the plant growth system that tracks user progress</li>
    <li><strong>Progress Bar:</strong> Created a visual progress tracker to show learning completion</li>
    <li><strong>Navigation Buttons:</strong> Implemented next and previous buttons for moving between quest modules</li>
    <li><strong>Overall Layout:</strong> Contributed to the design and structure of the user interface</li>
  </ul>
</div>

<div class="content-block">
  <h3>Team Collaboration</h3>
  <p>Worked collaboratively with my team throughout the development process, contributing to both frontend and backend integration.</p>
</div>

<div class="section-divider">
  <h2>MCQ Performance Analysis</h2>
</div>

<div class="stats-row">
  <div class="stat-item">
    <span class="number">35/42</span>
    <span class="label">Score</span>
  </div>
  <div class="stat-item">
    <span class="number">83.3%</span>
    <span class="label">Accuracy</span>
  </div>
  <div class="stat-item">
    <span class="number">2:37</span>
    <span class="label">Total Time</span>
  </div>
</div>

<div class="content-block">
  <h3>Strengths</h3>
  <p>I performed well on most fundamental concepts:</p>
  <ul>
    <li><strong>Variables and Data Types (1.3-1.5):</strong> Strong understanding of assignments, arithmetic operations, and casting</li>
    <li><strong>Boolean Expressions (2.2, 2.5):</strong> Successfully worked with compound conditionals and logical operators</li>
    <li><strong>Object-Oriented Programming (3.1-3.8):</strong> Good grasp of classes, objects, methods, and the dot operator</li>
    <li><strong>Arrays and ArrayLists (4.3, 4.8):</strong> Solid performance on basic array manipulation and ArrayList operations</li>
    <li><strong>2D Arrays (4.11-4.12):</strong> Successfully analyzed nested array traversals</li>
  </ul>
</div>

<div class="content-block">
  <h3>Areas for Improvement</h3>
  <p>I missed 7 questions and need to focus on:</p>
  <ol>
    <li><strong>String Manipulation in Loops</strong> (Q15): Need more practice with substring operations combined with loop logic</li>
    <li><strong>Inheritance</strong> (Q22): Review subclass/superclass relationships and method overriding rules</li>
    <li><strong>Recursion</strong> (Q29, Q39): Strengthen understanding of recursive calls and base cases, practice tracing through recursive algorithms step-by-step</li>
    <li><strong>Nested Conditionals</strong> (Q30): Work on complex conditional logic and edge cases</li>
    <li><strong>Sorting Algorithms</strong> (Q40): Review how insertion sort works through multiple passes, practice tracing algorithms by hand</li>
  </ol>
</div>

<div class="content-block">
  <h3>Correction Approach</h3>
  <p>For each missed question, I will:</p>
  <ol>
    <li>Understand the correct answer and why my answer was wrong</li>
    <li>Trace through the code step-by-step on paper to see how values change</li>
    <li>Practice similar problems from the AP Classroom question bank</li>
    <li>Focus on time management - some questions took significantly longer (Q13: 13 min, Q31: 21 min, Q34: 52 min)</li>
  </ol>
</div>

<div class="content-block">
  <h3>Content Performance</h3>
  <img src="{{site.baseurl}}/images/content_performnce.png" alt="GitHub Commit History" style="max-width: 100%; height: auto;">
  <h3>Skill Performance Graph</h3>
  <img src="{{site.baseurl}}/images/skill_performance.png" alt="GitHub Commit History" style="max-width: 100%; height: auto;">
</div>

<div class="content-block">
  <h3>Action Plan for Next Trimester</h3>
  <ul>
    <li>Complete additional practice problems on recursion and sorting algorithms</li>
    <li>Review College Board's inheritance and polymorphism materials</li>
    <li>Time myself on practice questions to improve efficiency</li>
    <li>Work through FRQs (Free Response Questions) that involve these weak topics</li>
    <li>Use the homework assignments as study resources to reinforce concepts</li>
  </ul>
</div>

<div class="content-block">
  <h3>Homework Resources for Study</h3>
  <p>I plan to revisit these homework assignments to reinforce the concepts I struggled with on the MCQ:</p>
</div>

<div class="section-divider">
  <h2>Reflection on Teacher Feedback</h2>
</div>

<div class="content-block">
  <h3>Areas for Personal Growth</h3>
  <p>I received feedback that while I am reliable, I sometimes fade into the background and let others take the lead in group work. Looking back at last year, I was able to stand out more in my group of 6 as scrum master, where I took on more leadership responsibilities and held myself accountable.</p>
  
  <p>For next trimester, I want to approach the project with a different mindset:</p>
  <ul>
    <li>Be more proactive in taking on challenging tasks rather than waiting for assignments</li>
    <li>Speak up more during team discussions and contribute ideas actively</li>
    <li>Hold myself accountable by setting personal deadlines and meeting them consistently</li>
    <li>Take initiative in identifying problems and proposing solutions</li>
    <li>Make my contributions more visible by documenting my work and communicating progress</li>
  </ul>
  
  <p>I understand that being reliable is not enough - I need to be a visible, active contributor who drives the project forward. This trimester showed me that I have the technical skills; next trimester, I need to demonstrate leadership and accountability more consistently.</p>
</div>

</div>