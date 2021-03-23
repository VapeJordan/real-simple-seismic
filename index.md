# rss - Real Simple Seismic

Forget about SEGY - watch your seismic like frames in a movie.

rss is a real simple way to ingest and access stacked 3d seismic data. Once ingested, 
the seismic data is access slices, inlines, crosslines, time slices (todo) or in 
3D chunks (todo). 

rss provides a command-line tool for ingesting SEGY data into rss format. The output 
is a directory that can be kept on a local file system or places on in blob storage. 

rss supports serverless access to data on blob storage, currently only AWS S3 is supported, 
but support for other cloud solutions is on the product roadmap. 

rss requires Python 3.6 or better. 

Use rss in your project today!

pip install real-simple-seismic
