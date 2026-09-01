OPR 2026 — Gallery Setup
==========================

This is a complete, working webpage with a real click-to-enlarge photo gallery,
grouped by month, with your report titles and "Tarikh Hantar" dates already filled in.

TO MAKE IT WORK (2 minutes):

1. Go to your "OPR 2026" folder in Google Drive.
2. Select all the photos, right-click → Download (Drive will zip them for you).
3. Unzip that download. You'll get a folder full of images with their original
   filenames (e.g. 060426a.png, 220226.jpg, etc.) — don't rename them.
4. Copy ALL of those image files into the "images" folder that came with this
   README (the empty "images" folder sitting next to index.html).
5. Open index.html in any web browser (double-click it). That's it — the
   gallery, captions, and click-to-enlarge will all work.

SHARING WITH YOUR COLLEAGUE:
Once the images folder is filled in, you can:
  - Zip the whole "opr-gallery" folder (index.html + images folder together)
    and send it via email or upload it to Drive for your colleague to download
    and open — OR
  - Upload the whole folder to any free static hosting (e.g. Google Sites'
    embed, Netlify Drop, GitHub Pages) if you want a live shareable link
    instead of a downloaded file.

UPDATING LATER:
To add a new report, just add its image file to the "images" folder, and add
a matching entry to the DATA list near the top of the <script> section in
index.html (copy an existing entry's format — file, title, date).

Missing images show a small placeholder message on the page itself, so you'll
immediately notice if a filename doesn't match.
