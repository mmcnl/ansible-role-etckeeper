## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: etckeeper
          vars:
            etckeeper_task_codename: etc
            etckeeper_target_dir: /etc
            etckeeper_gitignore_additions: |
              ufw/user.rules

## License

MIT

