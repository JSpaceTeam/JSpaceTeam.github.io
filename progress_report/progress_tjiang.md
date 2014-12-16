**12/16/2014**

1. Finished evaluation of JNC from tail-f and presented to both US team and china team.
2. Start looking at NACM (Netconf Access Control Model: RFC-6536 [https://tools.ietf.org/html/rfc6536])

**Next Week**

1. Update js-easy-rest SBT build to generate java code via JNC
2. Continue mapping NACM to Space ACM and Contrail ACM 

**Need help:**

========================================

**12/08/2014**

1. Mapped RESTCONF GET methods on vnc_cfg.yang
2. Met with Contrail and ProjectQ team on YANG representation of Contrail IFMAP data model semantics and got back positive feedback.
3. Refractored the vnc_cfg.yang to abstract out the base YANG modules (acm, ifmap, common, etc) based on the feedback from Contrail and ProjectQ team
4. Evaluated jnc from tail-f as the java library for YANG data model (https://github.com/JSpaceTeam/JNC)
5. Evaluating Hitachi YANG south-bound support

**Next Week**

1. Work with Juntao on POC on top of tail-f JNC (integrating JNC with js-easy-rest)
2. Work with Shin Ma on YANG definition of device management and inventory management

**Need help:**

Need Juntao's help on integrating tail-f JNC

**Action Items**

1. Write up meeting notes on RBAC brainstorm meeting (overdue)
2. Write up meeting notes on SlipStream (overdue)
3. Write up meeting notes with Contrail (overdue)

========================================

**12/02/2014**

1. ER diagram of Contrail data model (vnc_cfg.xsd)
2. Completed the conversion of Contrail data model xsd to YANG and shared with Kent, Contrail, and ProjectQ team
3. Worked with Kent on the slide deck about high level migration strategy to JUNOS IQ platform.

**Next Week**

1. Finalizd the YANG mapping of Contrail data model semantics with Contrail team and ProjectQ team
2. TOI to the team on writing YANG model with Contrail data model semantics
3. RESTCONF mapping and work with Shin Ma on the defining the YANG model needed for device ILP

**Need help:**

**Action Items**

1. Write up meeting notes on RBAC brainstorm meeting (overdue)
2. Write up meeting notes on SlipStream (overdue)
3. Write up meeting notes with Contrail (overdue)
