# Initial page

```mermaid
  graph TD;
      no_session-->maintain;
      maintain-->no_session;
      no_session-->ready ;
      ready-->open ;
      open-->suspend
      suspend-->open
      open-->close
      close-->void
      close-->un-settled
      settled-->close
      un-settled-->settled 
```
