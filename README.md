# android-tests
# The ActivityResult API has just been released, so these two files are just a comparision of how stuff works.
## The code gets an image file and shows it in an ImageView.
## MainActivity1
 Uses the old school approach.
Overriding `onActivityResult`, checking `requestCode`, getting `data` and all those..
## MainActivity2
 Uses the new ActivityResult API to ease the task.
 
 ***
 Don't forget to add the implimentation to your app level gradle file.  
  `implementation 'androidx.activity:activity:1.2.0-alpha02'
   implementation 'androidx.fragment:fragment:1.3.0-alpha05'`
