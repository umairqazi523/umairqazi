# umairqazi

```flow
st=>start: Start
op1=>operation: Understands the Design
cond=>condition: All good?
para=>parallel: Discussions with Client/Designer
op2=>operation: Implement code in Required Stack
op3=>operation: Submit to Client/PM
condRevisions=>condition: Bug Free?
para2=>parallel: Do Revsions
e=>end: End

st->op1->cond
cond(no)->para(path1, top)->op1
cond(yes)->op2->op3->condRevisions
condRevisions(no)->para2(path1, top)->op3
condRevisions(yes)->e
```
