
<!-- some hacks to hide the table of contents and make the links sidebar smaller, 
so the table has more screen real estate -->
<style>
.md-sidebar--secondary:not([hidden]){
  display: none 
}

.md-sidebar {
    width: 8rem
}

.copy-path-btn {
  margin: 0.15rem 0.3rem 0.15rem 0;
  padding: 0.15rem 0.5rem;
  font-size: 0.65rem;
  white-space: nowrap;
  cursor: pointer;
  border: 1px solid var(--md-default-fg-color--lighter);
  border-radius: 0.2rem;
  background: var(--md-code-bg-color);
  color: var(--md-default-fg-color);
}

.copy-path-btn:hover {
  border-color: var(--md-accent-fg-color);
}

</style>

<script>
function copyDatastorePath(path, btn) {
  navigator.clipboard.writeText(path).then(function () {
    var original = btn.textContent;
    btn.textContent = 'Copied!';
    setTimeout(function () { btn.textContent = original; }, 1500);
  });
}
</script>

# ACCESS-CM3 Experiments

The below lists key experiments that are being used to improve, evaluate and drive development for CM3. We welcome scientific and technical feedback on these runs. If you would like to get involved in evaluation of these runs, see instructions [here](https://github.com/acCESS-Community-Hub/access-cm3-paper-1/) and an overview [here](/contributing/#help-us-evaluate-and-improve-applications-of-cm). 

The below data is from unreleased configurations, and there is no guarantee that it will be available or re-producible long-term. Note that all experiments use constant forcing and that year numbers are essentially meaningless.

In CM3 experiments ocean initial conditions are taken from a "cold start" in ACCESS-OM3 (e.g., WOA2023 January).

This data, and the configurations they are based on, are licensed by 
[CC-by-4.0](https://creativecommons.org/licenses/by/4.0/) and therefore can be freely shared, 
distributed and modified. Users of ACCESS-NRI models, data, tools or expert support are required
 to clearly include an [acknowledgement](https://www.access-nri.org.au/resources/acknowledging-us/)
  in all publications/reports/public releases.

| Base Configuration                                                                                                  | Date completed | Description                                                                                                                                                                                                                                                             | Model build                                                                                                                                                                        | Length (years) | ESM Datastore  <br/>  (output path)                                                                                          |
|---------------------------------------------------------------------------------------------------------------------|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----|------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                     |                | CM3 present day control run.                                                                                                                                                                                                                                            | NA                                                                                                                                                                                 | 50 | <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-11-08-2025-25km-beta-om3-new-um-params/cm3-demo-datastore/cm3-demo-datastore.json', this)">Copy JSON path</button> <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-11-08-2025-25km-beta-om3-new-um-params/cm3-demo-datastore/cm3-demo-datastore.csv', this)">Copy CSV path</button> |
| [access-cm3-config](https://github.com/ACCESS-NRI/access-cm3-configs/tree/7c544cc2bfce97d28cf877b63620a6757a2aa273) | 17/03/2026     | CM3 present day control run. This run features updated OM3 components, pseudo-iceberg fluxes, and a more accurate wind stress remapping.                                                                                                                                | [UM](https://github.com/ACCESS-NRI/UM/tree/3ed9cb65e997b4453ee362f73876db2cb6b62036) [OM3](https://github.com/ACCESS-NRI/ACCESS-OM3/tree/a5b511da9573b106c3a98dc16e3b9668bfb597f1) | 100 | <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-20-01-2026-om3-update/cm3-datastore/cm3-datastore.json', this)">Copy JSON path</button> <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-20-01-2026-om3-update/cm3-datastore/cm3-datastore.csv', this)">Copy CSV path</button> |
| [access-cm3-config](https://github.com/ACCESS-NRI/access-cm3-configs/tree/cm3-run-03-06-2026)                       | 29/06/2026     | CM3 present day control run. This run features pseudo-iceberg melt fluxes spread according to a monthly climatologally (both basal and calving), improved atmosphere sea-ice windstress calculations, and includes meltponds (erroneously turned off in the previous run). | [UM](https://github.com/ACCESS-NRI/UM/tree/6e401a69402e603c21de607f617fa7951f18051e) [OM3](https://github.com/ACCESS-NRI/ACCESS-OM3/tree/f5d40a69fd31052448b80b157e37d361118092ff) | 50 | <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-03-06-2026/cm3-datastore/cm3-datastore.json', this)">Copy JSON path</button> <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-03-06-2026/cm3-datastore/cm3-datastore.csv', this)">Copy CSV path</button> |
| [access-cm3-config](https://github.com/ACCESS-NRI/access-cm3-configs/tree/cm3-run-27-07-2026-PD-control)                       | 17/08/2026     | CM3 present day control run. This run uses the GC5-central UM configuration, CMIP6 inputs, and includes several polar and tripolar bugfixes.                                                                                                                            | [UM](https://github.com/ACCESS-NRI/UM/tree/5491e5542e3f2f3fe828e0fbd3aa308c2baa8ea1) [OM3](https://github.com/ACCESS-NRI/ACCESS-OM3/tree/e1fc2a885bfd0740b9ae2b7a5e41482077397023) | 50 | <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-27-07-2026-PD-control/cm3-datastore/cm3-datastore.json', this)">Copy JSON path</button> <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-27-07-2026-PD-control/cm3-datastore/cm3-datastore.csv', this)">Copy CSV path</button> |
| [access-cm3-config](https://github.com/ACCESS-NRI/access-cm3-configs/tree/cm3-run-27-07-2026-PI-control)                       | 18/08/2026     | CM3 pre-industrial control run. This run uses the GC5-central UM configuration, CMIP6 inputs, and includes several polar and tripolar bugfixes. | [UM](https://github.com/ACCESS-NRI/UM/tree/5491e5542e3f2f3fe828e0fbd3aa308c2baa8ea1) [OM3](https://github.com/ACCESS-NRI/ACCESS-OM3/tree/e1fc2a885bfd0740b9ae2b7a5e41482077397023) | 50 | <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-27-07-2026-PI-control/cm3-datastore/cm3-datastore.json', this)">Copy JSON path</button> <button class="copy-path-btn" onclick="copyDatastorePath('/g/data/zv30/non-cmip/ACCESS-CM3/cm3-run-27-07-2026-PI-control/cm3-datastore/cm3-datastore.csv', this)">Copy CSV path</button> |

# ACCESS-CM2 Experiments

The below list are key CM2 experiments that are being used to improve, evaluate and drive development for CM3. When evaluating CM3 we encourage comparisons between CM2 and CM3. 

| Base Configuration | Date completed | Description                                                                                                                                                                                                        | Model build | Length (years) | ESM Datastore <br/> (output path) |
|--------------------| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |-------------|----------------|------------------------------|
|                    |                | CM2 25km present day control run for comparison. We recommend comparing the first N years of this run to ACCESS-CM3 runs to assess the spin-up. |             |                | `/g/data/lg87/wgh581/cz861/` |
