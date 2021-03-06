# ππ¦Μπͺπ¦π°

ππ¦Μπͺπ¦π° is a collaborative βfilesystemβ for [IPFS](//ipfs.io) resources. It varies from a traditional directory tree in the following ways:

* **Context Forest:** In a regular filesystem, each file exists at a single point in the tree. In ππ¦Μπͺπ¦π° *every* reasonable path for a resource resolves.
* **Pathsets:** When searching through resources, rather than a single path, the user can specify combinations of paths, and display elements that are common between them.
* **Collaborative Filter:** In ππ¦Μπͺπ¦π°, each user's additions are saved to their own subforest. These are traversed en masse to find which resources were the most often referenced to gauge popularity for competitive spaces like `/news/interesting/` where lots of content wants to have the top spots.
* **Native Collections:** Folders may contain multiple resources with the same name.