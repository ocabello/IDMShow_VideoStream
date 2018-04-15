# IDMShow_VideoStream

**Note**: Video streaming site uses sample videos stored in the following Google Drive folder: https://drive.google.com/drive/folders/1Sd2kvTDOwVnzNX6YLeNJLig3lOEPuhdB?usp=sharing

I also added a timer that will redirect to the main page after 6 minutes (in case there's no volunteer by the computer and the guest forgets to close a video after watching). To modify the timeout time in milliseconds, look for the following script in **Video_Stream.htm**:

```
<script>
    setTimeout(function(){
		window.location = "Video_Stream.htm";
		},360000);
</script>
```
