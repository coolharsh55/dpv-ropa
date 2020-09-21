# Extending Data Privacy Vocabulary (DPV) to represent ROPA

The Register of Processing Activity (ROPA) is a set of information required to be maintained by Data Controllers under the General Data Protection Regulation (GDPR). The ROPA contains information about the processing activities of the Controller which is then useful to in the compliance maintainence and evaluation process by Data Protection Officers and Data Protection Authorities (DPA).

The work presented here extends the [DPV](https://www.w3.org/ns/dpv) vocabulary with concepts required to represent ROPAs. The ROPA concepts are taken from a common semantic model derived from the analysis of templates provided by EU DPAs.

The concepts proposed for incorporation in to the DPV are present in [dpv-ropa.ttl](./dpv-ropa.ttl) with some additional concepts requiring discussion mentioned in [discussion.md](./discussion.md). The file `dpv.ttl` is a copy of DPV included for brevity.

For a general description of the concepts and their basis in ROPA templates provided by EU regulators, please see our working paper [Towards a Semantic Model of the GDPR Register of Processing Activities](https://arxiv.org/abs/2008.00877).