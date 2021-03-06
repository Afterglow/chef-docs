=====================================================
About the Hosted Server
=====================================================

.. include:: ../../includes_chef/includes_chef_hosted.rst

Hosted |chef server oec| is based on the idea that an infrastructure management tool should be built around a collection of API primitives. By using an API to talk to a cloud provider (such as |amazon vpc|, |windows azure|, or |rackspace|), it allows the freedom to think of those primitives as building blocks. The |chef client| only needs to know about the desired state, how it should get there, and what the proper functionality of that desired state should be.