
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

 .. NOTE! THIS FILE IS AUTOMATICALLY GENERATED AND WILL BE
    OVERWRITTEN WHEN PREPARING PACKAGES.

 .. IF YOU WANT TO MODIFY THIS FILE, YOU SHOULD MODIFY THE TEMPLATE
    `PROVIDER_COMMITS_TEMPLATE.rst.jinja2` IN the `dev/breeze/src/airflow_breeze/templates` DIRECTORY

 .. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!

Package apache-airflow-providers-ydb
------------------------------------------------------

`YDB <https://ydb.tech/>`__


This is detailed commit list of changes for versions provider package: ``ydb``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.1.0
.....

Latest change: 2024-12-19

=================================================================================================  ===========  =====================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =====================================================================
`088242a911 <https://github.com/apache/airflow/commit/088242a911ba52f16a8c97df0d6dcb7e47ca1b73>`_  2024-12-19   ``Update Example URL in YDB docs (#45033)``
`4b38bed76c <https://github.com/apache/airflow/commit/4b38bed76c1ea5fe84a6bc678ce87e20d563adc0>`_  2024-12-16   ``Bump min version of Providers to 2.9 (#44956)``
`1275fec92f <https://github.com/apache/airflow/commit/1275fec92fd7cd7135b100d66d41bdcb79ade29d>`_  2024-11-24   ``Use Python 3.9 as target version for Ruff & Black rules (#44298)``
`4dfae23532 <https://github.com/apache/airflow/commit/4dfae23532d26ed838069c49d48f28c185e954c6>`_  2024-11-15   ``Update DAG example links in multiple providers documents (#44034)``
=================================================================================================  ===========  =====================================================================

2.0.0
.....

Latest change: 2024-11-14

=================================================================================================  ===========  ========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================
`a53d9f6d25 <https://github.com/apache/airflow/commit/a53d9f6d257f193ea5026ba4cd007d5ddeab968f>`_  2024-11-14   ``Prepare docs for Nov 1st wave of providers (#44011)``
`e7194dff6a <https://github.com/apache/airflow/commit/e7194dff6a816bf3a721cbf579ceac19c11cd111>`_  2024-11-13   ``Add support for semicolon stripping to DbApiHook, PrestoHook, and TrinoHook (#41916)``
`cf3d55d8ed <https://github.com/apache/airflow/commit/cf3d55d8ed7524cd073b8d7ce3c2d8fd57043348>`_  2024-11-12   ``Migrate YDB Operator to new DBAPI (#43784)``
`857ca4c06c <https://github.com/apache/airflow/commit/857ca4c06c9008593674cabdd28d3c30e3e7f97b>`_  2024-10-09   ``Split providers out of the main "airflow/" tree into a UV workspace project (#42505)``
=================================================================================================  ===========  ========================================================================================

1.4.0
.....

Latest change: 2024-10-09

=================================================================================================  ===========  ====================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================
`2bb8628463 <https://github.com/apache/airflow/commit/2bb862846358d1c5a59b354adb39bc68d5aeae5e>`_  2024-10-09   ``Prepare docs for Oct 1st adhoc wave of providers (#42862)``
`3c4fbce5d6 <https://github.com/apache/airflow/commit/3c4fbce5d621e1e701a9a8574e50844821de37d4>`_  2024-10-03   ``Add an ability to use scan queries via new YDB operator (#42311)``
=================================================================================================  ===========  ====================================================================

1.3.0
.....

Latest change: 2024-08-19

=================================================================================================  ===========  ====================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================================
`75fb7acbac <https://github.com/apache/airflow/commit/75fb7acbaca09a040067f0a5a37637ff44eb9e14>`_  2024-08-19   ``Prepare docs for Aug 2nd wave of providers (#41559)``
`6e22364278 <https://github.com/apache/airflow/commit/6e223642780799e7b726eff6e307f2d270b9c689>`_  2024-08-14   ``ydb provider: add database to table name in bulk upsert, use bulk upsert in system test (#41303)``
`fcbff15bda <https://github.com/apache/airflow/commit/fcbff15bda151f70db0ca13fdde015bace5527c4>`_  2024-08-12   ``Bump minimum Airflow version in providers to Airflow 2.8.0 (#41396)``
=================================================================================================  ===========  ====================================================================================================

1.2.0
.....

Latest change: 2024-08-03

=================================================================================================  ===========  ============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================
`d23881c648 <https://github.com/apache/airflow/commit/d23881c6489916113921dcedf85077441b44aaf3>`_  2024-08-03   ``Prepare docs for Aug 1st wave of providers (#41230)``
`bef82d6ab3 <https://github.com/apache/airflow/commit/bef82d6ab38d627dc1b42981c90b9f8d36852f4c>`_  2024-07-19   ``Clean up remaining getattr connection DbApiHook (#40665)``
`51f334f27c <https://github.com/apache/airflow/commit/51f334f27c4f4ce1e4e2d347955033e170c25716>`_  2024-07-11   ``ydb provider: add bulk upsert support (#40631)``
=================================================================================================  ===========  ============================================================

1.1.0
.....

Latest change: 2024-07-09

=================================================================================================  ===========  ========================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================
`09a7bd1d58 <https://github.com/apache/airflow/commit/09a7bd1d585d2d306dd30435689f22b614fe0abf>`_  2024-07-09   ``Prepare docs 1st wave July 2024 (#40644)``
`91e6e6055b <https://github.com/apache/airflow/commit/91e6e6055b3241aae7e1593bd9b855682c733e7d>`_  2024-06-27   ``support auth key from content and from file (#40390)``
=================================================================================================  ===========  ========================================================

1.0.0
.....

Latest change: 2024-06-22

=================================================================================================  ===========  ============================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================
`6e5ae26382 <https://github.com/apache/airflow/commit/6e5ae26382b328e88907e8301d4b2352ef8524c5>`_  2024-06-22   ``Prepare docs 2nd wave June 2024 (#40273)``
`161fd5573f <https://github.com/apache/airflow/commit/161fd5573fd9e52b270359fb794b3dfeee7d701c>`_  2024-06-15   ``add new YDB provider (#39996)``
=================================================================================================  ===========  ============================================
