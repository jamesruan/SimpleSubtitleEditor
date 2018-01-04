# SimpleSubtitleEditor

An Blender Addon for editing subtitles.

## Features
- Adding/deleting lines of subtitle.
- Adjusting each lines with markers in the time line.
- Importing/exporting: SRT(SubRip) SUB(SubViewer).

## Usage

When activated, your should find an UI in Video Sequencer Editor > Properties > SimpleSubtitleEditor.

### From Scratch
Just press the 'new' button and there will be two markers added, marking the start and end frame of that subtitle line.

NOTE: Don't delete and insert markers manually. Use the buttons instead. There are background property storing info and manually adding or deleting markers will break its consistency.

### Import
Fill in the first line editor with the file path, then click the tick aside.

Then markers' position can be tweaked. Subtitles context can be changed or deleted.

Only file of format SRT or SUB is supported.

### Export
Fill in the last line editor with the file path, then click the tick aside.

Only file of format SRT or SUB is supported.

## Known Problems
- Stores only timecode info and titling info, no styling info or metadata.
- Only appending and deleting is supported (So that is why it's called "simple", for few people would use inserting).
- Encoding is based on your system's locale.

## Future Plan
Interface refraction? The current interface is slow for a large file.
