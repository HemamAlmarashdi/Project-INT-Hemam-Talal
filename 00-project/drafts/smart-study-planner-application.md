---
name: Hemam Almarashdi
neptun: WOFUKB
id: null
---
# Smart Study Planner with Progress Analytics

> Draft only — not a valid course application. No published brief has been supplied or verified for this topic. The `id` is deliberately unset and must be replaced with the official brief ID, and the content aligned with that brief, before submission. Independent ideas require the course's TDK exception and staff approval. This draft is kept outside `00-project/application/` to avoid presenting it as a submission.

## My interpretation of the brief
Pending confirmation against an official brief, the proposed project is a browser-based study planner that helps students organise courses, assignments, and study sessions in one place. Students would record deadlines, estimated effort, and weekly availability, then receive a suggested study schedule and track their progress. A dashboard would show upcoming deadlines, completed tasks, and planned versus logged study time. The client would provide the planning interface, while the backend would store each student's courses, tasks, sessions, and progress securely.

## Why I am a good fit for this project
As the applicant, I would approach this project through a practical student workflow: identifying upcoming work, dividing it into manageable sessions, and reviewing progress. Its bounded scope would provide an opportunity to demonstrate interface design, scheduling logic, backend development, and database integration. I would keep the first version focused on a complete, testable workflow rather than a large collection of features.

## Relevant experience and background
My GitHub repository has been set up to hold the project documentation and future implementation. Specific coursework, programming languages, and previous projects still need to be confirmed before this section is submitted; no unverified technical experience is claimed in this draft. The project would require skills in web development, relational data modelling, automated testing, and version control, with any gaps addressed through small prototypes during planning.

## Proposed approach
I would begin by defining the task and study-session models and testing an explainable, rule-based scheduling algorithm independently of the interface. The algorithm would prioritise deadlines, use the student's estimated remaining effort, and allocate sessions within declared availability. It would flag insufficient time instead of silently scheduling overlapping sessions or promising an impossible plan. Students would be able to accept or adjust suggestions.

Subject to the official brief and course requirements, an initial technical proposal is TypeScript with SvelteKit for the interface and backend routes, Prisma for data access, and PostgreSQL for persistence. The first complete version would support an individual account, course and task management, schedule suggestions, manual session logging, and a progress dashboard. Backend authorisation would restrict records to their owner. External calendar integration, collaboration, AI-generated advice, and predictions of academic performance would be outside the initial scope.

## Initial plan
1. Semester 1: Confirm the published brief or obtain the required exception approval, agree the scope, and identify the target users and key user journeys.
2. Semester 1: Prepare the project outline, functional specification, initial technical proposal, data model, and measurable acceptance criteria.
3. Semester 1: Investigate scheduling risks through a small prototype and prepare both mandatory PRMD presentations using the course templates.
4. Semester 2: Implement account access, course and task management, and persistence, with automated tests for validation and record ownership.
5. Semester 2: Add scheduling suggestions, session logging, and progress analytics; test deadline ordering, overlapping availability, insufficient capacity, and calculation accuracy.
6. Semester 3: Evaluate usability with consenting participants, analyse the results and limitations, refine the application, and complete the thesis documentation and final presentation.

## Additional information
I would maintain the documentation and source code in the project repository, make meaningful commits, and track work in Trello as required by the course workflow. Evaluation would cover scheduling correctness, successful completion of core user journeys, and user feedback; study-time statistics would not be treated as evidence of improved grades.

Before submission, this draft requires an eligible official brief and ID, confirmation of my relevant experience, and a check of the complete repository-workflow and evaluation rules. The final application belongs in `00-project/application/`, using any filename convention specified by the course. After assignment, the accepted application and the outline, specification, and two presentation documents would be maintained in `00-project/` according to the course instructions.
