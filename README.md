## Darwinia/Crab Network XCMP Cooperations
> Check [`parachain-info.toml`](parachain-info.toml) for more information about the Darwinia parachains.

### Cooperation Process
**Contract our developers or fork this repository and do the following things:**
1. Edit the [`xcmp-coops.toml`](xcmp-coops.toml)
2. Find your cooperation target, Darwinia or Crab network
3. Add an new item follow the existing items format
4. Fill the accept/batch/request call data
5. Make a pull request
6. Once the pull request gets more than one approvals, the on-chain governance will be started
7. Once the channel(s) was(were) established, update the result(s) with the Subscan or Polkadot Apps URI(s)
8. Once all the things above are finished, the pull request will be merged

**Some formatting issues:**
1. Sort the network list by alphabetic order
2. If the field you don't use, just leave with an empty string `""`
3. Convert your network's name to lowercase, e.g. `"Foo" -> "foo"`
4. Convert your network's name style to kebab-case, e.g. `"FooBar", "fooBar", "FOO_BAR", "foo_bar" -> "foo-bar"`
5. Replace the space in your network name with a dash, e.g. `"foo bar" -> "foo-bar"`
