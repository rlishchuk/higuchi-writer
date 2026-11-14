# Higuchi Writer

Write fiction scene by scene in Obsidian. Plan chapters, keep reference notes on your characters and locations, save versions of your text, and export the finished manuscript.

## Install and open

In Obsidian desktop 1.15.0 or later, open **Settings > Community plugins > Browse**. Find **Higuchi Writer**, then select **Install** and **Enable**. Click the book icon in the ribbon to open the manuscript panel.

The interface is available in Russian, English, and Simplified Chinese. Select **Interface language** in the Writer settings, then disable and re-enable the plugin or restart Obsidian. Existing manuscripts and filenames keep their original language. The included sample manuscript is in Russian.

## Write and organize a book

Choose **Create a book** to start a manuscript or **Open sample manuscript** to try the workflow. Outline supports parts, chapters, and scenes. Rename a section in the outline without renaming its file, or move a scene to another chapter from its menu.

Use **References** for the book plan, timeline, characters, locations, and plotlines. These notes are stored as Markdown in your vault and stay separate from the export. A scene can also have a separate plan for its point of view, participants, setting, and goals.

## Back up, check and export

Open a section’s menu and select **Save a text version** to keep a copy or **Restore text** to compare a copy with current text and restore it. Writer backs up the current text before replacing it.

Select **Check** to find missing files, incomplete sections, and broken links. Use **Preview** to read the assembled manuscript or **Export** to save EPUB, DOCX, Markdown, or HTML. For DOCX, use PNG or JPEG images. Each export creates its own folder. Writer’s version history supplements your vault backups.

## Optional editing with Ollama

Install Ollama and a local model separately. Select a passage and run **Higuchi Writer: Review selected text**. Choose a task, then run the review. The configured local Ollama server receives the selected passage and the instructions for that task. The limit is 6,000 characters per request. Review suggestions before saving or applying them.

## Privacy and license

Writer stores books, versions, and exports in your vault. There is no registration, telemetry, or remote account. Network requests are limited to the configured loopback Ollama server when you request a review or list installed models. Cloud models are rejected. Local images may be encoded as Base64 when building self-contained exports.

The official build is free to install and use. Source code is closed. See [LICENSE](LICENSE) for the binary terms and [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) for bundled dependencies.

[Руководство на русском](README.ru.md)
