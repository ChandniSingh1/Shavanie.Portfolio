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

Each page switches on its own: screens narrower than 760px get the phone
version, wider screens get the desktop version (scaled to fit below 1440px).
Add ?desktop or ?mobile to a URL to force one.

To put it online: upload the whole folder (keep the assets folder next to the
HTML files) to Netlify Drop, GitHub Pages, Vercel or any web host.

Still to fill in before you share it:
  - GitHub and LinkedIn icons link to "#github" / "#linkedin" — swap in your profile URLs.
  - "Download PDF" on the resume links to "#resume-pdf" — add your PDF to the
    folder and point the link at it.


GitHub + Vercel, step by step
-----------------------------
1. Unzip this file. You get one folder with the .html pages and an assets folder.
2. On github.com, click New repository, name it (e.g. portfolio), keep it Public, Create.
3. On the new repo page click "uploading an existing file", drag in everything
   from the unzipped folder (all .html files, README.txt and the assets folder),
   then Commit changes.
4. On vercel.com, sign in with GitHub, click Add New > Project, pick the repo, Import.
   Framework preset: Other. Leave build command and output directory empty. Deploy.
5. Vercel gives you a link like portfolio-xyz.vercel.app. Every later commit to the
   repo redeploys the site automatically.
