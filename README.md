# INSTRUCTIONS


## 1. Editing Site Configuration
1. Open the `_config.yml` file.
2. Edit the values to match your personal details, such as `title`, `email`, `description`, `url`, etc.

## 2. Adding New Artworks
You can add new artworks as either remote videos (from Vimeo) or local images.

### Adding a Vimeo Video
1. Go to the `_artworks` folder.
2. Create a new file named `artwork-title.md` (replace `artwork-title` with a meaningful name for your artwork).
3. Use the following template:

    ```markdown
    ---
    layout: artwork
    title: "Artwork Title"
    description: "This is a description of the Vimeo video artwork."
    media: "https://vimeo.com/your-video-id"
    ---
    ```

4. Replace `"Artwork Title"` with the title of your artwork.
5. Replace `"This is a description of the Vimeo video artwork."` with a description of your artwork.
6. Replace `"https://vimeo.com/your-video-id"` with the actual URL of your Vimeo video.

### Adding a Local Image
1. Place the image file in the `pictures` folder.
2. Go to the `_artworks` folder.
3. Create a new file named `artwork-title.md` (replace `artwork-title` with a meaningful name for your artwork).
4. Use the following template:

    ```markdown
    ---
    layout: artwork
    title: "Artwork Title"
    description: "This is a description of the local image artwork."
    media: "/pictures/your-image-file.jpg"
    ---
    ```

5. Replace `"Artwork Title"` with the title of your artwork.
6. Replace `"This is a description of the local image artwork."` with a description of your artwork.
7. Replace `"/pictures/your-image-file.jpg"` with the path to your image file.

## 3. Editing Existing Artworks
1. Go to the `_artworks` folder.
2. Click on the artwork file you want to edit.
3. Make your changes using the template format provided above.

## 4. Using GitHub to Manage Your Portfolio
1. Log in to GitHub and navigate to your repository.
2. Click on the file you want to edit.
3. Click the pencil icon to edit the file.
4. Make your changes and commit them.


