---
title: 3.1 How to use the Audio interface
---
### 3.1.1	How to Open an Audio File
**The Audio functionality of Rezonator allows the user to listen to the dialog associated with the transcript being annotated. The user can play and pause the audio, set bookmarks within the audio track, and even select lines to play the audio of.**

In order to begin using audio in Rezonator, you’ll need to open an audio file. To do so, Left Mouse Click on the “Media” option from the “File” dropdown. Note: Rezonator only supports .OGG audio files.

![unnamed](https://user-images.githubusercontent.com/77072787/132409845-1003a101-1eb2-42b5-bdc9-f5ebdf37729f.png)

If the audio file successfully imports, then the Audio Interface will appear, like so:

![unnamed-2](https://user-images.githubusercontent.com/77072787/132410189-3b459c3d-c07a-4209-90aa-e4cdba658412.png)

### 3.2.2	How to navigate the Audio Interface

On the leftmost panel, we display the name and file location of the current Audio Track:

![unnamed-3](https://user-images.githubusercontent.com/77072787/132410284-df322c85-fe95-4bf4-b858-3fe5f3692c92.png)

At the top-middle portion of the interface is the Play/Pause Button. A Left Mouse Click on this button will play or pause the current Audio track. Also, pressing the Spacebar on you keyboard will play or pause the current Audio Track

![unnamed-4](https://user-images.githubusercontent.com/77072787/132410321-9fdfe990-02b8-45cb-a20c-c9de5d58f487.png)


On top of the Seek Bar is the Playhead, represented by an orange circle. This is a visual representation of what position in the current Audio Track is being played.

The Playhead can be clicked and dragged with a Left Mouse Hold to a different position on the Seek Bar, which will update the current position of the Audio Trail being played.

![unnamed-5](https://user-images.githubusercontent.com/77072787/132410359-0b09a920-685e-4e9e-a495-d132ff32f73b.png)


On the Right Most side of the Audio Interface is the Jump Audio Toggle Button. When this button is toggled on, and a Word on the Main Screen is Left Mouse Clicked, the Audio will jump to the Start Time of the Line that contains the word.

![unnamed-6](https://user-images.githubusercontent.com/77072787/132410896-9477ec92-0814-4a83-948a-81ab326fb56b.png)

### 3.2.3	How to make an Audio Bookmark

A more advanced feature of Rezonator’s Audio capabilities is Audio Bookmarks, which are used to set custom start times for Audio playing.

Audio Bookmarks are created by pressing the Enter Key on the keyboard. Once the Enter Key is pressed, and Audio Interface is open, an Audio Bookmark will be placed at the current position of the Audio Playhead

![unnamed-7](https://user-images.githubusercontent.com/77072787/132410937-530892d1-1778-4f20-ad12-6da0f0e521e6.png)

The Audio Bookmark is visualized by a green triangle above the Seek bar. When an Audio Bookmark is present, pressing the Spacebar will set the Audio Playhead back to the position of the Audio Bookmark, in addition to playing/pausing the current audio file.

### 3.2.4	How to use Play Stack

Another advanced feature is Play Stack, which allows the currently selected Stack Chain to determine the Audio Bookmark and Audio Endmark. To focus a Stack Chain, you can Left Mouse Click on the Stack Chain Name within the List Window.

Once a Stack Chain has been focused, the first and last Lines within the Stack Chain will be used to set the Audio Bookmark and Audio Endmark. The Audio Endmark, when present, prevents the Audio Playhead from moving past the Endmark’s position.

![unnamed-22](https://user-images.githubusercontent.com/77072787/132411090-0e83b208-071a-4388-aff3-07137f9996ba.png)

The Endmark is visualized with a red triangle below the Seek bar.

The Bookmark and Endmark created by focusing a Stack Chain will update based on a few situations:
If the current Stack Chain has links added to or taken away from them, the Bookmark and Endmark will update to reflect the new lines.
If a new Stack Chain is focused, then the Bookmark and Endmark will update to reflect the lines of the new Stack Chain.
If the currently focused Stack Chain is unfocused or deleted, then the Bookmark and Endmark will be disabled for now.
