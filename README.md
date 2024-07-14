## Wallpaper Upload and Formatting Guidelines

To maintain consistency and quality, please follow these guidelines when uploading and formatting wallpapers for the RisingWalls app.

### Image Requirements
- **Images in the .webp format are recommended**

#### Homepage Images
- **Resolution**: 720 pixels on the shortest dimension.
- Ensure the images are high quality and properly cropped.

#### Thumbnails
- **Resolution**: 480 pixels on the shortest dimension.
- Thumbnails should be clear and accurately represent the full-sized image.

### Formatting images
- **depth wallpapers are in the depth folder, flat wallpapers in flat, and homepage images in homepage.**

#### Formatting depth wallpaper
- **Background**: `depth/background/wallname.webp`.   
- **Subjects**: `depth/subjects/wallname_subject.webp`.    
- **Thumbnails**: `depth/thumbnails/wallname_thumbnail.webp`.  

#### Formatting flat wallpaper
- **Thumbnails**: `flat/thumbnails/wallname_thumbnail.webp`.  
- **Wallpaper**: `flat/wallname.webp`.  

#### Formatting home wallpaper
- **Wallpaper**: `homepage/wallname.webp` 

### Formatting json
- **Depth wallpapers are in depth_manifest.json, flat wallpapers in flat_manifest.json, and homepage wallpapers in homepage_manifest.json.**
- **Do not edit other values rather than the given common template values.**

#### Formatting depth wallpapers json
- Depth wallpapers require four values: `title`, `thumbnail`, `wallpaper`, and `subject`. Ensure all values are filled for proper functionality. Here’s a common template for depth_manifest.json:
   ``` json
    {
        "title": "Wallpaper name",
        "thumbnail": "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/depth/thumbnails/name_thumbnail.webp",
        "wallpaper": "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/depth/backgrounds/name.webp",
        "subject": "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/depth/subjects/name_subject.webp"
    }
   ```

#### Formating flat wallpapers json
- Flat wallpapers requires three values: `title`, `thumbnail` and `wallpaper`.Ensure all values are filled for proper functionality. Here’s a common template for flat_manifest.json:
    ``` json
    {
		"title": "Wallpaper name",
		"thumbnail": "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/flat/thumbnails/name_thumbnail.webp",
		"wallpaper": "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/flat/name.webp"
	}
    ```

#### Formatting homepage images json
- Now for the homepage images only the the image url is enough:
    ```json
    "https://raw.githubusercontent.com/RisingTechOSS/risingwalls_storage/fourteen/homepage/name.webp"
    ```

    
### Additional Notes
- Verify the resolution of all images before uploading.
- Unauthorized changes to the `target-level` attribute are prohibited.

## For further details on the JSON configuration and other repository-specific instructions, please refer to the community.