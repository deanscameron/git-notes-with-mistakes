---
title: Git Notes
---

Introduction
============

These notes constitute a brief summary of the `git` version control tool.


Activating Git
==============

To turn on the version control system, use:

``` bash
mkdir my_work_folder
cd my_work_folder
git init
```

Tell Git about a new file
======================

```
vim my_file # Edit file
git add my_file
```

Include changes in a file into the next commit
==============================================

```
git add my_file
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the next commit.

Include all scheduled changes into a commit
===============================================

```
git commit -m "Journal entry"
```

Store all scheduled changes in a commit
==========================================

```
git add --update
```

Include all changes *and* commit them
====================================

```
git commit -am "Journal entry"
```

View list of recent commits
==========================

```
git log
```

Transmit commit to remote Repository
====================================

```
git push
```

Fetch commit from remote Repository
===================================

```
git pull
```
