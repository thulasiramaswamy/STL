// C++ Program to Demonstrate Queue using Standard Template Libraries(STL)
// Basic Operations of a Queue

// The functions supported by queue are :

// empty() – Returns whether the queue is empty.
// size() – Returns the size of the queue.
// queue::swap() in C++ STL: Exchange the contents of two queues but the queues must be of same type, although sizes may differ.
// queue::emplace() in C++ STL: Insert a new element into the queue container, the new element is added to the end of the queue.
// queue::front() and queue::back() in C++ STL– front() function returns a reference to the first element of the queue. back() function returns a reference to the last element of the queue.
// push(g) and pop() – push() function adds the element ‘g’ at the end of the queue. pop() function deletes the first element of the queue.

#include <iostream>
#include <queue>
using namespace std;

int main(void)
{
 queue<int> q, q1;
 q.push(10);
 q.push(20);
 q.push(30);
 q.push(40);

 q1.push(40);
 q1.push(30);
 q1.push(20);
 q1.push(10);

 cout << "\n Before Swap, Queue Elements - ";
 while(!q.empty())
 {
   cout << " " << q.front();
   q.pop();
 }
 q.swap(q1);
 cout << "\n After Swap, Queue Elements - ";
 while(!q.empty())
 {
   cout << " " << q.front();
   q.pop();
 }
 return 0;
}
