# Instructions to use git lfs

```
cd repo-home/
git lfs track "dstc1/*.tar.gz"
git add dstc1/*.tar.gz
git commit -am "message"      # if -am doesn't work, try -m first
git lfs ls-files              # you should see the *.tar.gz here on this list, otherwise lfs is not maintaining it
git push                      # only now files are pushed to remote
```
