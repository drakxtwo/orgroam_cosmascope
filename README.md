# orgroam_cosmascope
Convert org-roam files to a cosmascope for portability.

An experiment firstly in using ChatGPT & secondly to see if it was possible. This is adapted from Kévin Polisano’s obsidian2cosma.py (https://github.com/kevinpolisano/obsidian2cosma) which converts your Obsidian vault to a cosmascope. 

Cosmascope describes itself as a knowledge visualisation tool for knowledge workers and it allows you to create an HTML page which displays much like org-roam-ui or obsidians graph. 

Consider this as work in progress and to be improved! There are limitations
 - cosmascope will not display images if linked in your text
 - the script does not handle internal links well ie in the generated log you may see
   - The following paragraph contains a broken link
          "[[49F6458C-14AA-4C4B-9F6B-7F007E2199F9|emacs again?]]"

I'm sure there will be other issues but for an experiment and a test on a small org-roam data set it worked quite well.
