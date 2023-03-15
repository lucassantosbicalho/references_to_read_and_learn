Firebase Cloud Functions

---

# Error deploying functions
After run the command `firebase deploy --only functions` I got the error in the final log:
```
i  functions: cleaning up build files...
!  functions: Unhandled error cleaning up build images. This could result in a small monthly bill if not corrected. You can attempt to delete these images by redeploying or you can delete them manually at https://console.cloud.google.com/artifacts/docker/<project-name>/southamerica-east1/gcf-artifacts

+  Deploy complete!
```
The solutions is to redeploy. Take a look at this stack overflow:
 - https://stackoverflow.com/questions/68611817/cant-deploy-cloud-functions-because-of-unhandled-error-cleaning-up-build-image


# RESTFull APIs to Firestore

 - https://www.youtube.com/watch?v=LCGqOjO7Zc8
 - https://www.youtube.com/watch?v=bs_xs9-RJvc
 - https://www.youtube.com/watch?v=uAZye3L2NPo
 - https://www.youtube.com/watch?v=ny55KMSX-aY
 - https://www.youtube.com/watch?v=T8SZv6h2WbY
 - https://www.youtube.com/watch?v=mWAwxbeGU_E
   - For RealTime DB

# Sending e-mail via functions
 - https://edigleyssonsilva.medium.com/cloud-functions-for-firebase-sending-e-mail-1f2631d1022e
 - https://softauthor.com/firebase-functions-send-email/
 - https://medium.com/android-news/firebase-functions-send-email-using-google-oauth2-20c552da6b3e
   - Setup configuration

# Triggers on Firestore

 - https://www.youtube.com/watch?v=WrzvBulgBi0
 - https://www.youtube.com/watch?v=QTq4KJG5quU

# Schedule (Job)

 - https://www.freecodecamp.org/news/how-to-schedule-a-task-with-firebase-cloud-functions/

# Deleting old messages in chat (Firestore)

 - https://stackoverflow.com/questions/15990681/firebase-chat-removing-old-messages
 - https://stackoverflow.com/questions/18851549/deleting-old-messages-in-firebase-based-on-time-and-number-of-entries
 - https://medium.com/@fabio.sabbion/firestore-auto-delete-a-document-after-24-hours-91db9d0132a0

# FCM via Cloud Functions

 - https://engineering.monstar-lab.com/en/post/2021/02/09/Use-Firebase-Cloudfunctions-To-Send-Push-Notifications/
   - By HTTP request or Triggers 
 - https://www.youtube.com/watch?v=I0r10sk5fuI&ab_channel=TadasPetra

# Regions in functions 
 - https://firebase.google.com/docs/functions/locations
   - Regions locations supported	
 - https://firebase.google.com/docs/functions/locations
   - Firebase documentation on Cloud Functions locations 
 - https://firebase.google.com/docs/functions/manage-functions#modify-region
   - Modifying the region of a deployed function.
 
