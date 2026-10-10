# Editing Jessi's Whims

This is a plain HTML website. No subscriptions, CMS, dependencies, or build commands are needed.

## Publish on GitHub Pages

In the repository, open Settings → Pages. Under Build and deployment, select Deploy from a branch, then main and / (root), and Save.

Expected address after deployment: https://sslaughter.github.io/jessieswhims/

## Add a bouquet in GitHub

1. Upload your photo using Add file → Upload files. Use an images folder and a simple filename, such as images/autumn-bouquet.jpg. Resize large photos before uploading (around 1600 pixels wide is usually plenty).
2. Open index.html and click the pencil to edit it.
3. Find ADD BOUQUETS HERE. Copy the <article> through </article> template and paste it outside the HTML comment, immediately before the template comment.
4. Replace the bouquet name, image path, image description, date, recipe, verse, song, and idiom. Give each bouquet heading a unique id and use the same value in its article's aria-labelledby.
5. Remove the empty-state div for your first bouquet. Put later bouquets above earlier ones.
6. Commit the change. Once Pages finishes deploying, refresh the live site.

You can add another image inside an article with another <img> tag. Add a song link with <a href="https://your-listening-link">Listen to the song</a>.

Use &amp; for an ampersand and &lt; for a literal less-than sign in text. The template is hidden inside <!-- and -->; published entries must be outside those markers.

All repository files and committed history are public. Keep only photos and text intended for sharing in the repository.
