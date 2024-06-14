# jupiter
jupiter notebooks

## Installing R kernel

- https://stackoverflow.com/questions/57870575/install-and-run-r-kernel-for-jupyter-notebook

```
conda config --add channels r
conda install --yes r-irkernel
```


## creating an image from an updated container

- https://www.howtogeek.com/devops/how-to-create-a-docker-image-from-a-running-container/

```
docker commit example-container example-image:latest

Now you can use your image to restore the filesystem from example-container into a new container instance:
docker run -d example-image:latest
```

## 19 free dataset sources

- https://careerfoundry.com/en/blog/data-analytics/where-to-find-free-datasets/
  1. https://datasetsearch.research.google.com
  1. https://data.gov
  1. https://www.earthdata.nasa.gov/learn/use-data
  1. http://opendata.cern.ch
  1. https://www.bfi.org.uk/industry-data-insights
- https://github.com/fivethirtyeight/data
- https://github.com/BuzzFeedNews
- https://pds.nasa.gov/datasearch/data-search/
- https://registry.opendata.aws


----
EOF

