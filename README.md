# manifests

Repo download repository package with manifests
 

## Rockchip Linux SDK

### Before You Start

#### Run the following commands to install the repo tool

```
curl https://gitee.com/oschina/repo/raw/fork_flow/repo-py3 -o /usr/local/bin/repo  # If you do not have the access permission to this directory, download the tool to any other accessible directory and configure the directory to the environment variable.
chmod a+x /usr/local/bin/repo
pip3 install -i https://repo.huaweicloud.com/repository/pypi/simple requests
```

#### set env

```
vim ~/.bashrc            
export PATH=~/bin:$PATH 
source ~/.bashrc   
```

### Obtaining Source Code

#### Method 1 : Use the repo tool to download the source code over SSH.

- RK3399 Socs:

``` 
repo init -u git@github.com:Fruit-Pi/manifests -b master -m rk3399.xml
.repo/repo/repo sync -c
``` 

- RK3568 Socs:

```
repo init -u git@github.com:Fruit-Pi/manifests -b master -m rk3568.xml
.repo/repo/repo sync -c
```

- RK3288 Socs:

```
repo init -u git@github.com:Fruit-Pi/manifests -b master -m rk3568.xml
.repo/repo/repo sync -c
```

- PX30 Socs:

```
repo init -u git@github.com:Fruit-Pi/manifests -b master -m px30.xml
.repo/repo/repo sync -c
```

#### Method 2: Use the repo tool to download the source code over HTTPS.


- RK3399 Socs:

``` 
repo init -u https://github.com/Fruit-Pi//manifests -b master -m rk3399.xml
.repo/repo/repo sync -c
``` 

- RK3568 Socs:

```
repo init -u https://github.com/Fruit-Pi//manifests -b master -m rk3568.xml
.repo/repo/repo sync -c
```

- RK3288 Socs:

```
repo init -u https://github.com/Fruit-Pi//manifests -b master -m rk3568.xml
.repo/repo/repo sync -c
```

- PX30 Socs:

```
repo init -u https://github.com/Fruit-Pi//manifests -b master -m px30.xml
.repo/repo/repo sync -c
``` 
