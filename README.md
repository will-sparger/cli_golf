# CLI Golf

1. **Read:** [ProGit, Chapter 1.1](http://git-scm.com/book/en/Getting-Started-About-Version-Control)
2. Using `mv`, `cp`, `rm` and `mkdir`, reorganize the kitchen in as few steps as possible!
3. Once you're finished, go up to the file menu at the top and click `Shell` -> `Export Text As...` and save the output to your desktop. Tomorrow you'll submit this file to your homework repository. 

## Start Here:

    kitchen/
    ├── cans.txt
    ├── fridge
    │   ├── diapers.txt
    │   ├── freezer
    │   │   ├── couch.txt
    │   │   ├── frozenpeas.txt
    │   │   └── icecream.txt
    │   ├── milk.txt
    │   └── trashcan
    │       ├── banana-peels.txt
    │       ├── chicken-bones.txt
    │       ├── egg-shells.txt
    │       └── sink
    │           ├── clean-dishes.txt
    │           ├── delete-me.txt
    │           └── dirty-dishes.txt
    └── pantry
        ├── cans.txt
        ├── cereal.txt
        └── crisper-drawer
            └── lettuce.txt

## End Here:

    kitchen/
    ├── fridge/
    │   ├── crisper-drawer/
    │   │   ├── apples.txt
    │   │   └── lettuce.txt
    │   ├── freezer/
    │   │   ├── frozenpeas.txt
    │   │   └── icecream.txt
    │   └── milk.txt
    ├── pantry/
    │   ├── cans.txt
    │   └── cereal.txt
    ├── sink/
    │   ├── dirty-dishes.txt
    │   └── drying-rack/
    │       └── clean-dishes.txt
    └── trashcan/
        ├── banana-peels.txt
	    ├── chicken-bones.txt
	    └── egg-shells.txt

## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
