# github-oauth2
github的oauth2认证
======

Tornado + GitHub OAuth

Simple Demo of setting up GitHub OAuth with Tornado

Support python3

### Installation

```
pip3 install -r requirements.txt
```

### Development

You'll need a client ID and client secret from GitHub, which you can get from:

https://github.com/settings/applications/new

or, if using an organization:

https://github.com/organizations/<your_org>/settings/applications/

填充run.sh的相应字段，并执行:

```
bash run.sh
```

访问:
```
http://localhost:8088
```

