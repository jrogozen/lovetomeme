#MVP#
- user uploads video (sub 15 seconds)
- user sees edit screen with timeline
- user can add a text layer on top of the video at a certain position (hardcoded, subtitle)
- user saves video
- text is a node canvas image -> convert to video file
- ffmpeg overlays the text video file with the original video file
- gfycat encodes video into html5 (compressed) w/ GIF fallback
- show the gfycat url

##Sprints##

###idea 1###
- video file gets saved in our own amazon s3 account
- video url gets saved in database
- share functionality / unique webpage for each video

###idea 2###
- add templates of videos to use
- gallery view of templates
- video template has its own page. show popular videos made from that template
- store stats in database

###idea 3###
- text decoration/styling in videos


###Get Started###
- set up base node/express server
- set up react, redux, webpack
- start video edit page
  - load and display video
  - show timeline
  - clicking on a timepoint in the timeline will go to the corresponding timepoint in the video
- video file seed on server