ractice repository for learning Ansible, following a YouTube course.

## What's inside
- `inventory` and `ansible.cfg` – host list and basic configuration
- `install_apache1.yml` / `remove_apache1.yml` – playbooks to install and remove Apache
- `site.yml` – main playbook
- `site_tags.yml` – the same tasks organised with tags
- `files/` – supporting files used by the playbooks

## Run
ansible-playbook site.yml
ansible-playbook site_tags.yml --tags <tag>

## Reference
YouTube course: https://www.youtube.com/watch?v=teEhLgHpGgo&list=PLqyUgadpThTL1guZCdGy7H8V4snPrpj8t&index=11



