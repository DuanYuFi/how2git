# how2git

This repo aims to do test for myself.

## 1. rebase

Now I have two branches: main and feat-c. The comments like below:

```text
                                         main
                                          |
comment 1 -> comment 2 -> comment 3 -> comment 4
                 |
                 -> comment 5 -> comment 6 -> comment 7
                                                 |
                                                 feat-c
```

and the comments are independent. Now I am in feat-c, and I want to merge the updates from main to feat-c. I can do this by rebase.

```bash
git chekout feat-c
git rebase main
```

Then the comments will be like below:

```text
                                         main                                  feat-c
                                          |                                      |
comment 1 -> comment 2 -> comment 3 -> comment 4 -> comment 5 -> comment 6 -> comment 7
```

## 2. merge

to be continue.
