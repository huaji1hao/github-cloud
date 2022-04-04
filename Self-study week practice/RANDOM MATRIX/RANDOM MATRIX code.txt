M=rand(100);
P=ceil(100*M);
Q=floor(100*M);
pn=sum(sum(P<50));
qn=sum(sum(Q<50));
sprintf('There are %d and %d numbers less than 50 in P and Q',pn,qn)