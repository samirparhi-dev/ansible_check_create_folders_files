## Ansible Role to Ensure File and Folders

usage:
- create a `requirements.txt` in you role 
- Add it to requirements:
```
---
roles:
  - name: check_folders
    src: https://github.com/samirparhi-dev/ansible_check_create_folders_files.git
    scm: git
    version: main
```

add below content in `meta/main.yml`
```
---
dependencies:
  - name: <<Name of the Role>>
```

It should be available now for consuption
