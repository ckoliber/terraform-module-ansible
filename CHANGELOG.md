# [3.1.0](https://github.com/ckoliber/terraform-module-ansible/compare/3.0.0...3.1.0) (2025-07-26)


### Features

* transfer project from cktf to ckoliber ([6874335](https://github.com/ckoliber/terraform-module-ansible/commit/6874335cfbd7ef6d8e0c27e107eaa0437b9d5afe))

# [3.0.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.8.1...3.0.0) (2025-07-20)


### Features

* add playbook hash triggers_replace ([a837023](https://github.com/ckoliber/terraform-module-ansible/commit/a8370234c4c5ea7f3ea077d3e32c8b29a9a56b3b))


### BREAKING CHANGES

* merge create, destroy playbook args

## [2.8.1](https://github.com/ckoliber/terraform-module-ansible/compare/2.8.0...2.8.1) (2025-07-15)


### Bug Fixes

* add empty vars, groups to ungrouped group ([9a84204](https://github.com/ckoliber/terraform-module-ansible/commit/9a84204a4977d6ff66cd0a888ffb29789c040b7f))

# [2.8.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.7.0...2.8.0) (2025-07-15)


### Features

* add ungrouped default group ([2b714d5](https://github.com/ckoliber/terraform-module-ansible/commit/2b714d5c4856b21e76fb425ae7edb3e04441b2d7))

# [2.7.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.6.0...2.7.0) (2025-07-09)


### Bug Fixes

* restore empty terraform lock file ([0b1ac12](https://github.com/ckoliber/terraform-module-ansible/commit/0b1ac127e5024cc0375ffd11b9dfbb912005fe7d))


### Features

* add nonsensitive to show local-exec output ([0c89799](https://github.com/ckoliber/terraform-module-ansible/commit/0c897992a5ce44ab2cab2c0e3cc49bb864d318de))

# [2.6.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.5.0...2.6.0) (2025-02-22)


### Features

* add new CI ([bc45e78](https://github.com/ckoliber/terraform-module-ansible/commit/bc45e785f69d3d1753f72068126e27b05e958633))

# [2.5.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.4.0...2.5.0) (2025-02-18)


### Features

* replace date with mktemp ([8293207](https://github.com/ckoliber/terraform-module-ansible/commit/8293207fbf963642434144391c5f2a5c775c0c30))

# [2.4.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.3.0...2.4.0) (2024-11-26)


### Features

* remove inventory directory on successful playbook ([da95780](https://github.com/ckoliber/terraform-module-ansible/commit/da9578035b96a9a24cfc2f5fcf21ca908493afba))

# [2.3.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.2.0...2.3.0) (2024-11-26)


### Features

* add nanosecond to ansible inventory folder name ([63fc51e](https://github.com/ckoliber/terraform-module-ansible/commit/63fc51e78a48268da611c8b5a3cb587622395552))

# [2.2.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.1.0...2.2.0) (2024-11-26)


### Features

* add optional host vars ([3f85a48](https://github.com/ckoliber/terraform-module-ansible/commit/3f85a4825aab75838fd0bc59b2e08f60e50c75ef))

# [2.1.0](https://github.com/ckoliber/terraform-module-ansible/compare/2.0.1...2.1.0) (2024-11-26)


### Features

* add host vars ([8655ce7](https://github.com/ckoliber/terraform-module-ansible/commit/8655ce7e2396c4c4eb676a4adc7e2e206765f62b))
* disable inventory removal ([582678c](https://github.com/ckoliber/terraform-module-ansible/commit/582678c0583ee70dea7bb4b2eb316069699d0268))

## [2.0.1](https://github.com/ckoliber/terraform-module-ansible/compare/2.0.0...2.0.1) (2024-11-26)


### Bug Fixes

* disable ROOT remove on playbook errors ([42a0ff3](https://github.com/ckoliber/terraform-module-ansible/commit/42a0ff35bdc0a167eb3ca1be01068a6545a153f3))

# [2.0.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.6.0...2.0.0) (2024-11-18)


### Features

* add destroy time playbook ([6f4ab5f](https://github.com/ckoliber/terraform-module-ansible/commit/6f4ab5fd59cf4f4b6dc3405f8d2ca3c1a9ec5717))


### BREAKING CHANGES

* change variables

# [1.6.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.5.0...1.6.0) (2024-11-18)


### Features

* enable quite mode in local-exec ([891f3f3](https://github.com/ckoliber/terraform-module-ansible/commit/891f3f3e1034ac731b826386383a9c979fb2e323))

# [1.5.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.4.0...1.5.0) (2024-11-11)


### Features

* add UserKnownHostsFile ssh flag ([1de444c](https://github.com/ckoliber/terraform-module-ansible/commit/1de444c5d358d6ae12562a5058cffa0dd1aed66a))

# [1.4.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.3.1...1.4.0) (2024-10-16)


### Features

* change key, crt permissions ([cb16bfa](https://github.com/ckoliber/terraform-module-ansible/commit/cb16bfa34a75be6d997731e25ce431eda37127fb))

## [1.3.1](https://github.com/ckoliber/terraform-module-ansible/compare/1.3.0...1.3.1) (2024-10-16)


### Bug Fixes

* check template values not null ([b47f71b](https://github.com/ckoliber/terraform-module-ansible/commit/b47f71b6bbfd1f034e31b528c74f2de71f808c94))

# [1.3.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.2.0...1.3.0) (2024-10-09)


### Bug Fixes

* upgrade CI/CD ([632ee58](https://github.com/ckoliber/terraform-module-ansible/commit/632ee5825ce28e740a809498aa80109e86d0c0d4))


### Features

* change README ([a235dae](https://github.com/ckoliber/terraform-module-ansible/commit/a235dae3be86cd9e4792dd91afade904510d4742))

## [1.2.1](https://github.com/ckoliber/terraform-module-ansible/compare/1.2.0...1.2.1) (2024-10-09)


### Bug Fixes

* upgrade CI/CD ([632ee58](https://github.com/ckoliber/terraform-module-ansible/commit/632ee5825ce28e740a809498aa80109e86d0c0d4))

# [1.2.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.1.0...1.2.0) (2024-09-21)


### Features

* add LICENSE.md ([f678cb1](https://github.com/ckoliber/terraform-module-ansible/commit/f678cb1480b7cec14e9dca2bf2eed2a1e6eb689a))

# [1.1.0](https://github.com/ckoliber/terraform-module-ansible/compare/1.0.1...1.1.0) (2024-09-21)


### Features

* change README ([261ca9c](https://github.com/ckoliber/terraform-module-ansible/commit/261ca9c530c6930cc98551b5935dceccfdffb0db))

## [1.0.1](https://github.com/ckoliber/terraform-module-ansible/compare/1.0.0...1.0.1) (2024-09-21)


### Bug Fixes

* change ssh ProxyCommand ([094095b](https://github.com/ckoliber/terraform-module-ansible/commit/094095b84efbaf3bdd820f18d87ba5d5a05f0bee))

# 1.0.0 (2024-09-21)


### Bug Fixes

* change CI/CD ([ec3a1ee](https://github.com/ckoliber/terraform-module-ansible/commit/ec3a1ee590b04ed36dd8ed7f1680ca9f7bdb627a))


### Features

* add CI/CD ([50066ab](https://github.com/ckoliber/terraform-module-ansible/commit/50066abbf0caa2a5e8d4a9546027b42032783bf6))
* add empty lock file ([3f4b833](https://github.com/ckoliber/terraform-module-ansible/commit/3f4b833e6cc8e3ae5a1365f7bca249ddcf027455))
* enable playbook ([ff681ed](https://github.com/ckoliber/terraform-module-ansible/commit/ff681edc0fa8bad6b179b41e7b5d5f2e672bba91))
* init module ([fe876a2](https://github.com/ckoliber/terraform-module-ansible/commit/fe876a22e80af453847ef5a2e1673451ec5c8376))
