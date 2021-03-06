.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``comment``
     - |comment user| Default value: ``nil``.
   * - ``gid``
     - |id group| Default value: ``nil``.
   * - ``home``
     - |home_directory| Default value: ``nil``.
   * - ``password``
     - |password shadow_hash| Default value: ``nil``.
   * - ``provider``
     - Optional. |provider resource_parameter|
   * - ``shell``
     - |shell| Default value: ``nil``.
   * - ``supports``
     - |supports user| Default value: ``:manage_home => false, :non_unique => false``.
   * - ``system``
     - |system user| Default value: ``nil``.
   * - ``uid``
     - |user uid| Default value: ``nil``.
   * - ``username``
     - |name user| Default value: the ``name`` of the resource block (see Syntax section above).