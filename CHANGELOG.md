# @svizzle/atlas v0.8.0

- convert all JSON assets to javascript files, to avoid importing `.json`,
which is not officially supported in ESM yet

# @svizzle/atlas v0.6.0

- Add NUTS unified ids and hierarchy (#9)
- NUTS, add parent ids to `hierarchy.json` (#10)
- NUTS, add `rootId` (#12)
- NUTS, add resolution `10M`, update some texts in `3M` files (#14)
- NUTS, enhance distributed files (#16)
	- `unifiedNuts.json`: `year` is now a `Number`
	- `hierarchy.json`: `id` is now a `Number`
