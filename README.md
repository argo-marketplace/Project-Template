# Dirt simple ARGO marketplace project spec:
v0.1 Nov 4 2017

*Copy this spec to start a new argo-marketplace project*

# Define Roles
- `SEEKERS`: Usually a public institution that is seeking tech talent to address a need or solve a problem.
- `SOLVERS`: Technologists who mostly agree with a [Manifesto for public technology](civichall.org/civicist/manifesto-for-public-technology/). SOLVERs can individuals or groups.
- `ARGO`: A non-profit organization that shepherds the ARGO marketplace. Contact argo@argolabs.org if questions.
---
# Define Scope and Purpose 

- **Why are we doing this project? What specific problem are we addressing?**
	- *Describe the problem in a few sentences.*
	- *Specify short and long-term needs that provide context for this problem.*
- **What questions will this project help answer?**
	- *Ex: Which streets are worse that others in the city?* OR *Which utilities are achieveing their conservation targets?*
- **What is this ?** 
	- *Analysis - `SEEKER` have most data readily available and want to find meaningful insights through robust analysis and viz.*
	- *Integration - `SEEKER` needs to acquire data from multiple sources and create a sustainable/automated pipeline*
	- *Discovery - `SEEKER` needs to figure out a way to measure, generate/collect data using low-cost methods (may include surveys, scrapers & sensors).
- **Duration of Project**
	- *Estimated project completion time.*
- **Resources.**
	- *Links to news articles or research papers to help a potential `SOLVER` or a google doc providing extended explanations.*
- **Possible methods and tools to use**
	- *Have you tried any methods previously? Did they succeed, fail?*
	- *Improvements to existing methods?*
	- *A list of tools that can be used*
- **Solution details**
	- *What does a completed solution look like?*
	- *If applicable, how does this solution scale-up up to cover a citywide strategy.*
---
# Define Process
## Project init.
1. A `SEEKER` fills out the `Add Project Form`(**TBD Add Project form template**) to add a Project to the marketplace's `CLEARINGHOUSE spreadsheet`.
2. `ARGO` reviews the new form entry and if all good, creates new repo on argo-marketplace.
3. `ARGO` adds project to `CLEARINGHOUSE spreadsheet` for `SOLVERs` to view.
4. `SOLVERs` need to register by filling a `SOLVER FORM`(**TBD Solver form template**) before being granted access to `CLEARINGHOUSE spreadsheet`. 
	- Registration includes reviewing and committing to `SOLVER Guidelines`.
5. Once registered, `SOLVERs` will be granted access to a tab on the `CLEARINGHOUSE spreadsheet` to enter their github-username against a project-id.

## Project exec.
1. `ARGO` and `SEEKERS` will collaborate to update the repo with content that is deemed useful to SOLVERs.
2. A project can be grabbed by many SOLVERs.
3. When a `SOLVER` needs to ask a question, they open a [new issue](https://github.com/argo-marketplace/test-project/issues) and label it appropriately. It is highly recommended that `SEEKERs` commit to answering questions and close issues in a timely manner.
4. `SEEKERs` may also open issues and leave it open to serve as a FAQ.
5. `SOLVERS` are encouraged to fork project repos to work on a project. 
6. `SOLVERS` create pull requests once they have prepared a solution that is fully executable and readable as per `SOLVER Guidelines`

## SOLVER Guidelines
1. Once a SOLVER grabs a project, they must commit a `project update` (**TBD PROJECT UPDATE template**) every 2-weeks. A SOLVER who does not provide timely updates will be removed from the CLEARINGHOUSE spreadsheet and de-registered. They will need to re-register using the `SOLVER FORM`.

2. Solutions are submitted using Pull requests (**TBD PULL request template**). A solution needs to be fully executable by the SEEKER. SOLVERs are expected to provide clear instructions on how a SEEKER can execute the solution. SOLVERs cannot expect SEEKERs to re-create solution environments (Ex: install Python 3 on your computer). The SOLVER must deploy their fully working solution for the SEEKER to review.

---
# Suggested repo folders
- `Data`
	- *Contains datasets provided by SEEKERS to help SOLVERS*

- `Research/Literature`
	- *A place to upload research papers, news articles or additional literature review to help SOLVERS better understand the scope of the problem and provide as much context as possible. This should ideally be maintained by SEEKERS but SOLVERS may also contribute.*

- `Source`
	- *This is a place for both SOLVERS and SEEKERS. This folder or sub-folder(s) can contain **readable & executable code**, Tableau workbooks etc.

