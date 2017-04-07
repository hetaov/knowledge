### git导出项目 ###

---

git archive master | tar -x -C /somewhere/else

### 恢复远程提交

---

git reset --hard f414f31
git reset --soft HEAD@{1}
git commit -m "Reverting to the state of the project at f414f31
