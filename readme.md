Stack:

Next Greater Element
 Start Traversing from end of the array and find the observation from it.
  
  Pseudo Code:
  
   while(s.top()<=cur)
   {
   s.pop();
   }
   cout<<s.top();
   s.push(cur)
