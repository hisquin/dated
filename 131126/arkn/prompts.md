# I want to clarify an important development decision before we proceed.

**We are NOT ready for backend integration yet, and I don't want to start the Supabase + Vercel backend phase at this point.**

My preferred approach is to complete the entire Arkon School application on the frontend first, including all pages, features, workflows and user experiences. Once the frontend is complete, properly tested and approved, we will move into backend architecture and integration.

I don't want us to keep switching between frontend development and backend integration while the product itself is still being designed and expanded.

### 1. Complete the entire frontend first

We still have considerable product functionality to develop.

I want us to complete:

**Public website**
- All public-facing pages.
- Course catalogue and detailed course pages.
- Cohorts and intake pages.
- Admissions and registration.
- About, Studio, Approach and Contact.
- FAQ and other necessary information pages.

**Admissions and enrolment**
- Complete multi-step cohort registration.
- Application review and status tracking.
- Admissions workflows.
- Course enrolment.
- Cohort selection.
- Student onboarding.

**Student platform**
- Student dashboard.
- Profile and account settings.
- Course learning environment.
- Video, audio and text learning experiences.
- Learning preferences.
- Assignments and submissions.
- Grades and feedback.
- Notifications.
- Learning progress.

**Teacher platform**
- Teacher dashboard.
- Course and curriculum management.
- Module and lesson creation.
- Multiple lesson content formats.
- Assignment management.
- Submission review.
- Grading and feedback.
- Cohort management.
- Student progress views.

**Administrator platform**
- Administrative dashboard.
- User management.
- Course management.
- Cohort and intake management.
- Admissions management.
- Enrolment management.
- Reports.
- Settings and other administrative workflows.

**Collaborative learning environment**

We also need to design and implement the frontend experience for our future interactive classroom.

This includes:
- Live classroom interface.
- Video and audio controls.
- Participant management.
- Classroom chat.
- Collaborative design canvas.
- Instructor annotation and student participation.
- Browser-based coding workspace.
- Project workspaces.
- Classroom resources and collaboration interfaces.

We don't need actual real-time infrastructure or production-grade collaborative execution yet. However, the interfaces, interactions and user workflows should be developed and tested.

### 2. Make the frontend backend-ready

Although we are postponing backend integration, I don't want the frontend architecture to become a limitation later.

Please:
- Use structured mock data.
- Separate UI components from data operations.
- Create reusable service interfaces.
- Establish consistent data models.
- Avoid scattering hardcoded sample data throughout components.
- Keep the architecture ready for future API integration.
- Design all role-based workflows with future permissions in mind.

The objective is to replace mock data with real backend services later without having to rebuild the entire frontend.

### 3. Complete the actual user experiences

I don't want pages that simply exist visually.

Every feature should have meaningful interactions, including:
- Create, edit, view and delete where applicable.
- Search and filtering.
- Navigation.
- Form validation.
- Confirmation and error states.
- Loading and empty states.
- Role-specific experiences.
- Responsive layouts.

All major workflows should be testable using demo data.

### 4. Establish a proper frontend completion checklist

Before we declare the frontend complete, I want:
- Every planned page implemented.
- Every major workflow functional.
- All roles properly represented.
- Consistent visual identity.
- Responsive behaviour tested.
- Automated tests passing.
- No broken navigation or dead buttons.
- No misleading claims about demo functionality being real.
- All incomplete features explicitly documented.

Test at 375px, 390px, 430px, 768px and desktop.

I also want actual browser-based visual inspection, not only simulated Node interactions.

### 5. Backend integration comes afterwards

Only after the frontend is complete and approved will we move to:

- Supabase/Postgres architecture.
- Authentication.
- Database schema and migrations.
- Row-level security.
- Real application and enrolment persistence.
- File and media storage.
- Email notifications.
- Real-time collaboration.
- Live classroom infrastructure.
- Secure coding environments.
- Production deployment.

At that point, we can make the final technology decisions based on the complete product rather than prematurely committing to infrastructure.

### 6. What I want you to do now


First, assess the entire remaining frontend scope.

Create a comprehensive development roadmap covering every page, feature and workflow that still needs implementation.

Identify dependencies between features and organise the work into manageable phases.

Then proceed with frontend development phase by phase.

Do not jump into backend integration, do not treat the current published artifact as the complete application, and do not declare the product finished simply because the existing tests pass.

**Our current objective is to finish building the complete Arkon School product experience first. Backend integration is a separate development stage that begins only after frontend completion and approval.**

---
------

# I have decided to make an important adjustment to our development approach.

Instead of continuing to expand Arkon School inside a standalone Claude Artifact, I want us to transition the application into a proper, permanent development environment now.

**Here is the GitHub repository I want us to use:**

https://github.com/hisquin/arkn.git

### 1. Migrate the existing application into the GitHub repository

I don't want to lose the work we've already completed inside the Claude Artifact.

The existing implementation contains significant functionality, including:
- Public website and navigation.
- Course catalogue and course detail pages.
- Cohort management.
- Multi-step applications.
- Application review workflows.
- Student, teacher and administrator dashboards.
- Curriculum management.
- Assignments and grading.
- Demo data and existing workflow logic.

Inspect the repository first and determine its current state.

Then assess the existing Artifact source code and establish the best way to migrate its functionality into the repository.

