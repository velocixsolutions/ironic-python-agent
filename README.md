# ironic-python-agent
Ironic Python Agent


Overview
========

An agent for controlling and deploying Ironic controlled baremetal nodes.

The ironic-python-agent works with the agent driver in Ironic to provision
the node.  Starting with ironic-python-agent running on a ramdisk on the
unprovisioned node, Ironic makes API calls to ironic-python-agent to provision
the machine.  This allows for greater control and flexibility of the entire
deployment process.

The ironic-python-agent may also be used with the original Ironic pxe drivers
as of the Kilo OpenStack release.


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
