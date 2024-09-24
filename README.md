# W7 Exercise - Identifying and Creating Task Topics

**Objective**: Identify task topic content on NCSU's Student Services website. Translate that content as task topic `.dita` XML files.

## Exercise Folder Setup

1. Create a new branch with the following naming scheme: `lastname-task-topic-exercise`.
2. Copy and paste the `COPYME` folder.
  - NOTE: Ignore the `.keep` files. They help git track "empty" folders.
3. Rename it with your lastname.
4. Add any new task topic files in your folder.

## What to Do

1. Review the following two pages from NCSU's Student Services:
  - ["Personal Information and Privacy"](https://studentservices.ncsu.edu/resources/personal-information-and-privacy/).
  - ["Student Addresses"](https://studentservices.ncsu.edu/resources/personal-information-and-privacy/student-addresses/)
2. In your respective work folder, create as many task topics as you think necessary to account for task topic content across these two pages.
3. Use the following filenaming scheme for your task topics: `t_imperativeverb_verbobject.dita`.
  - **Examples**: `t_make_latte.dita`, `t_steam_milk.dita`, or `t_prepare_beans.dita`
4. Before you start translating the task topic content, feel free to copy an paste the content from the skeleton file for task topics in the root of this repo: `t_scary_skeleton.dita`.

## Identifying existing task content

Tasks often include the following information (Bellamy et al., p. 220):

- Numbered lists
- Describes how to do something
- Verb-based titles or headings. Yet, do not rely on this guideline solely, because sometimes conceptual and reference genres fit this characteristic sometimes, e.g., "Understanding cat behavior."

## Review of Guidelines for Writing Task Topics

Know the difference between different kinds of content and always be sure that the element you use to wrap the content is the right element.

### Write one task per topic

Think in terms of smaller topic files with procedures broken down into component sections that are potentially small enough to be reused.

- For example, instead of appending related tasks to an already long topic, make them stand on their own.
- Use organization and reltable linking in order to connect related topics.
- Recognize the difference between "processes" and "procedures" as they differ primarily in terms of breadth.

### Create tasks and subtasks to organize long procedures

Even tasks that may seem like they are all one coherent task should be broken up into smaller topical units. This may not be the case in this assignment, but it is always good to consider the following questions to mitigate this issue:

- Is the task topic over 10 steps long? Reconsider and put in smaller task topics.
- Feel like you want to include a new step section and restart the numbering? You really need a new task topic.

**Example**: Identifying manageable topics for a user goal like "Managing your Zotero Library" when using a citation manager like Zotero:

- Managing your Library  (too big! break it down into topics)
  - Library (concept)
  - Building your library (process)
  - Adding an item  (task)
  - Item Types (reference)
  - Book (concept)
  - Organizing your library (process)
  - Collections (concept)
  - Adding a collection (task)