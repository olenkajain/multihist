.. :changelog:

History
-------


------------------
0.5.1 (2017-03-22)
------------------
* get_random for Histdd no longer just returns bin centers (Hist1d does stil...)
* lookup for Hist1d. When will I finally merge the classes...

------------------
0.5.0 (2016-10-07)
------------------
* pandas.DataFrame and dask.dataframe support
* dimensions option to Histdd to init axis_names and bin_centers at once

------------------
0.4.3 (2016-10-03)
------------------
* Remove matplotlib requirement (still required for plotting features)

------------------
0.4.2 (2016-08-10)
------------------
* Fix small bug for >=3 d histograms

------------------
0.4.1 (2016-17-14)
------------------
* get_random and lookup for Histdd. Not really tested yet.

------------------
0.4.0 (2016-02-05)
------------------
* .std function for Histdd
* Fix off-by-one errors

------------------
0.3.0 (2015-09-28)
------------------
* Several new histdd functions: cumulate, normalize, percentile...
* Python 2 compatibility

------------------
0.2.1 (2015-08-18)
------------------
* Histdd functions sum, slice, average now also work

----------------
0.2 (2015-08-06)
----------------
* Multidimensional histograms
* Axes naming

--------------------
0.1.1-4 (2015-08-04)
--------------------
Correct various rookie mistakes in packaging...
Hey, it's my first pypi package!

----------------
0.1 (2015-08-04)
----------------
Initial release

* Hist1d, Hist2d
* Basic test suite
* Basic readme
