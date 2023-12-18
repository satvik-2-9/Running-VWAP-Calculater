# NASDAQ ITCH 5.0 Running VWAP Calculater

Calculate the running Volume weighted average price(VWAP) of each stock at all trading hours given the NASDAQ ITCH 5.0 tick data file.

The program will print the execution time at the end.

### Output

`/out` folder has VWAP results for each trading hour, and the files are named by the timestamp


### Running 

Navigate to the VWAP directory and run the following commands in your terminal.

```
mkdir out
python setup.py build_ext --inplace
python main.py [itch_file_path] 
```

If ITCH file path is not provided, the program will look up for the file in the current working directory
