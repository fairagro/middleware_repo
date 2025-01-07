# Schema.org issues

**Note:** Issues to be solved by the repository (where possible) are listed in the columns `Schema.org` and `ARCtrl (ro-crate)`. Specific issues will be created using the GitHub issues system and assigned to the responsible person.

| Repository | Schema.org | ARCtrl (ro-crate) | Gitlab |
| ----- | ----- | ----- | ----- |
| e\!DAL |  | from type `Person` only creators are recognized.  `Address` spected as string Missing `identifier` property | invalid characters in repo name |
| Bonares |  | `identifier` is a list (position 0 hash, position 1 DOI, most of the cases). Author different type `Organization` `contactPoint`   | invalid characters in repo name |
| OpenAgrar |  | `description` is a list (position 0 most of the times empty) `identifier` is a list of dict sometimes no doi or other id, only refers as intern id | invalid characters in repo name |
| Publisso | No schema.org, use publisso schema in JSON-LD vocabulary |  | invalid characters in repo name |
| Thünen Atlas | No schema.org or JSON-LD | authors in the dataset refers only the admin as creator, only internal ids | invalid characters in repo name |
