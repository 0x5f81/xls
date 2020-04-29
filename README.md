# xls

forked from extrame/xls

fix problems at comparexlsxlsx.go by 0x5f81 (last tealeg/xlsx does not have property Rows and Cols)

Pure Golang xls library writen by Rongshu Tech (chinese), based on libxls. 

Thanks for contributions from Tamás Gulácsi @tgulacsi, @flyin9.

# Basic Usage

* Use **Open** function for open file
* Use **OpenWithCloser** function for open file and use the return value closer for close file
* Use **OpenReader** function for open xls from a reader, you should close related file in your own code

* Follow the example in GoDoc
