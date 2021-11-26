# My Mechanicsville Memories - Devlog 3
## Week 10 - November 26, 2021

### What was I trying to do
This week, my focus was on content. I was finally able to outline my story and decided to segment it into a few distinct chapters: 
1. Intro and conclusion (which I called "The Place" and "The Place Revisited")
2. The House
3. The Park
4. The Street
5. The Sidewalk

My plan was that each part shares a small snapshot of my memories and feelings towards Mechanicsville in conversation with the oral history interviews I had already recorded with my parents. I wanted to vary the chapters by using different temporal frameworks (ex. starting with the present then going back to the past or opening with a memory and circling back to the present, etc.) and a variety of multimedia (video, photos, audio). While it was a more productive week than I expected, there were obviously some hiccups.

### Creating the chapters

I sometimes forget, scripting, recording, editing, transcribing, and uploading content can take a while. I have a fair bit of experience working with photos, video editing, and podcast making so luckily, I know my creative process and what works best for me. That said, I did spend more hours than I would like to admit fighting wih audacity to delete my own breaths or making sure a video looped juuuuuust right. While not exactly a challenge to overcome, I wanted to write this down more for future me: things. take. time. 

### Adding a volume warning

When I sent my story to someone to show them what I was working on, their ears were blasted by the first audio segment. Unfortunately, there isn't an option built into Mural that allows the viewer to play/pause audio segments so I needed to come up with a way to counteract this. 

I decided the easiest way would be to include a warning about the website's use of audio on the website's landing page. The only difficulty with this is that the Mural editor only allows you to customize the story name and background photo on the landing page. As my workaround, I relied on my pretty basic understanding of HTML to add a warning line. 

What I did was edit the index.html file once it was uploaded to my github repo. I went to the story-name line and added this underneath:
<h3 class="content-warning">This website uses audio, be concious of your volume settings before opening</h3>

### Things may be getting out of hand... 

Honestly, things were going much better than I imagined they would… That's when you should always be nervous. With two of the main chapters done, I decided I wanted to see what it would look like by putting my mural story onto github again. I had a few issues this time, the first being I forgot to upload my "uploads" folder which meant that there was no multimedia content for my story (facepalm). But I got over that hurdle once I realized it was missing and then added the folder. As I was adding the multimedia content, I got a warning code from github:
"Yowza, that’s a big file. Try again with a file smaller than 25MB."

I really hadn't put much thought into file sizes up until this point, aside from what I mentioned in my last devlog about forgoing the sliding scale of photo sizes. Unfortunately, the video file for the Street chapter is just too big for github to take. At firt I thought since the visual component of this video was looping footage of a static street, it wouldn't change much if I shift this to being an audio file over a photo like I did for the House chapter. But I was really missing the motion that a video file had and I ended up reexporting the video but compressed it.

So for next steps, I need to consider file sizes for the next two chapters. At the very least, I'm not going to be trying any video files again without significantly compressing them or uploading them to YouTube. More broadly, I need to put some more thought into how much bigger I want this story to get. Although I have outlined four chapters, maybe the story still comes across with just the two? This is what I'm going to be thinking about for the next few days.

If you want to check out the story so far, you can access it here: https://merandagp.github.io/MyMechanicsvilleMemories/