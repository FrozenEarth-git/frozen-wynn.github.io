Part 1: How to download a clone of hppeng-wynn to edit and test with on your own machine:
1. download ZIP of the repo
2. unzip
3. open command prompt
4. navigate to the folder root `hppeng-wynn.github.io/` - use `cd (filepath)`, can use Windows Explorer to get filepath 
5. run `python3 -m http.server`
6. go to `localhost:8000` in your browser
7. you now have a local version of the site in your browser!

Part 2: How to update the ability tree file and test it:
1. open a local version of the site in your browser - see part 1
2. open another command prompt
3. navigate to the folder `hppeng-wynn.github.io/js/builder` - see step 4 of previous part
4. make changes to `atree_constants.js`
5. run `python3 ../../py_script/atree-generateID.py`
6. refresh the site and check that it still works