Preserve existing functionality, business rules, visual identity and reusable components.

Do not simply recreate the application from scratch or discard existing work.

### 2. Convert the application into Next.js

I want Arkon School developed as a proper Next.js application.

My preference is:

- Next.js with App Router.
- React.
- TypeScript.
- Tailwind CSS where appropriate.
- Reusable, modular components.
- A maintainable project structure.
- Server Components by default, using Client Components where interactivity requires them.

Use an architecture that supports the full application, including public pages, student portals, teacher dashboards, administrator interfaces and eventually the interactive classroom.

Do not introduce unnecessary dependencies.

### 3. SEO, GEO and AEO are important

One of the main reasons for moving to Next.js is to establish a stronger foundation for discoverability.

I want the public-facing Arkon School website properly optimised for:

**SEO**
- Server-rendered or statically generated public pages where appropriate.
- Unique page titles and meta descriptions.
- Canonical URLs.
- XML sitemap.
- Robots.txt.
- Open Graph and social sharing metadata.
- Semantic HTML.
- Image optimisation and descriptive alt text.
- Proper heading hierarchy.
- Structured internal linking.
- Fast loading and Core Web Vitals.
- Appropriate indexing rules.

**GEO — Generative Engine Optimization**
- Clear, factual and well-structured content about Arkon School.
- Consistent organisation, programme and instructor information.
- Strong topical relevance around product design, software engineering, AI implementation and product entrepreneurship.
- Structured data that helps search engines and AI systems understand our organisation and programmes.
- Credible, useful content rather than keyword stuffing.

**AEO — Answer Engine Optimization**
- Clearly structured answers to common admissions questions.
- Descriptive headings.
- Well-organised FAQs.
- Relevant structured data.
- Clear programme descriptions and learning outcomes.
- Content that answers prospective students' actual questions.

Implement appropriate schema markup where applicable, including Organization, EducationalOrganization, Course, BreadcrumbList and other relevant types.

Do not add structured data for information that is not actually visible or supported by the website.

Important: SEO, GEO and AEO should be built into the content architecture and page structure, not treated as a plugin added at the end.

### 4. Proper routing and indexing

Move away from the current single-page hash-based routing approach.

Use proper, clean URLs.

Examples:

- `/`
- `/courses`
- `/courses/product-design`
- `/courses/product-development`
- `/cohorts`
- `/about`
- `/studio`
- `/approach`
- `/contact`
- `/apply`

Student, teacher and administrator environments should have appropriate protected application routes.

Public pages should be indexable where appropriate.

Private dashboards, applications, account pages and internal administrative pages should not be indexed.

### 5. Preserve the existing brand identity

Do not redesign Arkon School.

Maintain the established Studio Atelier identity:

- Warm paper backgrounds.
- Dark ink typography.
- Fraunces display font.
- Instrument Sans.
- Signature hand-drawn vermilion redline critique mark.
- Editorial layouts.
- Thoughtful whitespace.
- Responsive and accessible interfaces.

Avoid generic AI-generated SaaS designs, excessive gradients, unnecessary cards and decorative UI.

The objective is to improve the underlying application architecture without losing its existing visual character.

### 6. Backend integration is still postponed

Although we are moving to Next.js and GitHub now, this does NOT mean we are beginning backend integration.

Our development priority remains completing the entire frontend first.

Continue using structured mock data and appropriate demo services until the frontend is complete.

Keep the architecture backend-ready so we can later integrate Supabase, authentication, database persistence, storage, email and real-time services without rebuilding the application.

Do not introduce fake production functionality.

Clearly distinguish working prototypes from features requiring future backend infrastructure.

### 7. Important: inspect before making changes

Before implementation:

1. Inspect the GitHub repository.
2. Inspect the current Artifact source code.
3. Determine whether the repository already contains an application or is empty.
4. Identify which existing features can be migrated directly.
5. Identify what needs adaptation for Next.js.
6. Establish the migration plan.
7. Identify dependencies, technical risks and missing functionality.

If you cannot directly access or modify the GitHub repository from the current environment, tell me clearly what access or development environment is required. Do not pretend that changes have been committed or pushed.

Do not overwrite existing repository content without inspecting it and establishing a safe migration strategy.

### 8. Development and delivery

Once the migration plan is established, proceed with the conversion.

Use GitHub as the permanent source of truth.

Maintain clean commits and a clear development history.

Ensure the application can eventually be deployed through Vercel.

After migration, verify:
- Existing routes.
- Existing workflows.
- Responsive layouts.
- Form functionality.
- Role-specific interfaces.
- SEO metadata.
- Sitemap and robots configuration.
- Build and type-check results.
- Automated tests.

Do not claim visual verification unless you have actually inspected the rendered application in a browser.

### FINAL DIRECTION

We are transitioning Arkon School from a standalone Claude Artifact into a proper Next.js application maintained in our GitHub repository.

We are doing this now to establish the correct technical foundation before implementing the remaining product features.

**The immediate objective is: migrate, convert to Next.js, preserve existing functionality and establish a strong SEO/GEO/AEO foundation.**

After that, continue completing the remaining frontend features.

Backend integration remains a separate future phase, beginning only after the complete frontend has been implemented, tested and approved.

---
---

# 3 

---
