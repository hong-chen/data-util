### Description

This code can be used to explore data with the following format:

- HDF4
- HDF5
- netCDF
- netCDF4
- IDL save file

---
### Dependencies

- h5py
- pyhdf
- scipy.io
- netCDF4

---
### How to use

1. Install the dependencies;
2. Put this code under one of the system `$PATH` directories, e.g., `/usr/local/bin`.
3. Reopen a terminal, go to a directory that has data, e.g, `test.h5`,

  ```lss test.h5```

4. For data that has unclear extention, e.g., `test.idlsav`,

  ```lss test.h5 idl```


