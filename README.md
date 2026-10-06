#

#resources
#common file types according to GeeksForGeeks (+flac mkv) to use as base for sorting.
    #text
.txt .rtf .docx .csv .doc .wps .wpd .msg
    #images
.jpg .png .webp .gif .tif .bmp .eps
    #audio
.mp3 .wma .snd .wav .ra .au .aac
    #videos
.mp4 .3gp .avi .mpg .mov .wmv .flac .
    #program
.c .cpp .java .py .js .ts .cs .swift .dta .pl .sh .bat .com .exe
    #compressed
.rar .zip .hxq .arj .tar .arc .sít .gz .z
    #web
.html .htm .xhtml .asp .css .aspx .rss

#asked chatgpt for three suggestions on how to make a sorting linux bash-script. Chose an array based method as it appeared easier to amend in case I wanted to add file types. It's more lines but but feels cleaner as it's structured.

#chatgpt generated touch promts with various filetypes for testing as follows;
touch \
  report.txt notes.txt todo.txt meeting.rtf letter.rtf \
  resume.docx invoice.docx essay.docx project.docx \
  data.csv contacts.csv budget.csv \
  old.doc file.doc \
  photo.jpg photo2.jpg vacation.jpg screenshot.jpg \
  image.png logo.png diagram.png \
  picture.webp banner.webp \
  animation.gif \
  scan.tif \
  drawing.bmp \
  graphic.eps \
  song.mp3 music.mp3 podcast.mp3 \
  track.wma \
  recording.wav \
  sound.au \
  audio.aac \
  video.mp4 movie.mp4 \
  clip.avi \
  recording.mpg \
  vacation.mov \
  film.wmv \
  phone.3gp \
  movie.mkv \
  program.c \
  program.cpp \
  script.py script2.py \
  app.js \
  server.java \
  utility.sh \
  tool.exe \
  backup.zip archive.zip \
  files.rar \
  package.tar \
  data.gz \
  archive.7z \
  webpage.html \
  index.html \
  style.css \
  page.htm \
  site.aspx \
  feed.rss

#end of touch prompt

261006: tested on VM. Failed and created only other. Found I was a bit fat fingered on lines 91+92 when writing and fixed in beta ver of script. Now gonna push and try again.
