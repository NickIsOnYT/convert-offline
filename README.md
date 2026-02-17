# [Convert to it!](https://convert.to.it/)
**Truly universal ~~online~~ offline file converter.**

If you'd like to contribute anything, please head over to the [original repo](https://github.com/p2r3/convert) and request it there.
This is only a repo that includes a script to run this tool offline.

Anyways,

# The Setup

**How to manually run the program/initial setup: (Windows)**

This requires a lot of setup, but it's only a one-time thing.

1. Download [Git](https://git-scm.com/install/) (make sure it's added to your PATH)
2. Download [Bun](https://bun.sh/) (make sure it's added to your PATH)
3. Open Powershell and cd to your preferred location (do not use symbols in the folder name)
4. Run `git clone --recursive https://github.com/p2r3/convert/` (it will create a new sub-folder) (If the main repo is deleted, you can change the link to this repo.)
5. Run `bun install` in the folder it created to install the dependencies
6. Run `bunx vite` to start the server. (note: if you close the Powershell window, it stops the server.)
7. Ctrl+Click the localhost link in the Powershell window or use your browser to go to the localhost url listed. (in my experience, the url is typically `localhost:5173/convert/`)


**How to run the program quickly after the initial setup: (Windows)**

It's important to do the previous steps to test if everything is working correctly.

1. Download the [release package](https://github.com/NickIsOnYT/convert-offline/)
2. Modify the `$targetPath` variable
3. You can now run it using that script. (again, closing the Powershell window will stop the server.)


**If you'd like to make a shortcut to the script:**

Place the script in a permanent location, then right-click and `send to` -> `Desktop (create shortcut)`, then you can customize the shortcut and place it anywhere.
