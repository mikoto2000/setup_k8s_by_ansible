# setup_k8s_by_ansible

[Oracle Cloud Free Tier の Ampere A1 VM(ARM VM) に Kubernetes をインストールする - mikoto2000 の日記](https://mikoto2000.blogspot.com/2022/03/oracle-cloud-free-tier-ampere-a1-vmarm.html) の作業内容を Ansible で実現したもの。

## Usage:

Fix `.env`, `hosts` and run `docker compose`.

```sh
docker compose run --rm ansible
```

Run `ansible-playbook` command in container.

```sh
ansible-playbook -i hosts ./site.yaml
```

## License:

Copyright (C) 2022 mikoto2000

This software is released under the MIT License, see LICENSE

このソフトウェアは MIT ライセンスの下で公開されています。 LICENSE を参照してください。


## Author:

mikoto2000 <mikoto2000@gmail.com>

