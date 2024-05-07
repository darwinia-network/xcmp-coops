## Darwinia/Crab Network XCMP Cooperations
> For detailed information about the Darwinia parachains, refer to the [`parachain-info.toml`](parachain-info.toml) file.

### Cooperation Process
**To collaborate with our developers or contribute directly, follow these steps:**
1. Modify the [`xcmp-coops.toml`](xcmp-coops.toml) file.
2. Identify your target for cooperation, either Darwinia or Crab Network.
3. Add a new entry following the format of existing items.
4. Complete the accept/batch/request call data fields.
5. Submit a pull request.
6. After your pull request receives at least one approval, on-chain governance will commence.
7. Once the channels are established, update the results with the Subscan or Polkadot Apps URI(s).
8. After completing the above steps, your pull request will be merged.

**Formatting guidelines:**
1. Arrange the network list in alphabetical order.
2. Leave unused fields as an empty string `""`.
3. Convert your network's name to lowercase, e.g., `"Foo" -> "foo"`.
4. Change your network's name to kebab-case, e.g., `"FooBar", "fooBar", "FOO_BAR", "foo_bar" -> "foo-bar"`.
5. Replace spaces in your network name with a dash, e.g., `"foo bar" -> "foo-bar"`.
