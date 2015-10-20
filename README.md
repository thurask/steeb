#steeb
steeb is a way to download music based on the search of an album and artist

**Demo:**  
[Click here for a demo gif](http://i.imgur.com/bulRcP1.gif)


**How does it work?**  
Steeb searches the musicbrainz library for the tracklists of your chosen artist and thereafter it does single queries to third party music services to get the mp3 files you want. Awesome, right?  

TODO:
- [x] Make a search on musicbrainz
- [x] Get all the tracks of an album
- [x] Loop through the tracks and search on pleer for it
- [x] Set download locations
- [x] Download all the tracks one by one
- [ ] Make progress bar work
- [ ] Reorganize code
- [ ] By pleer search make sure length match by song for better matches.
- [ ] Force 320kbs option
- [ ] Run beets on the downloaded tracks to format them immediately
- [ ] Make an exe for windows
- [ ] Making a settings window

Optional:
- [ ] Migrate to TkInter

**Build:**  
Make sure you have `wxpython` installed and you're using `python2` and `python2-pip` OR python2.7

```bash
# get requirements
$ pip install -r requirements.txt 

# run with steeb with: 
$ python2 steeb/steeb.pyw
$ python2.7 steeb/steeb.pyw
$ python2.8 steeb/steeb.pyw
```
