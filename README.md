# baristawrite-ai
AI-powered ESP writing assessment prototype for English for Baristas.

## Project files
- [Website prototype](index.html): a browser-based writing task with rubric-guided feedback.
- [Assessment plan](docs/assessment-plan.md): source context, proposed writing objectives, task prompt, draft rubric, alignment map, and development procedure.

## Current prototype
The website presents a customer-complaint writing task about an oat-milk latte prepared with regular milk. Learners write a 60–90 word response and receive feedback indicators for:
1. Task completion
2. Organization and clarity
3. Tone and audience awareness
4. Language use

**Important:** the current feedback is rule-based and heuristic. It is not connected to a generative AI model and the score is not a validated grade. It is an initial functional prototype to demonstrate the task and feedback flow. Instructor review and pilot testing are still needed.

## Run locally
Open `index.html` in a modern web browser. No build step or package installation is required.

## Publish with GitHub Pages
1. Open the repository's **Settings**.
2. Choose **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. Wait for the deployment to finish. GitHub Pages will show the published website URL in the Pages settings.

## Next steps
- Review the objectives and rubric with the course instructor.
- Pilot the task with sample responses and revise the rubric.
- If the assignment requires generative AI, confirm the permitted model/API and implement it through a secure backend. Do not put private API keys in `index.html` or other public client-side files.
