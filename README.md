# ModaNet-MinorProject-

**Donwloading Data** (and reading)

1. `wget https://github.com/kyamagu/paperdoll/raw/master/data/chictopia/chictopia.sql.gz`

Once done, do this:

* <del>gunzip -c chictopia.sql.gz</del> `gunzip -c chictopia.sql.gz | sqlite3 chictopia.sqlite3`

(this will take a LOT of time, keep it running until the program terminates. **When it terminates, take a screenshot of the terminal window** (to ensure there was no error))


Update: (Feb 13 2019) **Step-1 Done!**

Next stop - **Download LMDB data (~40 GB).**

* <del>wget https://s3-ap-northeast-1.amazonaws.com/kyamagu-public/chictopia2/photos.lmdb.tar</del>
* `wget http://vision.is.tohoku.ac.jp/chictopia2/photos.lmdb.tar`


MD5SUM is: `a404789687fc3906d7d843942c802f53.`

Then extract the LMDB content:

`tar xf photos.lmdb.tar`
