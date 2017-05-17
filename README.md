# HW4: Creating your own playlist

You will need:
- Your songs in .mp3 form. 
- CS193X disclaimer: please don't do anything illegal re: music downloading.

1. In Github, create a new repository using the + in the top right corner.
![Image: create new repository](/images/1.png?raw=true)

2. Make sure to check the box labeled "Initialize this repository with a README." Name your repository anything you want.
![Image: initialize with readme](/images/2.png?raw=true)

3. On your computer, put your song mp3s in a folder...
- It might be helpful to shorten the song titles
- The rest of these instructions assume you used `songs` as the folder name
![Image: songs in folder](/images/4.png?raw=true)

4. On Github, click "Upload Files" (just as you do when submitting homework).
![Image: upload files](/images/3.png?raw=true)

5. Drag the entire folder into the upload box.
- This definitely works on Chrome (and doesn't work on Safari). I'm not sure if it works on Firefox or Edge
- Make sure to drag the **folder** and **not the individual songs**
![Image: drag entire folder](/images/5.png?raw=true)

6. Now publish the site (just as you do when submitting homework).
- Go to the "Settings" tab
- Change "Source" to "master branch" and click "Save"
![Image: settings](/images/6.png?raw=true)
![Image: master branch](/images/7.png?raw=true)

7. When you go to the link (in my example, https://sofiecaprice.github.io/whatever-name-here/), not much shows up. 
- Add `songs/[copy-paste the name of the mp3]` to the end of the URL, like `https://sofiecaprice.github.io/whatever-name-here/songs/toby fox - UNDERTALE Soundtrack - 25 Dating Start!.mp3` and hit enter
- You should see a mp3 player and be able to hear your song
![Image: mp3 player](/images/8.png?raw=true)

8. Now, copy the URL from the URL bar and save it somewhere (ie. email it to yourself, paste it in a google doc, etc). This URL is escaped, like `https://sofiecaprice.github.io/whatever-name-here/songs/toby%20fox%20-%20UNDERTALE%20Soundtrack%20-%2025%20Dating%20Start!.mp3`

9. Repeat steps 7 and 8 for each song in the songs/ folder

10. On your text editor (ie. Atom, Sublime, vim, etc), open a new file. Copy and paste the **text** from https://yayinternet.github.io/hw4-music/songs.json
![Image: orignal json](/images/9.png?raw=true)

11. Replace it with information from your songs
- Use the links you saved in step 8
- Save this file with a .json extension
![Image: your json](/images/10.png?raw=true)
![Image: json extension](/images/11.png?raw=true)

12. On Github, upload your file
- It's best to upload only this file (no need to re-upload songs)
- It's also good to upload it into your main directory (ie. not the songs/ folder)
![Image: upload json file](/images/12.png?raw=true)

Now, you should be able to access your .json file! Go to your published site link (in my example, https://sofiecaprice.github.io/whatever-name-here/) and add your json file name at the end, like `https://sofiecaprice.github.io/whatever-name-here/amy-songs.json`
