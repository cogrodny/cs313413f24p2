TestIterator:
  1. LinkedList seems to not make a difference in the code and all tests pass as they did with ArrayList
  2. list.remove(Integer.valueOf(77)) completely broke my code and seems to delete the list entirely or somehting to that degree

TestList:
  1. LinkedList seems to not make a difference in the code and all tests pass as they did with ArrayList

TestPerformance:
  1. SIZE 10 = 675ms, SIZE 100 = 715ms, SIZE 1000 = 1s, SIZE 10000 = 5s, SIZE 100000 = 1m 16s
  2. decreasing REPS makes run time shorter while increasing has opposite affect
