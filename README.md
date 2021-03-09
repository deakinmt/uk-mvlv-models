# uk-mvlv-models
Hybrid European MV-LV Models for Smart Distribution Network Modelling - unbalanced distribution network models for testing the scalability of smart controls and considering impacts of flexibility, accounting for MV level coupling and heterogeneous LV circuit models.

The uses of the models could include modelling/control of 
* Smart Local Energy Systems, 
* Virtual Power Plants, 
* Peer-Peer Trading Platforms, 
* TSO-DSO,

and so on. The models were built by allocating [LVNS LV circuits](https://www.enwl.co.uk/zero-carbon/innovation/smaller-projects/low-carbon-networks-fund/low-voltage-network-solutions/) to the loads of the [UKGDS MV ('HV') circuits](https://github.com/sedg/ukgds). The models are provided in the OpenDSS '.dss' format.

![mv-lv-modelling](https://user-images.githubusercontent.com/30076553/110505081-bbbcfd80-80f5-11eb-96c4-85bda139c886.png)

If you use these models in your work, please could they be referenced as

"*Hybrid European MV-LV Network Models for Smart Distribution Network Modelling*", M. Deakin, D. Greenwood, S. Walker and P. C. Taylor, (accepted for presentation at IEEE Powertech 2021).
Preprint: http://arxiv.org/abs/2009.14240

The work was funded by the Supergen Energy Networks hub, EPSRC grant no. EP/S00078X/1.

Comments & feedback welcome!

---

The _UG MV network_ topology and demand is as follows (demands are prior to LV network allocation - see full paper for details):

![plotNetwork_HV_UG_s](https://user-images.githubusercontent.com/30076553/110504112-bf9c5000-80f4-11eb-86d5-72ee4db965c8.png)

Similarly, the _UG-OHa MV network_ topology and demand are as here:

![plotNetwork_HV_UG-OHa_s](https://user-images.githubusercontent.com/30076553/110504130-c4610400-80f4-11eb-953a-e31978e3b8c6.png)


