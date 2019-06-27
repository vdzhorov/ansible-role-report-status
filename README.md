# report-status

Role used for getting reports from remote machines to the local ansible host.

## Getting Started

No parameters needed to set beforehand. Just run the role like so:

```ansible-playbook -i '<IP>,' playbooks/repot-status.yml && cat /tmp/report.txt && rm -f /tmp/report.txt```

### Prerequisites

No prerequisites required

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## License

This project is licensed under the MIT License.

## Company
* **Delta.BG**

## Acknowledgments

* Needed quick tool for dignosing problems so this simple role was born.
