# Viora Extension VR — Package Archive

This repository currently contains a packaged extension ZIP. It does not include the unpacked source tree at the repository root, so review the archive contents before installing or publishing it.

## Inspect and install

1. Download `viora-extension-vr-5_6-fixed.zip`.
2. Extract it into a new folder.
3. Inspect the files and permissions before running anything.
4. If it is a Chrome/Edge extension, open the browser's extensions page, enable Developer mode, choose **Load unpacked**, and select the extracted folder that directly contains `manifest.json`.
5. If the manifest is missing, unreadable, or requests unexpected permissions, do not install it.

## Safety and release notes

- Only install packages you trust.
- Do not put API keys in the archive, README, or Git history.
- Test the package in a separate browser profile before using it with personal accounts.
- Add the editable source code, a versioned changelog, and a reproducible packaging process before treating this ZIP as a release.
- Feature availability depends on the actual contents of this package; the filename alone does not verify functionality.

