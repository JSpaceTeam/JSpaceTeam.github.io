**Working On:**

Generating the ApiDummy.scala and MappingDummy.scala.

**Doubts**: 
-Both interfaces and system are defined as containers in the yang file. How to decide which one needs a table and which one doesnt?
-Facing this issue from a template perspective.

**Scenario**:
```
object DeviceQueryDummy extends YangMappingQueryDSL {
  mapping(_ => new Device)
  select("device.dm_id") mapping "id"
  select("device.dm_domainId") mapping "domainId"
  select("device.dm_system_hostname") mapping "system/hostname" **//system is defined as a container in the yang file**
  cascade(InterfacesQueryDummy) mapping "interfaces" jointField "id" as "deviceId" **//interfaces is defined as a container in the yang file**
  from("device device")
  postProcess{
    (apiCtx, result) =>
  }
}
```
How to identify when to make a cascade and when to do mapping like "system/hostname" while parsing.

**Update 12/3/2014**

Resolved earlier doubts and proceeding with the *dummy.scala template implementations.


