.. Licensed to the Apache Software Foundation (ASF) under one
   or more contributor license agreements.  See the NOTICE file
   distributed with this work for additional information#
   regarding copyright ownership.  The ASF licenses this file
   to you under the Apache License, Version 2.0 (the
   "License"); you may not use this file except in compliance
   with the License.  You may obtain a copy of the License at
   http://www.apache.org/licenses/LICENSE-2.0
   Unless required by applicable law or agreed to in writing,
   software distributed under the License is distributed on an
   "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
   KIND, either express or implied.  See the License for the
   specific language governing permissions and limitations
   under the License.
   

What's New in |version|
=======================

Version |release| includes 180 pull requests and fixes more than 80 bugs since
the 4.9.0 release.

The 4.9.2.0 is part of the LTS 4.9.x releases. The 4.9 LTS branch is supported
for 20 months, and will receives updates for first 14 months and only
security updates in its last 6 months. The 4.9 LTS branch is supported till 1
June 2018.

A LOT changed in this release, so this is not a complete list, but here is a 
quick summary of some of the changes.


Networking
----------

* Fixes to ACLs, S2S VPN, Private Gateways, Redundant VRs and other optimizations
* Nuage VSP SDN Plugin got a lot of improvements and some new features


Database
--------

* MySQL connector changed
* DB optimizations and improvements


Storage
-------

* Enabled fast snapshots for managed storage using XenServer
* Fixes for some RBD issues
* Fixes multiple Swift object store issues
* Improved VMware disk implementation


Hypervisor
----------

* Support for XenServer 7
* Support for VMware vSphere 6.0, 6.5
* Support for Ubuntu 16.04 as KVM host


Usability
---------

* Added user defined roles
* Added configurable root volume size for KVM
* Lots of localization improvements
* Added CentOS 6.x guest OS mappings for VMware


Operations
----------

* Added Out-of-band power management for hosts (EG: IPMI, iLO, DRAC, etc.)


Miscellaneous
-------------

* Use non-blocking SSL handshake in NioConnection/Link
* Added memory utilization to ``listVirtualMachines``
* Multiple fixes related to usage


QA
--

* Higher quality releases due to better QA automation, testing and code reviewing

Build dependency
----------------

When building Apache CloudStack with ``noredist``, it now require the file
``deps/vim25_60.jar`` available from vSphere SDK 6.0,
VMware-vSphere-SDK-6.0.0-3634981.zip.

