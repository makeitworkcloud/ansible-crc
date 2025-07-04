# ansible-crc

Ansible role to deploy OpenShift Local (CRC) with an external DNS base domain. (Defaults for 12xCPU & 64 GB RAM RHEL server.)

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [crc_cpus](#crc_cpus)
  - [crc_disk_size](#crc_disk_size)
  - [crc_external_domain](#crc_external_domain)
  - [crc_kubeadmin_password](#crc_kubeadmin_password)
  - [crc_memory](#crc_memory)
  - [crc_pull_secret](#crc_pull_secret)
  - [crc_version](#crc_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.1`

## Default Variables

### crc_cpus

#### Default value

```YAML
crc_cpus: 10
```

### crc_disk_size

#### Default value

```YAML
crc_disk_size: 500
```

### crc_external_domain

#### Default value

```YAML
crc_external_domain: makeitwork.cloud
```

### crc_kubeadmin_password

#### Default value

```YAML
crc_kubeadmin_password: crc
```

### crc_memory

#### Default value

```YAML
crc_memory: 57344
```

### crc_pull_secret

#### Default value

```YAML
crc_pull_secret: ''
```

### crc_version

#### Default value

```YAML
crc_version: 2.52.0
```

## Discovered Tags

**_certs_**


## Dependencies

None.

## License

GPL-2.0-or-later

## Author

welchworks
