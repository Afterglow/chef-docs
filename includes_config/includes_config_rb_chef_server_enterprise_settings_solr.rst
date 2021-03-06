.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The |service solr| service has the following settings:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``opscode_solr['commit_interval']``
     - Default value: ``60000``.
   * - ``opscode_solr['data_dir']``
     - The directory in which the index data for |apache solr| is located. Default value: ``/var/opt/chef-server/chef-solr/data``.
   * - ``opscode_solr['dir']``
     - Default value: ``/var/opt/chef-server/chef-solr``.
   * - ``opscode_solr['enable']``
     - |enable service| Default value: ``true``.
   * - ``opscode_solr['ha']``
     - |use ha| Default value: ``false``.
   * - ``opscode_solr['heap_size']``
     - |heap_size solr| The default value should work for many organizations with fewer than 25 nodes. For an organization with several hundred nodes, the amount of memory that is required often exceeds 3GB. Default value: ``nil``.
   * - ``opscode_solr['ip_address']``
     - Default value: ``127.0.0.1``.
   * - ``opscode_solr['java_opts']``
     - Default value: ``(empty)``.
   * - ``opscode_solr['log_directory']``
     - |directory logs| The default value is the recommended value. Default value: ``/var/log/chef-server/chef-solr``.
   * - ``opscode_solr['max_commit_docs']``
     - Default value: ``1000``.
   * - ``opscode_solr['max_field_length']``
     - Default value: ``100000``.
   * - ``opscode_solr['max_merge_docs']``
     - The maximum number of index segments allowed before they are merged into a single index. Default value: ``2147483647``.
   * - ``opscode_solr['merge_factor']``
     - The maximum number of document updates that can be stored in memory before being flushed and added to the current index segment. Default value: ``100``.
   * - ``opscode_solr['new_size']``
     - Default value: ``nil``.
   * - ``opscode_solr['poll_seconds']``
     - Default value: ``20``.
   * - ``opscode_solr['port']``
     - |port opscode_solr| Default value: ``8983``.
   * - ``opscode_solr['ram_buffer_size']``
     - Default value: ``200``.
   * - ``opscode_solr['svlogd_size']``
     - |svlogd_size| Default value: ``1000000``.
   * - ``opscode_solr['svlogd_num']``
     - |svlogd_num| Default value: ``10``.
   * - ``opscode_solr['url']``
     - Default value: ``"http://localhost:8983"``.
   * - ``opscode_solr['vip']``
     - |ip_address virtual| Default value: ``127.0.0.1``.





