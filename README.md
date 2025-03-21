Ansible Basics

    **Agentless:** Unlike other configuration management tools (e.g., Puppet, Chef), Ansible does not require agents on managed nodes. It uses SSH for Linux and WinRM for Windows.
    **Declarative Syntax:** Uses YAML-based playbooks to define desired system states.
    **Idempotency:** Ensures that running the same playbook multiple times produces the same result without causing unintended changes.

Core Components

  1. Inventory: Defines target hosts (/etc/ansible/hosts or dynamic inventories from cloud providers).
  2. Modules: Built-in functions for tasks (e.g., copy, yum, apt, user, service).
  3. Tasks: Individual actions performed in playbooks.
  4. Playbooks: YAML files defining tasks and roles for automation.
  5. Roles: A structured way to organize playbooks (tasks, handlers, templates, etc.).
  6. Handlers: Special tasks triggered when a change occurs (e.g., restarting a service).

    
