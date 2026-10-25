HANNAH & CASSY PHOTO COLLAGE

HOW TO ADD YOUR OWN PHOTOS
1. Put your image files (JPG, PNG, or WebP) inside the images folder.
2. Open index.html in a text editor such as Notepad or VS Code.
3. Find the `const photos = [` section.
4. Add one entry per photo, using the filename, like this:
   { src: "images/photo-01.jpg", caption: "A favourite memory" },
5. Remove the sample image entries if you only want your own pictures.
6. Save index.html and refresh the page.

The public-facing page has no upload buttons or photo management controls.
For the collage to work when published online, upload the entire folder structure
(index.html plus the images folder) to your web host. Use exact filenames and
capitalization. The sample images currently use online image URLs as placeholders.
