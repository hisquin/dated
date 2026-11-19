

# Links:
- https://www.figma.com/design/cKjCtg0uyF88RZMCbPmIPv/Dashboards-Constructor-7.6-Promo?node-id=15027-61271&p=f&t=OENGfZ0bvSz2ZIV2-0
- 
- https://www.figma.com/community/file/1284617779490261600/quizwiz
- https://www.figma.com/community/file/1037306397959773962/quiz-game
- https://www.figma.com/community/file/834159367507466339/virtual-quiz-template
- https://www.figma.com/community/file/1145433435196546360/neubrutalist-quiz-app-by-loidgi
- https://www.figma.com/community/file/1384735320358247227/quiz-web-application
- https://www.figma.com/community/file/1401229554049192726/quiz-miniapp
- https://www.figma.com/community/file/1414332288171686410/quiz-app-ui-design
- https://www.figma.com/community/file/1445338174140577091/wireframes-for-interactive-quiz-v-1-0
- https://www.figma.com/community/file/968710196159658963/quizzing-website-hompegae
- https://www.figma.com/community/file/1284617779490261600/quizwiz


:::
```
# DOGOMA

# DOGOMA — PRODUCT ENHANCEMENT & FUTURE DEVELOPMENT ROADMAP

## 1. Purpose

This document outlines additional product features and improvements proposed for Dogoma.

Dogoma should grow beyond a conventional trivia application into an engaging knowledge and learning platform.

The product should create three connected experiences:

1. **PLAY** — Test knowledge, answer questions and compete.
2. **LEARN** — Discover new information and develop knowledge.
3. **IMPROVE** — Track progress, strengthen weak areas and become better.

The objective is to encourage users to return regularly, develop their knowledge and enjoy a meaningful experience.

These requirements should be considered alongside the existing Dogoma product briefs and implementation roadmap.

---

# 2. GAMEPLAY IMPROVEMENTS

## 2.1 Daily Challenge

Introduce a Daily Challenge feature.

Requirements:

- Provide a new daily quiz.
- Make the same daily challenge available to all players.
- Allow guests and registered players to participate.
- Display the date and daily challenge status.
- Show the player's results after completion.
- Allow players to compare their performance with other eligible participants.
- Track participation history for registered players.
- Prevent duplicate official entries where applicable.
- Provide a clear indication when the daily challenge has already been completed.

The Daily Challenge should encourage users to return every day.

## 2.2 Custom Quiz

Allow players to create their own quiz experience.

Players should be able to select:

- Category.
- Subcategory or topic, where available.
- Difficulty.
- Number of questions.
- Timer or untimed practice mode.
- Available question formats, where appropriate.

Requirements:

- Generate quizzes using the existing question bank.
- Avoid unnecessary repetition within a single quiz.
- Respect the selected difficulty and category.
- Display a clear summary before the quiz starts.
- Preserve existing scoring and session rules.
- Provide a useful empty state when insufficient questions are available.

## 2.3 Streaks and Achievements

Introduce a non-monetary achievement system.

Possible achievements include:

- Daily participation streak.
- Perfect quiz completion.
- Consecutive correct answers.
- First completed quiz.
- Improvement in accuracy.
- Mastery of a particular category.
- Completion of difficult quizzes.
- Consistent learning activity.

Requirements:

- Achievements must have clear criteria.
- Award achievements only when criteria are genuinely met.
- Prevent duplicate achievement awards.
- Show earned achievements on the player profile.
- Keep achievement progress where possible.
- Do not introduce paid rewards, subscriptions or monetization.

Streak calculations should respect the player's timezone.

---

## 2.4 Challenge a Friend

Introduce a social quiz challenge feature in a later development phase.

Requirements:

- Allow a player to generate a shareable challenge link.
- The link should open the relevant Dogoma challenge.
- Friends should be able to participate without mandatory registration.
- Allow participants to compare their results.
- Preserve fair scoring rules.
- Prevent manipulation of official results.
- Provide a useful experience when a challenge link has expired or is invalid.

This feature should be designed for simple sharing through messaging applications and social platforms.

---

# 3. LEARNING EXPERIENCE IMPROVEMENTS

Dogoma must offer a meaningful learning experience beyond answering quiz questions.

The Learning section should help users understand topics, discover information and improve their knowledge.

## 3.1 Explanations and Learning References

Preserve explanations and source information in the question content model.

Requirements:

- Keep gameplay feedback short and distraction-free.
- Allow explanations to be accessed after a quiz.
- Make sources available in question review.
- Provide links to relevant learning materials where available.
- Avoid displaying unverified explanations or sources.

Explanations should support learning without interrupting the quiz experience.

## 3.2 Explore a Topic

Allow players to explore topics related to their quiz performance.

Examples:

- A player struggling with Rwandan history can explore Rwandan history materials.
- A player performing poorly in geography can explore geography lessons.
- A player interested in African culture can explore relevant learning content.

Requirements:

- Connect quiz categories and subcategories to learning topics.
- Recommend relevant materials based on actual performance.
- Make recommendations understandable and useful.
- Avoid recommending unavailable content.
- Provide an honest empty state when no relevant learning material exists.

## 3.3 Saved Knowledge and Bookmarks

Allow registered players to save useful learning materials.

Requirements:

- Bookmark learning articles and modules.
- View saved materials in the player profile or Learning section.
- Remove bookmarks.
- Preserve bookmarks across sessions.
- Prepare for future account synchronization.

Guest bookmarking may use local browser storage where appropriate.

## 3.4 Knowledge of the Day

Introduce a featured daily knowledge experience.

Content may include:

- Interesting facts.
- Today in History.
- Historical discoveries.
- Geography.
- Science and technology.
- African history.
- African culture.
- World history.
- Educational tips.

Requirements:

- Display one or more featured items.
- Include credible sources.
- Display dates where relevant.
- Allow players to explore related learning materials.
- Link to relevant quizzes where possible.
- Avoid fabricated facts or unsupported historical claims.
- Support content management through the future admin dashboard.

## 3.5 Continue Learning

Allow players to resume learning materials they previously started.

Requirements:

- Save learning progress.
- Track completed modules.
- Remember the last accessed learning material.
- Display progress clearly.
- Recommend the next relevant learning activity.

---

# 4. COMPETITION AND PLAYER ENGAGEMENT

## 4.1 Multiple Leaderboard Views

Expand the leaderboard experience.

Proposed views:

- All-time leaderboard.
- Weekly leaderboard.
- Monthly leaderboard.
- Category-specific leaderboard.

Requirements:

- Display player rankings clearly.
- Show relevant points and performance information.
- Allow users to find their own ranking.
- Distinguish official verified rankings from local or demonstration scores.
- Exclude unverified scores from official rankings.
- Avoid duplicate score submissions.
- Ensure ranking calculations are consistent.

The leaderboard should remain accessible to guests, but only eligible registered players should contribute to official rankings.

## 4.2 Personal Best Scores

Track a player's best performance.

Possible metrics:

- Highest quiz score.
- Best accuracy.
- Most consecutive correct answers.
- Best category performance.
- Fastest completed quiz, where speed is relevant.
- Highest difficulty successfully completed.

Display personal records on the profile and relevant results screens.

## 4.3 Accuracy and Improvement Rankings

Do not make competition depend exclusively on total points.

Consider:

- Accuracy percentage.
- Improvement over time.
- Category mastery.
- Difficulty performance.
- Consistency.

Ensure that rankings are calculated fairly and that players cannot gain unfair advantages by repeatedly submitting incomplete or unusually short sessions.

## 4.4 Category Achievements

Recognize players who develop strong knowledge in specific categories.

Examples:

- Rwanda History Explorer.
- Geography Expert.
- African Culture Enthusiast.
- Science Explorer.
- History Master.

Achievements must be based on measurable performance rather than arbitrary labels.

---

# 5. TRUST, CONTENT QUALITY AND USER EXPERIENCE

These features are important for maintaining Dogoma's credibility as a knowledge platform.

## 5.1 Report a Question

Allow players to report questions they believe are incorrect, confusing or inappropriate.

Possible report reasons:

- Incorrect answer.
- Incorrect explanation.
- Unclear wording.
- Duplicate question.
- Incorrect source.
- Outdated information.
- Other content issue.

Requirements:

- Provide a simple reporting interaction.
- Allow optional additional comments.
- Prevent repeated accidental submissions.
- Store reports for future administrative review.
- Provide feedback after a report is submitted.

Do not automatically change or remove a question because one player reports it.

## 5.2 Question Review and Approval

Create a content review workflow for administrators.

Possible statuses:

- Draft.
- Published.
- Reported.
- Under review.
- Needs correction.
- Archived.

Requirements:

- Administrators can inspect reported questions.
- Corrections should preserve the original question history where appropriate.
- Changes should be traceable.
- Questions should be reviewed before publication.
- Only authorized administrators should publish or modify official content.

## 5.3 Duplicate Detection

Introduce duplicate-question detection.

Requirements:

- Detect identical question IDs.
- Detect identical or highly similar question text.
- Identify repeated questions across categories.
- Warn administrators before importing duplicates.
- Avoid removing legitimate variations automatically.

## 5.4 Content Verification

Every published question should meet content-quality standards.

Requirements:

- Correct answer.
- Clear question wording.
- Appropriate difficulty.
- Correct category and subcategory.
- Explanation where appropriate.
- Credible source references.
- Correct spelling and grammar.
- Relevant country or regional scope.
- Appropriate question format.

Historical and statistical questions should include relevant dates or reference periods.

## 5.5 Difficulty Balancing

Ensure that quiz difficulty is meaningful.

Requirements:

- Maintain a consistent difficulty classification.
- Avoid unexpectedly difficult quizzes when players select easy difficulty.
- Monitor question performance.
- Identify questions that are too easy, too difficult or frequently misunderstood.
- Use actual player performance data to inform future adjustments.

## 5.6 Search

Introduce search across Dogoma.

Search should eventually support:

- Categories.
- Topics.
- Learning materials.
- Daily Knowledge content.
- Relevant questions, where appropriate.

Provide useful empty states and clear search results.

## 5.7 Privacy and Account Controls

When accounts are introduced, provide:

- Account information.
- Profile management.
- Notification preferences.
- Data and privacy settings.
- Account deletion request.
- Clear information about stored player data.

Respect user consent and applicable privacy requirements.

---

# 6. ADMIN DASHBOARD AND CONTENT MANAGEMENT

The admin experience should eventually provide proper management of Dogoma's knowledge content and player activity.

## 6.1 Question Management

Administrators should be able to:

- Create questions.
- Edit questions.
- Delete or archive questions.
- Preview questions.
- Assign categories and subcategories.
- Assign difficulty.
- Manage question formats.
- Add explanations.
- Add source references.
- Set country and regional scope.
- Publish and unpublish questions.

## 6.2 Bulk JSON Question Import

This is particularly important because Dogoma will use large question banks.

Allow administrators to import question files in the supported Dogoma JSON structure.

Before importing, validate:

- JSON syntax.
- Required fields.
- Unique question IDs.
- Supported question types.
- Correct answer structure.
- Valid categories and subcategories.
- Valid difficulty values.
- Country and scope consistency.
- Explanation and source fields.
- Duplicate questions.
- Unsupported or malformed records.

The system should provide an import preview.

Show:

- Total records detected.
- Valid records.
- Invalid records.
- Duplicate records.
- Records requiring correction.
- Detailed error messages.

Allow administrators to correct or exclude invalid records before import.

Imported questions should enter a draft or review state unless an authorized administrator explicitly approves publication.

Do not automatically publish an entire imported question bank without validation and review.

## 6.3 Question Performance Analytics

Provide administrators with useful question-level analytics.

Possible metrics:

- Number of times a question was presented.
- Correct-answer rate.
- Incorrect-answer rate.
- Unanswered rate.
- Average response time.
- Performance by difficulty.
- Report frequency.

Use this information to improve question quality.

## 6.4 Report Management

Administrators should be able to:

- View reported questions.
- Filter reports by status.
- Review player comments.
- Investigate content issues.
- Correct questions.
- Archive inappropriate or inaccurate questions.
- Mark reports as resolved.

## 6.5 Category Management

Allow administrators to:

- Create categories.
- Edit categories.
- Create subcategories.
- Organize topics.
- Manage category visibility.
- Connect learning materials to categories.

## 6.6 Learning Content Management

Administrators should eventually manage:

- Learning subjects.
- Topics.
- Articles.
- Modules.
- Learning resources.
- Publication status.
- Sources and references.
- Related quiz categories.

## 6.7 Daily Knowledge Management

Allow administrators to:

- Create daily knowledge content.
- Schedule publication.
- Edit content.
- Add sources.
- Set publication dates.
- Archive outdated items.
- Preview content before publication.

## 6.8 Player and Engagement Analytics

Provide an administrative overview of:

- Registered players.
- Guest activity where measurable.
- Quiz participation.
- Daily active players.
- Completed quizzes.
- Average accuracy.
- Popular categories.
- Learning engagement.
- Daily Challenge participation.
- Retention and return activity.

Do not display fabricated metrics or treat unavailable backend data as real.

---

# 7. PRODUCT EXPERIENCE AND NAVIGATION

Dogoma should remain simple and intuitive.

## 7.1 Core Product Destinations

The main player experience should be organized around:

1. Home.
2. Game.
3. Learn.
4. Leaderboard.
5. Profile.

Daily Knowledge and Daily Challenge should be easy to discover without overcrowding navigation.

## 7.2 Mobile Experience

More than 60% of expected users are anticipated to use phones.

The mobile experience should feel like a native installed application.

Priorities:

- Simplified bottom navigation.
- Comfortable touch targets.
- Clear gameplay.
- Minimal distractions.
- Proper safe-area spacing.
- Smooth and meaningful transitions.
- Fast loading.
- Clear feedback.
- Easy access to installation.
- Appropriate offline functionality.

## 7.3 Desktop Experience

Desktop should be intentionally designed rather than simply using a stretched mobile layout.

Priorities:

- Broader layouts.
- Appropriate sidebar navigation.
- Better use of screen space.
- Clear analytics presentation.
- Comfortable quiz interaction.
- Desktop QR code encouraging mobile access.

## 7.4 Visual Identity

Preserve Dogoma's established visual identity.

Avoid:

- Unnecessary gradients.
- Too many accent colours.
- Excessive decorative cards.
- Generic AI-generated interface patterns.
- Unnecessary animations.
- Visual complexity that does not improve usability.

Design decisions should serve functionality and clarity.

---

# 8. DEVELOPMENT PRIORITIES

These enhancements should be implemented progressively.

## Phase 1 — Core Application Stability

Priorities:

- Stable gameplay.
- Reliable scoring.
- Correct timers.
- Session recovery.
- Results analytics.
- PWA installation.
- Mobile-first experience.
- Desktop experience.
- Offline functionality.
- Custom Quiz.
- Daily Challenge foundations.

## Phase 2 — Player Engagement

Priorities:

- Achievements.
- Streaks.
- Personal bests.
- Weekly and monthly rankings.
- Daily Knowledge.
- Improved player profile.
- Performance history.

## Phase 3 — Learning Ecosystem

Priorities:

- Structured learning.
- Topic exploration.
- Learning recommendations.
- Bookmarks.
- Learning progress.
- Continue Learning.
- Connections between quizzes and learning materials.

## Phase 4 — Administration and Content Operations

Priorities:

- Admin dashboard.
- Question management.
- Bulk JSON import.
- Question validation.
- Duplicate detection.
- Content approval.
- Report management.
- Learning content management.
- Daily Knowledge management.
- Administrative analytics.

## Phase 5 — Backend and Official Player Accounts

After the local-data experience is stable:

- Supabase integration.
- Registration and login.
- Guest-to-account migration.
- Cross-device progress.
- Server-verified scores.
- Official leaderboards.
- Protected admin access.
- Achievement synchronization.
- Notification preferences.
- Push notification infrastructure.

## Phase 6 — Social Competition and Expansion

Later possibilities:

- Challenge a Friend.
- Shareable quiz challenges.
- Advanced competition formats.
- More social engagement features.

---

# 9. IMPORTANT PRODUCT AND TECHNICAL CONSTRAINTS

All future implementation must respect these decisions:

1. Dogoma is completely free.
2. No subscriptions.
3. No premium plans.
4. No payment features.
5. Guest play must remain available without mandatory registration.
6. Registration should provide additional value, not block gameplay.
7. Dogoma launches as a web application with a strong PWA-first approach.
8. Mobile is the primary experience, but desktop must remain fully supported.
9. Mobile and desktop experiences should be intentionally different.
10. Existing local JSON and browser storage functionality must continue working.
11. Supabase integration must be handled as a separate development phase.
12. Do not fabricate learning content, Daily Knowledge content, statistics or player metrics.
13. Do not present local or unverified scores as official rankings.
14. Preserve existing working functionality.
15. Avoid unnecessary rewrites and complexity.
16. Protect player data and administrative operations.
17. Do not claim a feature is complete until it has been implemented and tested.

---

# 10. FINAL PRODUCT VISION

Dogoma should become a knowledge platform that gives people a reason to return, learn and improve.

Its central experience should follow this cycle:

**PLAY → DISCOVER WEAKNESSES → LEARN → IMPROVE → PLAY AGAIN**

The platform should reward genuine knowledge, consistency and improvement, not merely speed.

A player should be able to:

- Play without creating an account.
- Discover new topics.
- Test their knowledge.
- Understand their performance.
- Explore areas where they need improvement.
- Learn something useful every day.
- Track personal progress.
- Compete fairly with other players.
- Develop a habit of continuous learning.

The long-term goal is not simply to build another trivia application.

**The goal is to build Dogoma into a trusted, engaging and accessible knowledge and learning platform, starting with Rwanda and extending across Africa.**
```
:::