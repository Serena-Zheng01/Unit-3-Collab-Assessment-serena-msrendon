# Short Response Questions

1. **If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step? Hint: After this step each team member would have diverged from the main branch!**

When collaborating with classmates, each classmate would make their own seperate branch and when naming the branch to put their name at the end of the branch name so other classmates would know who is working on what.

---

2. **Why do developers use branches?**

Developers use branches when collaborating with other developers so when they make changes to their branch it doesnt affect main and their team members can check their work before pushing it to main.

---

3. **What is git? What is github? How does git and github work together?**

Git is a distributed version control system that allows developer to track and manage their code and changes to their code. GitHub is a friendlier version of git it makes git easier to use even for novice coders. They work together by allowing developers to code and collaborate easier, and tracking and managing change to their code.

---

4. **What is wrong with the following command sequence? What should be the correct command sequence?**

```
git commit -m "saving work"
git add .
git push
```
When saving your work your supposed to do `git add . ` first instead of `git commit -m "saving work"`. The correct command sequence would be...

```
git add . 
git commit -m "saving work"
git push
```