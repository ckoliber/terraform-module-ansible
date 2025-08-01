# Terraform Module Ansible

![pipeline](https://github.com/ckoliber/terraform-module-ansible/actions/workflows/ci.yml/badge.svg)
![release](https://img.shields.io/github/v/release/ckoliber/terraform-module-ansible?display_name=tag)
![license](https://img.shields.io/github/license/ckoliber/terraform-module-ansible)

Terraform module to generate dynamic inventory from SSH/WinRM connections and run ansible-playbook over that

> This modules needs Ansible to be installed on local

## Installation

Add the required configurations to your terraform config file and install module using command bellow:

```bash
terraform init
```

## Usage

```hcl
module "ansible" {
  source = "ckoliber/ansible/module"

  hosts = {
    server-1 = {
      groups = ["cluster"]
      connection = {
        host        = "192.168.1.10"
        user        = "root"
        private_key = "<REDACTED>"
      }
    }
    server-2 = {
      groups = ["cluster"]
      connection = {
        host        = "192.168.1.11"
        user        = "root"
        private_key = "<REDACTED>"
      }
    }
    server-3 = {
      groups = ["cluster"]
      connection = {
        host        = "192.168.1.12"
        user        = "root"
        private_key = "<REDACTED>"
      }
    }
  }

  groups = {
    cluster = {
      vars = {
        myKey = "myValue"
      }
    }
  }

  playbook     = "main.yml"
  create_args  = "--tags create"
  destroy_args = "--tags destroy"
}
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the [MIT](LICENSE.md).  
Copyright (c) KoLiBer (koliberr136a1@gmail.com)
