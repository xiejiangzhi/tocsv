# To CSV

A tool to convert spreadsheet to csv format

## Support formats

* xlsx: Excel 2007 - 2013
* xlsm: Excel 2007 - 2013
* xls: Excel 97,
* ods: LibreOffice / OpenOffice.org
* xml: Excel 2002 2003 XML

**More see roo-rb/roo**


## Installation

```
$ gem install tocsv
```

## Usage

Convert first sheet

```
$ tocsv mydata.xls > mydata.csv
```

Specifiy a sheet index

```
$ tocsv mydata.xls:1 > mydata_sheet1.csv
```


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/tocsv.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
