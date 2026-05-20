# Complete Python 3 Bootcamp

# CRITICAL RULES - MUST FOLLOW

## RESPONSES

- Keep responses concise and to the point - unless the user asks otherwise

## PLANNING MODE

- Always ask clarifying questions
- Never assume design, tech stack or features
- Use deep-dive sub-agents to assist with research
- Use deep-dive sub-agents to review the different aspects of your plan before presenting to the user

## CHANGE / EDIT MODE

- Never implement features yourself when possible - use sub-agents!
- Identify changes from the plan that can be implemented in parallel, and use sub-agents to implement the features efficiently
- When using sub-agents to implement features, act as a coordinator only
- Use the best model for the task - premium models for complex tasks (like coding) and mid-tier models for simpler tasks, like documentation
- After completing features (large or small), always run commands like lint, type check and next build to check code quality

**Course companion repo** for the Udemy course by Pierian Data Inc. Not a Python package — purely educational Jupyter Notebooks and supporting scripts.

## Structure

- **Sections `00`–`19`**: each is a numbered directory with Jupyter Notebooks (`.ipynb`) as primary content.
- Assessment notebooks follow the pattern `* Assessment Test.ipynb` with a corresponding `* Assessment Test-Solution.ipynb`.
- Supporting `.py` scripts live inside section directories (e.g., `06-Modules and Packages/`, `07-Errors and Exception Handling/`).
- Section `09-Empty-Section-Skip` is **not empty** — it covers Map/Reduce/Filter/etc.

## Quirks

- **No `.gitignore`** — `.ipynb_checkpoints` directories **are tracked** in git. Don't add them to `.gitignore` or delete them unless you mean to.
- No build system, no package manager, no CI, no linting/formatter config, no test framework. The only "test" files are `test_cap.py` in section 07 (used for in-notebook demonstrations).
- Notebooks target Python 3 (kernel `python3`). The repo metadata shows Python 3.6.2.

## Working with the repo

- No install, setup, or test commands to run. Open any notebook with `jupyter notebook <path>` or `jupyter lab`.
- `.py` files are standalone scripts that accompany specific notebooks — don't move them between sections.
- Some notebooks reference local files (e.g., `test.txt` in section 00, PDFs in section 15, images in section 14). Keep relative paths intact.
