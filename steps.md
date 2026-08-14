# Steps to Complete the Cat Mouth Website

## Step 1: Prepare Project Structure
- Create `source_img/` directory in the root.
- Prepare all original cat photos in `source_img/`.

## Step 2: Create Image Metadata
- For each cat photo, create a JSON file (e.g., `cat_photos.json`) that maps each image to the coordinates of the cat's mouth (x, y).
- The mouth coordinates will be used to place the speech bubble.

## Step 3: Build the Mouth Annotation Program
- Create a simple HTML/JS tool (e.g., `annotate.html`) that loads each cat photo.
- Allow clicking on the photo to mark the mouth position.
- Save/export the coordinates into the metadata JSON.
- Run this locally to populate `cat_photos.json`.

## Step 4: Prepare Speech Content
- Create a list of possible speech phrases (e.g., `speeches.json`).
- Ensure there are enough variations for randomness.

## Step 5: Extend `index.html`
- Load the cat photos and metadata.
- On page load:
  - Pick a random cat photo.
  - Pick a random speech phrase.
  - Position the speech bubble at the annotated mouth coordinates.
- Render the selected cat image and speech bubble.
- Style the speech bubble to look like the cat is speaking.

## Step 6: Prepare for GitHub Pages
- Ensure all assets are relative paths and work with static hosting.
- Confirm no server-side code is needed.
- Create a `README.md` with instructions if needed.

## Step 7: Deploy
- Push the repository to GitHub.
- Enable GitHub Pages in repo settings.
- Verify the site loads and picks a new cat/speech on each reload.
