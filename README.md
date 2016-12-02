# pediy spider
 A series of spider written in py which make my life more comfortable  

## Overview
- `pediy_spider.py`  
A spider for the bbs of pediy's Android security forum,also you can modify the url to spider other forums.

## Prerequisite 
Execute the command below to solve the dependency:  
`sudo pip install -r requirement.txt` 

Whether for some personal reasons or others,it is very highly recommended to leverage the advantage of virtualenv to avoid some unnecessary pain from your local python enviroment.Just now,one of my colleagues encountered a strange problem then I fix it by using the virtualenv. maybe you can try this command:

`sudo -H pip install html5lib==1.0b8`



## Usage
Once all steps above you have done,just run one of the scripts which show in this repo to wait lots of 1s to see what will happen.For example:  
`python pediy_spider.py`

```
usage: pediy_spider.py [-h] (-a | -f FILTER | -gf GFILTER)

A spider for the bbs of pediy's Android security forum,also you can modify the
url to spider other forum.

optional arguments:
  -h, --help            show this help message and exit
  -a, --all             Get all titles
  -f FILTER, --filter FILTER
                        filter title
  -gf GFILTER, --gfilter GFILTER
                        filter good title
```

