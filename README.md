### Description

This code can be used to explore data with the following format:

- HDF4
- HDF5
- netCDF
- netCDF4
- IDL save file
- geoTIFF
- png

---
### Dependencies

- Python 3.6
  - [h5py](http://www.h5py.org/)
  - [pyhdf](http://fhs.github.io/python-hdf4/)
  - [scipy.io](https://docs.scipy.org/doc/scipy/reference/io.html)
  - [netCDF4](http://unidata.github.io/netcdf4-python/)
- gdalinfo
- [imgcat](https://www.iterm2.com/documentation-images.html)

---
### How to use

1. Install the dependencies;
2. Put this code under one of the system `$PATH` directories, e.g., `/usr/local/bin`.
3. Reopen a terminal, go to a directory that has data, e.g, `test.h5`,

  ```lss test.h5```

4. For data that has unclear extention, e.g., `test.idlsav`,

  ```lss test.idlsav idl```


