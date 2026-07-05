# Ansible

* [documentation](https://github.com/dancer1325/ansible-collaborative)

## Design Principles

* SIMPLE setup process / minimal learning curve
* Manage machines 
  * quickly
  * in parallel
* agentless
  * == ❌NO need custom-agents❌ 
* use the existing SSH daemon
  * WITHOUT NEED opening ADDITIONAL ports
* Describe infrastructure -- via a -- language /
  * machine-friendly
  * human-friendly
* security + easy auditability/review/rewriting of content
* Manage NEW remote machines instantly
  * WITHOUT bootstrapping any software
* enable module development | any dynamic language
* usable -- as -- non-root

## how to use Ansible?

* [latest release](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
* "devel" branch
  * == default Git branch 
  * the latest features & fixes

## Communication

* [here](https://docs.ansible.com/ansible/devel/community/communication.html)

## Branch Info

* The `devel` branch corresponds to the release actively under development.
* The `stable-2.X` branches correspond to stable releases.
* Create a branch based on `devel` and set up a [dev environment](https://docs.ansible.com/ansible/devel/dev_guide/developing_modules_general.html#common-environment-setup) if you want to open a PR.
* See the [Ansible release and maintenance](https://docs.ansible.com/ansible/devel/reference_appendices/release_and_maintenance.html) page for information about active branches.

## Roadmap

* initial roadmap 
  * is published / EACH major OR minor version
* [Ansible Roadmap page](https://docs.ansible.com/ansible/devel/roadmap/)
