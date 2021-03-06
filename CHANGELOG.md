# CloudFoundry Persistence Service Broker Version Log
## v1
vccfe2a3622428bd93521f0b6ce8fbb0116b3413f Initial Commit With CI
## v2
v8cee9155abeb71d0f38359f2c834240f21461ea1 Resolve depencies problem on libstorage by deleting api/server, import/routers, and api/tests folders
## v3
v39a8ed044f1e16e21c78182f36b711ca2163b1a2 Fix integration test script
## v4
vbdfe5338002907e8638c1aa94ddce01257000efd Add bind, unbind, deprovision, provision into service broker
## v5
vbad235205fce7458ec536602ceb2bc624342c4a8 Modified catalog and binding for service broker to match that of cf-scaleio-broker
## v6
v5b20ade2d236ecea4b628aad0a8efefcc6a4e9a4 Change service broker to use volumeName for Binding
## v8
v88dc765d825417ce657ada3be5c43330f351d2a1 Reuse service broker instance from lifecycle test
## v9
va5ed98d54ea2e083e4cfc1bdfd5f95746d54e827 Change to non-interactive for delete app
## v10
v2d5fe573ecbf0eb974b9167f4cc4a13db54e6a87 Change delete app to restage app
## v11
v48f8eb128e036f37b15c2a489abab31101dfbe35 Combine acceptance tests to lifecycle
## v12
vde0ffcd82e6956aca93b5422e5db52ed3d0cb60e Changed EMC-CMD to EMC-Dojo
## v13
v710575ae06bd28fcfa28699d705e3999cda85376 Add configure persistence docs
## v14
vd043756be46d96a5d9f8d1dd038206cc5b0a5c46 copy README.md inside docs folder
## v15
v49339eb278b1e73c2bf389896ac8764d3743683b Format configure persistence document
## v16
v94e735020a0f7cdefed34de1eea487604ce266d3 Error handling for delete service instance when service is still attached to App [#121134559](https://www.pivotaltracker.com/story/show/121134559)
## v17
v1fdbc21b77cc0064eba43f82bc970731f4472e05 Adding unbind service to lifecycle step of Pipeline
## v18
v7ff5dc1dd8cdb8544f6300be65f4cb4fa6ea295e Created new block in pipeline for releasing new candidate
## v21
v9382e197f2ebb934f551330dcb00324bb96d5d5e Create New Diego Cells for multiple cell testing of persistence driver
## v25
v761c1f9aeddb2c842d8ee08147b7bdb8ea5aa581 Extract scale diego cell out from isilon lifecycle
## v
vdb87a13feb1671a209481235fc9f670e967cd627 Make promote script reusable
## v
vc811e7c7506888cf5bad43d1650ae16b393f2234 Add promote rexray and scaleio sdc release
## v
v251e8759eb2fc511f4e313b98a9e7d9fb8cc02bb Merge pull request #1 from linlynn/master
## v38
543cc67 Rename scaleio-sdc release to scaleio
## v40
0ab740c Fix isilon lifecycle bug
## v41
98d6f12 Fix cell deployment doesn't get right version of releases
## v42
9bc1173 Added sequence change for versioning
## v43
1ec10eb Diego release is now called diego
## v44
c77cc79 changed readme
## v45
c451fc7 Remove unused ruby code
## v46
219d213 Fix typo
## v47
c3ac9d7 Added documentation for PCF Tile/Open Source
## v48
124add6 Few Doc Updates/Clarifications
## v49
6364e07 Allow broker to accept volume size in GB
## v50
7b43853 Fix Size Bug: global variable issue
