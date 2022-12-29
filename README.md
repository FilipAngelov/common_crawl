# common_crawl
This repo contains an app that gets data from commoncrawl.org and extracts company info (ex. address) from WARC files

The structure of the notebooks is as follows:
-- Exec_Notebook.ipynb
|----Notebook_Setup.ipynb
|----Input_Domain.ipynb
|----Get_WARC.ipynb
|----Process_HTML.ipynb

The Exec_Notebook is used to run the other 4 notebooks and prints the final extracted info per domain in a dataframe.
