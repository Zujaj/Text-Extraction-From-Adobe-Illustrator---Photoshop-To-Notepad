# Related Issue

This PR addresses issue: **#github-issue-number**

## Summary

Provide a concise summary of the changes introduced in this PR.

### Sample Heading

- Implements text extraction from Adobe Illustrator and Photoshop files, saving results to Notepad-compatible text files.

- Adds support for extracting text from PDF files, with results saved in a structured format.

## Steps For Quality Assurance

Define the steps for the QA.

- Try to bullet down the steps with short summary, instead of using long paragraphs. See the below example

  - Checkout this branch
  - Open Adobe Photoshop.
  - Go to `File > Scripts > Browse...` and select the updated `.jsx` script from the `Photoshop-Script` directory.
  - Open a sample `.psd` file with text layer & run the script.
  - When prompted, select a location to save the exported text file.
  - Verify that the output `.txt` file contains the expected text content from all visible text layers.
  - Test with multiple open documents to ensure batch export works as expected.
  - Confirm UTF-16 encoding and correct text extraction.

- For nested lists, simply hit `tab` before `-` .
  - Grand Parent
    - Parent
      - Child
- For a numbered list, simply type `1.` then a `space`, some text and hit enter.

1. lorem ipsum.
2. lorem ipsum.

- Include links, images, nested, numbered lists if necessary.

  ![Sample Image](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

> Note: You can add qoutes as well by typing the `>` key and a `space`.

You can also use these general Markdown guides for the [Summary](#summary) section as well.

For more information, read this [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and install these markdown extensions on your Visual Studio Code as well for better productivity.

1. [markdownlint | David Anson](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
2. [GitHub Markdown Preview | Matt Bierner](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)
3. [Markdown All in One | Yu Zhang](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

## Additional Notes

- No external dependencies are required; the script runs directly in Adobe Photoshop via the ExtendScript engine.
- Refer to the [README.md](../README.md) for setup and usage instructions.
- Attach screenshots or logs if relevant.
- Ensure that the script is tested on both Windows and macOS platforms for compatibility. (Optional)
