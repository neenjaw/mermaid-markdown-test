# mermaid-markdown-test

A rudimentary test using GitHub Actions to detect changes to the repo, filter out changed md.mermaid files, then compile them to a directory.

Plan would be eventually to create a markdown parser that could take mermaid codeblocks (designated by ```` ```mermaid ````), take the code block, produce an image to a build folder, comment out the block in the markdown then add an image reference to the markdown.
