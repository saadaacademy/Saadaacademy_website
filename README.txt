SA'ADA ACADEMY WEBSITE
======================

Files
  index.html    the home page (must keep this name)
  gallery.html  the Gallery page
  (the design and scripts are built into the two HTML files)
  images/       logos and photos (gallery photos go in images/gallery)

Publish on GitHub Pages
  1. Create a new repository on GitHub.
  2. Upload everything in this folder, keeping the same structure.
  3. Settings > Pages > publish from the main branch.
  4. The site appears at yourusername.github.io/repository-name

Add a photo to the Gallery
  1. Put the photo in images/gallery (about 1200 px wide, under 300 KB).
  2. Open gallery.html and find "ADD PHOTOS HERE".
  3. Copy the example line from the comment, change the file name, alt text
     and caption, and paste it above the empty tiles.
  4. Delete one "Photo coming soon" tile for each photo you add.
  Tapping a photo opens it full screen with next and previous arrows.

Replace a photo elsewhere
  Replace the file in the images folder and keep the same file name.
  Institutions: masjidu-ssaada.jpg, dawa-college.jpg, madrasathu-ssada.jpg,
  women-institute.jpg, hope-shore.jpg
  Hero slideshow: hero-1.jpg, hero-2.jpg    Chairman: chairman.jpg

Home page preview strip
  In index.html find: class="gal"
  Replace each <div class="ph">Photo</div> with:
  <img src="images/gallery/photo-1.jpg" alt="Short description" loading="lazy">

Still to add when available
  Bank and UPI details (Support section), Google Maps link,
  registration details, real campus photos.
