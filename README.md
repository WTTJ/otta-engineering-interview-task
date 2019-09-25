# Otta - Engineering Interview Task

This is the take-home interview task for engineering job applications at Otta.

The goal is to both give you a flavour of the kind of work we do, and give us an idea of your technical (and non-technical) skills.

We expect the task to take approximately one hour. If it takes much longer or you require clarification on anything, please don't hesitate to contact us.

## Instructions

Start by forking this repository using your personal GitHub account ([here's how](https://help.github.com/en/articles/fork-a-repo)). All work should be completed on the fork, which is what you will submit - we'll only consider the `master` branch.

The following details the individual tasks. Please complete **all** of the them. You may use any programming language, provided all of the code used can be committed to this repo.

### Task 1

In the `data` folder of this repo there is a CSV file called `reactions.csv`. It contains real data corresponding to how users on Otta have reacted to (saved or discarded) jobs on the platform.

The reaction data consists of four columns:

- `user_id` - the integer ID of the user who liked or disliked the job
- `job_id` - the integer ID of the job the user liked
- `direction` - whether the user liked (`true`) or disliked (`false`) the job
- `time` - the timestamp corresponding to when they reacted to the job

**Task**: Find the pair of users with the highest number of jobs that they both like.

**Answer**: [Enter the two user IDs & the number of jobs they both like here]

### Task 2

In the `data` folder there is an additional CSV file called `jobs.csv`. It contains unique integer IDs for over 12,000 jobs, along with integer IDs for the job's associated company.

**Task**: Using both the `reactions.csv` and `jobs.csv` data, find the two companies which share the highest number of users who have liked at least one the company's jobs.

**Answer**: [Enter the two company IDs & the number of users who like them both here]

### Task 3

Engineering at Otta is truly full-stack. Features are owned end-to-end, from backend and database-level work to front-end finishes. As a result, we like to see evidence of your experience at both ends of the spectrum.

We know your time is precious and don't think it's fair to ask you to build something with a UI on top of the previous tasks. Instead, we'd love to see an example of something you've already built and hear about what you learned building it.

**Task**: Share an example of something you've built using front-end web technologies.

- A link to a GitHub repo is ideal.
- If the best example of your work is something you've done at a company, it's okay to link to a live deployed version
- If you can't link to anything, a screenshot is also fine

**Answer**: [Add a link to repo/website/screenshot here]

**Task**: Tell us about the biggest challenge you faced in building the above.

**Answer**: [Write your answer here (300 words max)]

## Submission

Once you've completed all of the above tasks, make sure:

- [ ] You've committed all of the code used, and your edited answers, to the `master` branch
- [ ] You've pushed the changes to your fork
- [ ] You send a link to the forked repo in an email to us

Good luck!
