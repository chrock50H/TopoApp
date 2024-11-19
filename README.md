## TopoApp

---

### Only a Front-End, the idea is

TopoRemedialAction / Gridstatealteration

- Generate Testdata for CGMES (NetworkCodeProfiles)
- Exchange of Scenario-Parameters used in Backoffice Calculations through randomized (hashed) DifferenceModels, which send no critial Grid Data and instead can reproduced locally by a TSO.
- should easy to store, load all kinds of timeseries and have an UI that can be adopted to different Set of needed buttons/parameters..
- 2-3 Wireframes for <complextyp>> BusbarCoupler or PST[crossborderrelevant]
 
Grid-View should have 1:1 correspondance to for Topo-Nodes, and each Element from Flat List can be highlighted for each user individually, and still be displayed as a merged Set in one color per border for the RCC View. 

Adhoc changes or new Overloads on overlapping XNE then could could be agaien identical colors for TSO, TSO and RCC Operator (same for TSO-DSO Interface).

Backoffice Implementation continous in python, some other options might follow. Like Oracle Java 1.8 LTS Runtime or a idealerly a containerized Webassembly/Rust parsing-script using JavaScript together with a signed Template.
A second Container (docker image) which can be exchanged and maintained by local IT wrappd around, establishing modular deployment bei TSO IT and still providing Interoperability in terms of used operating system in a Sandboxed offline environment.
