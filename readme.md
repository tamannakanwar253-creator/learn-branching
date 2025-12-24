Level 5: Detach yo’ HEAD
 Description:
This level introduces the concept of detached HEAD.
Normally, HEAD points to a branch, but here it points directly to a commit.
![WhatsApp Image 2025-12-24 at 14 32 28_adfb98c1](https://github.com/user-attachments/assets/d6b48dff-243d-4404-8099-d90b751c0862)

 Commands Used
``` blash 
git checkout C4
```

Level 6: Relative Refs (^)
Description:

This level teaches relative references using the caret (^) operator.
It allows you to move to the parent commit of a branch or commit.
![WhatsApp Image 2025-12-24 at 14 32 39_da82299d](https://github.com/user-attachments/assets/0ca53675-168b-4529-b306-bad2058f3d44)

 Command Used:
```blash
git checkout bugFix^
```

Level 7: Relative Refs #2 (~)
 Description

This level expands on relative references using the tilde (~).
It moves multiple commits back in history and demonstrates forcing branch pointers.

![WhatsApp Image 2025-12-24 at 14 32 50_62819245](https://github.com/user-attachments/assets/add5af1a-e8d8-4fa4-9951-c14bd7611ad9)

Commands Used
```blash
git branch -f main C6
git branch -f bugFix HEAD~1
```

Level 8: Reversing Changes in Git
 Description:

This level explains how to undo changes safely using reset and revert.
It highlights the difference between local and pushed (remote) history.
![WhatsApp Image 2025-12-24 at 14 32 59_e06c7d4b](https://github.com/user-attachments/assets/f3fcc230-50df-40be-ad96-e47c0583fff2)

Commands Used
```blash
git branch -f local HEAD~1
git checkout pushed
git revert pushed
```
