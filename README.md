# LaTex
HomeWork For Computational Theory 2017
using a package theroy.mp to draw and create nodes-- Thanks to Russ.

EX1;
\begin{emp}(0,0)
  node.q0("q0"); q0.c = origin;
  node.q1("q1"); q1.c = q0.c + (u,0);
  node.q2("q2"); q2.c = q0.c + (2u,0);
  node.q3("q3"); q3.c = q0.c + (3u,0);
    makestart(q0);
  makefinal(q3);

  % draw the nodes
  drawboxed(q0,q1,q2,q3);
\end{emp}
