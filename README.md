# Fallout 76 Archive Explorer

Find which BA2 archive contains the Fallout 76 file you’re looking for—without extracting the game’s archives.

Browse **679,240 file entries across 40 archives** through a Fallout-inspired interface. Search, filter, and copy results directly in your browser.

**[Open the Archive Explorer](./index.html)**

## Find a file

Enter any part of a filename or folder path in the search field. Searches are case-insensitive, so `PowerArmor` and `powerarmor` return the same results.

Use the filters to narrow your search:

- **Archive:** Search every archive or choose a specific BA2 file.
- **File type:** Choose an extension such as `.dds`, `.nif`, or `.hkx`, or select **No extension**.
- **Search in:** Match the full internal path or just the filename.

You can also leave the search field empty and choose an archive or file type to browse its contents. Filters work together.

For example, search for `powerarmor` and select `.dds` to find matching texture filenames and the archives that contain them.

## Read and copy results

Each result shows the filename, its folder path inside the archive, and the BA2 archive that contains it. Matching text is highlighted.

- **Copy name** copies just the filename, including its extension.
- **Copy path** copies the complete internal path, including the filename.

Internal paths describe locations **inside an archive**, not locations on your computer. If your browser blocks clipboard access, you can select and copy the text manually.

Choose **25, 50, or 100 results per page**, then use the navigation buttons or enter a page number to move through the matches.

## Search tips

- Start with a distinctive part of the name, then narrow the results with filters.
- Use **Full internal path** to find folder names as well as filenames.
- Both forward slashes (`/`) and backslashes (`\`) work in search queries.
- Search matches literal text; wildcards and regular expressions are not supported.
- If nothing matches, shorten your search or reset the archive and file-type filters.

## Runs in your browser

The directory loads into memory when you open the explorer. The first load may take a moment, especially on slower connections or devices. After loading, searches run locally, and only one page of results is displayed at a time to keep the interface responsive.

No account or game installation is required. Search terms stay in your browser, and the explorer includes no analytics or tracking scripts.

If you download the HTML-and-JSON version to use offline, open the HTML file and select the accompanying JSON when prompted. The standalone HTML version includes the directory and opens without that step.

## About this directory

**Snapshot · 04 Oct 2026**

This directory contains filenames and archive membership only. It does not include or extract game assets, and it does not modify your installation. A file may appear in more than one archive, and later game updates may differ from this snapshot.

This is an unofficial fan project, not affiliated with or endorsed by Bethesda Softworks. Fallout and related names belong to their respective owners.
