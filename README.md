# Initial page

```mermaid
  graph TD;
      no_session-->雨天維護中;
      雨天維護中-->no_session;
      no_session-->ready ;
      ready-->open ;
      open-->suspend 
      suspend-->un-settled
      un-settled-->settled 
      settled-->close 
      close-->void
      void-->un-settled
```
