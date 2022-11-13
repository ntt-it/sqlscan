git clone https://github.com/ntt-it/sqlscan.git
cd sqlscan
pip install -r requirements.txt
python main.py -d <dork> -w

```
usage: main.py [-h] -d DORK [-w]

optional arguments:
  -h, --help            show this help message and exit
  -d DORK, --dork DORK  dork to search example: product.php?id=
  -w, --write-over      write over the existing log file
```
