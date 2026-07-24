# asInBundle

prov:asInBundle is used to specify which bundle the general entity of a prov:mentionOf property is described.

When :x prov:mentionOf :y and :y is described in Bundle :b, the triple :x prov:asInBundle :b is also asserted to cite the Bundle in which :y was described.

**Domain**: [Entity](../classes/Entity.md)

**Range**: [Bundle](../classes/Bundle.md)

**IRI**: `http://www.w3.org/ns/prov/asInBundle`
