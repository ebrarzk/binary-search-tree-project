# binary-search-tree-project
7             7 → Kök (root)


  7
  
 /           5 → 5 < 7 → sola

5


   7
  /
 5            1 → 1 < 7 → sola, 1 < 5 → sola
/
1


   7
  / \
 5   8      8 → 8 > 7 → sağa



     7
    / \
   5   8
  /          3 → 3 < 7 → sola, 3 < 5 → sola, 3 > 1 → sağa
 1
  \
   3



      7
    / \
   5   8     6 → 6 < 7 → sola, 6 > 5 → sağa
  / \
 1   6
  \
   3


     7
    / \
   5   8
  / \              
  / \            0 → 0 < 7 → sola, 0 < 5 → sola, 0 < 1 → sola
 1   6
 / \
0   3


     7
    / \
   5   8
  / \    \
 1   6    9      9 → 9 > 7 → sağa, 9 > 8 → sağa
 / \
0   3



     7
    / \
   5   8
  / \    \
 1   6    9      4 → 4 < 7 → sola, 4 < 5 → sola, 4 > 1 → sağa, 4 > 3 → sağa
 / \
0   3
      \
       4


     7
    / \
   5   8
  / \    \
 1   6    9
 / \                     2 → 2 < 7 → sola, 2 < 5 → sola, 2 > 1 → sağa, 2 < 3 → sola


0   3
    / \
   2   4
