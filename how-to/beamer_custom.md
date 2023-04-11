# Changing primary `beamer` colors

1. In your `border.css` file, change the hex color code in the custom property `--beamer-main: #1f38c5` to a different color
   - For example `#008000`
2. Open the `beamer_bar.svg` file using a text editor and search for `#1f38c5`. Replace `#1f38c5` with a different color, e.g., `#008000`. Save the `.svg` file.
3. Encode the `.svg` file to base64 format. For instance, you may use the following webapp: https://fffuel.co/eeencode/. Drag and drop the `.svg` file and copy the Data URI (`data:image/svg+xml;...`)

4. In your `border.css` file, locate `section` and the `background-image` property. Replace the original URI with the new URI generated in step 3.
5. 🎉🎉🎉

