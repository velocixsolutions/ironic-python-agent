===================
Ironic Python Agent
===================


.. image:: https://governance.openstack.org/tc/badges/ironic-python-agent.svg
    :target: https://governance.openstack.org/tc/reference/tags/index.html

Clone of official `ironic-python-agent` repository: https://github.com/openstack/ironic-python-agent 
This has a patch fix to skip partition validation step due to a Open Bug for Gen10 hardware.

BUG link: https://storyboard.openstack.org/#!/story/2005772


Patch applied on `ironic-python-agent/extensions/standby.py` file.
Official repository file: https://github.com/openstack/ironic-python-agent/blob/master/ironic_python_agent/extensions/standby.py#L591
Patched version: https://github.com/velocixsolutions/ironic-python-agent/blob/master/ironic_python_agent/extensions/standby.py#L591

This patch is hosted until next release of `ironic-python-agent` is released with a fix for the above mentioned open bug.


Project Resources
=================
Project status, features, and bugs are tracked on StoryBoard:

  https://storyboard.openstack.org/#!/project/947

Developer documentation can be found here:

  https://docs.openstack.org/ironic-python-agent/latest/

Release notes for the project are available at:

  https://docs.openstack.org/releasenotes/ironic-python-agent/

Source code repository for the project is located at:

  https://opendev.org/openstack/ironic-python-agent/
