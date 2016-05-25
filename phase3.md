### Firebass - Phase 3

Once the time locks were disengaged on Tuesday evening (24nd May 2016), coming back to the screen we were last on (https://probassfinders.foo/walleyejournal/SILO.html) finally reveals the portal to 1997 along with a link:

<img src="screenshots/time_portal_2007.png" alt="portal 2007" width="500px"/>

Following through with the link takes us to a new section:

http://probassfinders.foo/finclub/home.html

Once again, we need to search for clues for the [sup] elements, to fill in `probassfinders.foo/[1]/[2]/[3]/[4]/[5]/index.html`

#### Clue #1 (000147)

On the bottom of the page, the first part of the link is displayed right in front of us. In the source code it also has the exact number displayed @ `<img alt="Web counter: visitor number 000147 [1]" src="../images/1997/counter.jpg" />`

<img src="screenshots/phase_3_hint_1.png" alt="sub 1" width="200px"/>

#### Clue #2 (notafish)
#### Clue #3 (MOODMUSIC)

When you click on the sound bit @ https://probassfinders.foo/finclub/featured-fish.html you see a reference to this code in your console. 
```
<script>
    console.log('TODO: Complete connection to Firebase Storage');
    var storageRef = firebase.app().storage().ref();
    var file = storageRef.child('spectrogram.wav');

    // TODO: Get download URL for file (https://developers.google.com/firebase/docs/storage/web/download-files)
</script>
```

When you follow the instructions on how to connect to the db (we generated the token in part 1) and go for the file that they tell you to connect to, you download this file: https://firebasestorage.googleapis.com/v0/b/firebass-450f9.appspot.com/o/spectrogram.wav?alt=media&token=fee520a4-19ae-4106-89fe-5ae9df6c8330

After downloading the file, `spectogram.wav` you can put it into audacity and convert it to a spectogram, it returns the following image:

<img src="screenshots/hint_3_decoded.png" alt="sub 3" width="700px"/>

#### Clue #4 (Alex)
#### Clue #5 (index)


#### The terminal

When you put all the answers together from above, you end up @ https://probassfinders.foo/000147/notafish/MOODMUSIC/Alex/FIN/index.html


#### THE END
