





# App Tracking Networks

This repository contains two bipartite graphs: A network of companies `companies.txt` and a network of domains `domains.txt`.

These networks were created from the [Lumen dataset](https://zenodo.org/record/3560420), containing details of `10 546 774` network transmissions from `48 717` apps.

The networks are provided as `nodelists` in the `TSV` (tab-separated values) format. In every line of the files, the first entry in the `TSV` file indicates the app, the other the contacted domain respectively company by the app.

These `nodelists` are compatible with the network analysis software `UCINET`, but can easily be transformed into other network file formats.

The company names were obtained using the [Disconnect list](https://github.com/disconnectme/disconnect-tracking-protection) of tracking companies and their respective domains.

![Company Network](company_network.png)

Company network, with node size indicating occurrence in apps and edge size co-occurrence in apps.



![Domain Network](domain_network.png)

Domain network, with node size indicating occurrence in apps and edge size co-occurrence in apps.