## Démonstration *ansible-pull*

### Préparation du client

* **Prérequis logiciels**
  * `git`

* **Installation minimale de ansible**

  ```
  pipx install ansible-core
  ```

  **Remarque**

    Selon les modules des playbooks, il peut être nécessaire d'effectuer des installations supplémentaires.

### Exécution de `ansible-pull`

```
ansible-pull -U https://github.com/bob2204/ansible-pull playbook-pull.yml
```
