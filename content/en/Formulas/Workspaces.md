---
title: Workspaces
weight: 44
description: >-
  In this section, you will find how to use workspaces.
---

---

## What is the difference between workspace and repository?

Repositories and workspaces are used to interact with formulas on Ritchie, but the way they work is different, check out:

**`workspace`** You can use workspace commands to develop, edit and test formulas `locally`.

**`repository`** You can use repository commands to import formulas from `Git repositories` and execute them.

*See an example to add a repository on the [**Hello World Formula**](/docs-ritchie/formulas/hello-world-formula/) section.*

Commands for repos and workspaces are similar, they allow the CLI to "see" available formulas on your local machine. Workspaces have **higher priority** than Repos, for example, if you use both commands for the same formulas' repositories, the workspaces' formulas will be executed.

Check out more about workspace and repositories commands [**in the list of commands and flags**](/docs-ritchie/reference/list-of-commands-and-flags/).

## How to add?

To add a workspace, you just have to run this command:

```text
rit add workspace
```

After that, follow the next steps:

**Step 1:** Inform the workspace name (don't use *spaces* or *special characters*).

**Step 2:** Inform the workspace path on the local machine.

![](/shared/rit-add-workspace.gif)

## How to list?

To list avalaible workspaces, you just have to run this command:

```text
rit list workspace
```

![](/shared/rit-list-workspace.gif)

## How to delete?

To delete a workspace, run the command below:

```text
rit delete workspace
```

After that, follow the next steps:

**Step 1:** Select the workspace name;

**Step 2:** Confirm you want to delete the workspace.

![](/shared/rit-delete-workspace.gif)

## Next Steps

In this section, you saw how to use workspaces on Ritchie. Now

👉 Check out all the available formulas on Ritchie in the [**list of commands and flags**](/docs-ritchie/reference/list-of-commands-and-flags/)