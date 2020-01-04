# ideas

* loop through musical instruments
* play jingle / sfx on resulting instrument selection
* zoom in on face on result as well

# asset list

* images: guitar, bass, piano, drums, synth, xylopohne, clarinet, saxophone, trumpet, violin, cello, voice
* sounds: see above

# cheat sheet

wav to m4a conversion:

for i in *; do ffmpeg -i "$i" -c:a libfdk_aac -b:a 128k -ac 1 "${i%.*}.m4a"; done
