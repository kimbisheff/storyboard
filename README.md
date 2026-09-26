# storyboard
storyboard template for video projects 
Fillable, printable video storyboard for JOUR 4462 (Senior Media Practicum) at Cal Poly San Luis Obispo.

**Live tool:** https://kimbisheff.github.io/storyboard/

## What it does

A browser-based version of the JOUR 4462 paper storyboard. Each shot has a frame for a sketch or screen grab, plus fields for length, audio, speaker and timecode, what's on screen, and the shot's purpose. Students fill it in directly in the browser, with no account and nothing to install.

- **Add, remove, duplicate and reorder shots.** Drag a shot by its handle or use the arrow buttons. Shot numbers update automatically.
- **Frame images.** Click, drag and drop, or paste an image into any frame.
- **Running time.** The header totals the length of every shot.
- **Autosave.** Work saves in the browser as you type.
- **Multiple storyboards.** Keep several named storyboards in one browser, which is useful on shared lab computers.
- **Export and import.** Save a storyboard as a `.json` file to move it to another computer or hand it to a teammate.
- **Print or save as PDF.** Prints six shots per landscape letter page, with the header and page numbers repeated on each page.

## For students

1. Open the live tool and fill in your team name and story.
2. Fill in each shot. The audio key is at the top: SOT = soundbite, NAT = natural sound, VO = narration. List the speaker and timecode for every SOT.
3. Add, delete or reorder shots as your story changes.
4. When you're done, click **Print / PDF** and choose "Save as PDF" to submit.

Your work is saved only in the browser you're using. To work on another computer or share with your team, click **Export**, send the `.json` file, and open it with **Import**. Clearing your browser data will erase anything you haven't exported.

## Hosting your own copy

The tool is a single HTML file with no build step and no backend.

1. Create a GitHub repository and add `index.html`.
2. In the repository, go to **Settings → Pages**, set the source to the `main` branch, and save.
3. After a minute or two, the tool is live at `https://<username>.github.io/<repository>/`.

It also works when opened directly from your computer, though fonts load from Google Fonts and need an internet connection. Without one, the page falls back to system fonts.

## Privacy

Nothing is sent to a server. Storyboards and images are stored in the browser's local storage on the student's own device, and only leave it when the student exports a file.

## License

Released under the [MIT License](LICENSE). You're welcome to adapt it for your own courses.

## Credits

Created by Kim Bisheff, Cal Poly Journalism Department. Built with assistance from Claude (Anthropic).
