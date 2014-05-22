code
====

jm
%author: jackson makale
%matlab version:
% sum of multiple of 3 or 5



n = 1;
sum =0;


    for n=1:999;
 while (mod(n,3)==0 || mod(n,5)==0);
    sum = sum + n;
    break;
    
 end
    end
    
    
fprintf ('sum %d\n',sum);
