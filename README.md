# XU-Ran_MSc-in-Biomedical-Data-Science_NTU
1 Operations for the right sum
a: 
m = 9;
n = 9;
a = [repmat([1], 1, n); repmat([2], 1, n); repmat([3], 1, n); repmat([4], 1, n); repmat([5], 1, n); repmat([6], 1, n); repmat([7], 1, n); repmat([8], 1, n); repmat([9], 1, n)];
sum_65 = sum(a(1:6), a(2,6), a(3,6), a(4,6), a(5,6), a(6,6), a(7,6),a(8,6:end));
sum_72 = sum(a(1:5), a(2,5), a(3,5), a(4,5), a(5,5), a(6,5), a(7,5),a(8,5:end));
disp(sum_65);
disp(sum_72)
