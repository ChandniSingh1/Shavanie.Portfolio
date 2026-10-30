Shavanie Singh — portfolio website
==================================

Open index.html to view the site. Every page has a desktop and a phone version:

  index.html / m-index.html          Home
  about.html / m-about.html          About
  resume.html / m-resume.html        Resume
  writing.html / m-writing.html      Short story
  cardstory.html / m-cardstory.html  CardStory case study
  wikipedia.html / m-wikipedia.html  Wikipedia iOS case study
  aetherplay.html / m-aetherplay.html AetherPlay case study
  recall.html / m-recall.html        Recall Command Center case study

Each page switches on its own: screens narrower than 760px get the phone
version, wider screens get the desktop version (scaled to fit below 1440px).
Add ?desktop or ?mobile to a URL to force one.

To put it online: upload the whole folder (keep the assets1 and assets2 folders next
to the HTML files) to Netlify Drop, GitHub Pages, Vercel or any web host.


GitHub + Vercel, step by step
-----------------------------
1. Unzip this file. You get one folder with the .html pages plus two
   image/video folders, assets1 and assets2 (split so each upload stays under
   GitHub's 100-file limit).
2. On github.com, click New repository, name it (e.g. portfolio), keep it Public, Create.
3. Upload in three rounds (GitHub allows 100 files per upload):
   a. Click "uploading an existing file", drag in all the .html files, README.txt
      and vercel.json. Commit changes.
   b. Add file > Upload files, drag in the assets1 FOLDER itself. Commit changes.
   c. Add file > Upload files, drag in the assets2 FOLDER itself. Commit changes.
4. On vercel.com, sign in with GitHub, click Add New > Project, pick the repo, Import.
   Framework preset: Other. Leave build command and output directory empty. Deploy.
5. Vercel gives you a link like portfolio-xyz.vercel.app. Every later commit to the
   repo redeploys the site automatically.
