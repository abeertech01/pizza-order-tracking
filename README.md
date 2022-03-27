## Important Notes

---

### QnA

#### Q: If we are updating from cntroller, then again why should we update via socket? Couldn't we reload instead?

Ans: when we update from controller we make an update to the database. But when we update through socket we do it very temporarily.

So, controller's update is saved to database but socket's update gets destroyed when one reloads.

reload destroys socket's update and brings database's update.

---
