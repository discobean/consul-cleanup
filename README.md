# consul-cleanup
Cleans up dead members and services in Consul
```
pip install consul-cleanup
```

## Usage
Specify a host with `--host`, defaults to localhost
```
consul-cleanup --host consul.service.consul
```

## Build notes
````
python setup.py sdist
twine upload dist/*
````

