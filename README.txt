Nikhil Lokesh portfolio website
================================

What is in this folder
  index.html        The whole website. The words, design, 3D sky, globe, company logos, animations,
                    fonts and music are all inside this one file (about 4.5 MB), so it works without
                    internet and on locked-down networks.
  Nikhil-L_CV.pdf   Your CV, linked from the "View my CV" and "Download my CV" buttons.
  licenses/         Licences for the two fonts (SIL Open Font License) and the credit the music's
                    licence requires (CC BY 3.0). Keep them with the site.

Keep index.html and the CV together in the same folder.

Preview it on your computer
  Double-click index.html. It opens in Chrome, Edge, Safari or Firefox, even with no internet.
  Press the record player in the top corner to play the music.

Publish it for free with Netlify
  1. Go to https://app.netlify.com/drop and sign up or log in.
  2. Unzip this download, then drag the whole folder onto the page.
  3. You get a live link right away, such as something.netlify.app, and can rename it in the site settings.

Use your own domain (optional)
  Buy a domain such as nikhillokesh.com from a registrar (GoDaddy, Namecheap, Hostinger),
  then add it under Domain management in Netlify.

Editing it in another Claude account
  1. Attach this zip file to a new chat. Attach the zip itself, not index.html: the page is about 4.5 MB
     because everything is inside it, which is too big to send as a single file in chat.
  2. Paste this message, then add what you want changed:
     "Unzip the attached file. Publish index.html as an artifact exactly as it is. Don't open, rewrite or
      shorten it: it already contains everything it needs, including the 3D code, fonts, logos and music.
      Upload Nikhil-L_CV.pdf to that artifact and point the 'View my CV' and 'Download my CV' links at it.
      Then make these changes: ..."

Editing the file yourself
  Open index.html in a text editor such as VS Code and use Find (Ctrl+F) for the words you want to change.
  Your content and styles are near the top. Long blocks near the end hold the embedded fonts, code
  libraries, logos and music; leave those as they are.

The easter eggs (for you to show off)
  - Konami code (up up down down left right left right B A): the page does a barrel roll.
  - Type "liftoff": a rocket launches up the screen.
  - Scroll really fast: a sonic boom.
  - Tap the initials / name in the top corner five times: a paper plane squadron.
  - Hold the record player for a second: the cabin seatbelt chime.

Updating the live site
  After any change, drag the folder onto Netlify again from your site's Deploys page.
