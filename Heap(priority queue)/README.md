Collections.reverseOrder()
Normally, Java's PriorityQueue works as a Min Heap, meaning the smallest number comes out first when you call poll().
For example, if we insert 2, 7, 4, 8:
Without reverseOrder():
PriorityQueue<Integer> pq = new PriorityQueue<>();
System.out.println(pq.poll()); // 2


With reverseOrder():
PriorityQueue<Integer> pq =
    new PriorityQueue<>(Collections.reverseOrder());

System.out.println(pq.poll()); // 8
