
# User Collections
 - https://www.google.com/search?q=collection+users+firebase&rlz=1C1GCEU_pt-BRBR1015BR1015&oq=collection+users+firebase&aqs=chrome..69i57.2488j0j1&sourceid=chrome&ie=UTF-8#kpvalbx=_zjUOY6iaGfr01sQPnIawuAE_33
 - https://firebase.google.com/docs/firestore/data-model
 - https://stackoverflow.com/questions/50086515/firebase-document-for-each-user

# Prevent duplicate entries
 - https://stackoverflow.com/questions/54236388/prevent-duplicate-entries-in-firestore-rules-not-working

# Chat
## Not necessarily in firestore. But I'm looking to learn more about data modeling and best practicies.
 - https://www.youtube.com/watch?v=Qwk5oIAkgnY
 - https://levelup.gitconnected.com/structure-firestore-firebase-for-scalable-chat-app-939c7a6cd0f5
 - https://ngengesenior.medium.com/database-structure-of-one-to-one-chat-app-with-firebase-93f813184dfe
 - https://blog.logrocket.com/how-to-build-chat-application-flutter-firebase/
 - https://www.youtube.com/watch?v=aKYfq-VPnMA&list=PLD46K4dpufBEMDz5UblupcWLUiS2hFBXI&index=6
 - https://www.youtube.com/watch?v=LKAXg2drQJQ

# Data modeling NoSQL (Five useful data modeling techniques)
 - https://www.youtube.com/watch?v=35RlydUf6xo

# Increment
 - https://fireship.io/snippets/firestore-increment-tips/#:~:text=Increment%20is%20a%20special%20value,1%20to%20the%20current%20total.


----

# Security rules

  - https://medium.com/firebase-developers/how-to-build-a-team-based-user-management-system-with-firebase-6a9a6e5c740d
    - Rules with teams. Very interesting!
  - https://www.youtube.com/watch?v=7lFgcHvOfbo
    - Using real time database. But the principles applies to Firestore.
  - https://stackoverflow.com/questions/62215187/firestore-security-rule-for-fieldvalue-increment
    - Based on increment
  - https://stackoverflow.com/questions/56487578/how-do-i-implement-a-write-rate-limit-in-cloud-firestore-security-rules
    - Security Rules based on timestamp (To avoid read/write in less than X minutes)

## Unit testing Security Rules with Emulator Suite
  - Using Mocha (https://mochajs.org/#hooks)
    - Mocha is a JS test framework running on Node.js and in the browser.
    
  - https://firebase.blog/posts/2021/01/code-review-security-rules

  - https://firebase.google.com/docs/firestore/security/test-rules-emulator
    - Documentation

  - https://www.youtube.com/watch?v=VDulvfBpzZE
    - Todd Kerpelman explaining Unit testing Security Rules with Emulator Suite

  - https://medium.com/firebase-developers/run-continuous-integration-tests-using-the-firebase-emulator-suite-9090cefefd69
    - CI tests using Travis CI

  - https://www.youtube.com/watch?v=VgQwlMtxbAw

  - https://medium.com/firebase-developers/develop-your-firestore-with-tdd-unit-testing-security-rules-afefb0d772c4


----

# Batch writes

 - https://stackoverflow.com/questions/60600591/firebase-cloud-functions-update-a-different-object-within-onupdate-cloud-trigg
 - Batch writes optimization with Cloud Functions
   - https://medium.com/@michael.kimpton/batch-processing-with-firebase-cloud-functions-aa11640cc9ac
   - https://www.youtube.com/watch?v=_X7Ry8Q0wbg&ab_channel=thecloudfunction
   - https://dev.to/wceolin/cannot-modify-a-writebatch-that-has-been-committed-265f



