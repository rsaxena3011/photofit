# PhotoFit

**Make every photo fit.** A free offline tool for resizing, cropping, rotating, and compressing images. The complete app is one editable HTML file.

![PhotoFit - Make every photo fit. Resize. Crop. Compress.](Images/Banner-Horizontal.png)

## Start here

1. Extract the ZIP into a folder on your computer.
2. Open **index.html** in a modern browser. If it opens in an editor, right-click it and choose **Open with → your browser**.
3. Add photos, choose your output settings, and click **Process photos**.
4. Compare the original and result. Save one image or the finished batch as a ZIP.

Only **index.html** is needed to run PhotoFit. All HTML, CSS, and JavaScript are inside it. There is no installer, build command, account, subscription, or external dependency.

## What you can do

- Choose a 50 KB, 100 KB, 200 KB, or custom file-size limit, or use no limit.
- Resize by width, height, longest edge, or a bounding box while keeping proportions.
- Crop each photo with a free selection or a preset shape; drag the crop, use its corner handles, or enter pixel values.
- Rotate individual photos in 90-degree steps.
- Export JPG, PNG, or WebP where the browser supports WebP encoding.
- Compare actual file sizes, dimensions, and appearance before saving.
- Process a batch and download the finished images together in one ZIP.

Output settings apply to the batch. Each photo has its own crop and rotation. Changing settings clears the affected results; process again before saving.

## Need exactly 600 × 600 pixels?

1. Select the photo, click **Crop**, choose **1:1 square**, and apply it.
2. Choose **Image dimensions → Set width**, then enter **600**.
3. Enable **Allow enlarging smaller images** if the cropped image is smaller than 600 pixels.
4. Turn off **Allow smaller dimensions to meet the limit**.
5. Process and check the displayed output dimensions and file size.

PhotoFit reports when the chosen dimensions cannot meet your file-size limit. A bounding box preserves proportions; it does not stretch a rectangular image into a square.

## File-size limits and formats

Limits use decimal KB: **100 KB = 100,000 bytes**. PhotoFit checks the actual encoded size. JPG and WebP can adjust quality; PNG uses lossless encoding. When the smaller-dimensions option is enabled, PhotoFit may also reduce width and height to fit the limit. An unmet target is clearly labeled **Over limit**.

JPG fills transparent areas with the chosen background color. PNG and WebP preserve transparency where supported. Re-encoding changes metadata and can change color appearance. Keep your original files for archival use. PhotoFit works with pixel dimensions, not print DPI settings.

## Privacy and saving

The app works offline and makes no network requests. It processes photos in this tab and saves new copies; the original files are unchanged. **Save your results before closing or reloading the tab.** The app does not save your batch between sessions.

If saving is blocked in a download preview, extract the ZIP and open **index.html** directly. Your browser controls the download location. A ZIP contains only successfully processed images; check any **Over limit** labels before uploading them elsewhere.

## Practical limits

- Up to **50 still images** per batch, **50 MB** per input file, and **64 megapixels** per input image.
- Input: JPG, PNG, and still WebP. GIF, HEIC, SVG, PDF, animated PNG, and animated WebP are not supported.
- Exports: up to **8,192 pixels per side** and **16 megapixels**. Large images may be reduced; the result shows its actual dimensions.
- Combined ZIP: up to **250 MB** of processed images. Save larger results individually or use a smaller batch.

## Package contents

| File | Purpose |
| --- | --- |
| **index.html** | The complete app and editable source. |
| **README.md** | This quick-start and upload guide. |
| **Listing-Copy.txt** | Product copy, FAQ, captions, GitHub copy, and image alt text. |
| **LICENSE.txt** | MIT license. |
| **Images/Banner-Horizontal.png** | Wide product cover / README banner; 1672 × 941 px. |
| **Images/Banner-Vertical.png** | Portrait promotional banner; 941 × 1672 px. |
| **Images/Banner-Square.png** | Product thumbnail / square post; 1254 × 1254 px. |
| **Images/Product-Image.png** | Text-free supporting illustration; 1254 × 1254 px. |
| **Images/Image-Prompts.txt** | Original artwork prompts and dimensions. |

The images are finished promotional illustrations, not screenshots of the interface. The app runs independently of the Images folder.

## Upload to Gumroad

1. Create a digital product titled **PhotoFit - Free Image Resizer & Compressor**.
2. Paste the summary and full description from **Listing-Copy.txt**.
3. Use **Banner-Horizontal.png** for the cover and **Banner-Square.png** for the thumbnail.
4. Set the minimum price to **0**. Gumroad may show **0+**; visitors can enter **0** to download free. PhotoFit has no paid tier.
5. Add this complete ZIP as the downloadable content. Preview the page and verify the free download option before publishing.

## Upload to GitHub

1. Create a public repository, for example **photofit**.
2. Upload the extracted folder's contents. Keep **index.html**, **README.md**, and **LICENSE.txt** at the repository root, along with the **Images** folder.
3. Use the repository description and topics in **Listing-Copy.txt**.
4. For an optional live version, choose **Settings → Pages → Deploy from a branch**, select your default branch and **/(root)**, then save.
5. Attach this ZIP to a GitHub Release for a convenient complete download.

For other platforms, reuse the ZIP, copy, and banner shape that fits the listing. Add your published download link after the social captions.

## Version and license

PhotoFit 1.0. MIT licensed; keep the license notice with redistributed copies.

Verification: 10 image-processing/archive checks and two simulated UI workflows passed, including real JPG/PNG/WebP encoding and independent ZIP extraction. Live browser layout and compatibility testing remain unverified because the preview service was unavailable in the build environment.

Platform guidance: [Gumroad covers](https://gumroad.com/help/article/60-adding-a-cover-image), [Gumroad free pricing](https://gumroad.com/help/article/133-pay-what-you-want-pricing), [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
